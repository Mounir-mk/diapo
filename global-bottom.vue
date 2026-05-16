<script setup>
import { computed } from 'vue'
import { useNav } from '@slidev/client'

const { currentPage, total } = useNav()

// Slides masquées : 1 (cover), 3 (Section Partie I), 14 (Section Partie II)
const HIDE_ON = new Set([1, 3, 14, 23, 24, 25, 26])

// À partir de la slide 15, c'est Tahar (pages/16.md et suivantes)
const TAHAR_FROM = 15

const showBar = computed(() => !HIDE_ON.has(currentPage.value))

const presenter = computed(() =>
  currentPage.value >= TAHAR_FROM ? 'Tahar OTHMANE' : 'Mounir MEKOUI'
)

const partLabel = computed(() =>
  currentPage.value >= TAHAR_FROM
    ? 'Partie II — Éolien offshore & far-shore'
    : 'Partie I — Éolien terrestre'
)
</script>

<template>
  <transition name="bar-fade">
    <div v-if="showBar" class="bar-bottom">
      <!-- Logos institutions -->
      <div class="bar-left">
        <img src="/institutions/logo-urca.png" alt="URCA" class="logo logo-urca" />
        <span class="bar-sep">|</span>
        <img src="/institutions/logo-ithemm.png" alt="ITheMM" class="logo logo-ithemm" />
      </div>

      <!-- Titre + partie courante -->
      <div class="bar-center">
        <span class="bar-title">Énergie éolienne · Stage L3 URCA 2025/2026</span>
        <span class="bar-part">{{ partLabel }}</span>
      </div>

      <!-- Présentateur + numéro de slide -->
      <div class="bar-right">
        <span class="bar-presenter">{{ presenter }}</span>
        <span class="bar-pages">{{ currentPage }}&thinsp;/&thinsp;{{ total }}</span>
      </div>
    </div>
  </transition>
</template>

<style scoped>
.bar-bottom {
  position: fixed;
  bottom: 0;
  left: 0;
  right: 0;
  height: 30px;
  background: #f4f7fb;
  border-top: 1.5px solid #2c5f9e;
  color: #1a3358;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 14px;
  font-family: 'Inter', 'Segoe UI', sans-serif;
  z-index: 200;
  gap: 8px;
  box-shadow: 0 -1px 6px rgba(44, 95, 158, 0.08);
}

/* ── Logos ─────────────────────────────── */
.bar-left {
  display: flex;
  align-items: center;
  gap: 6px;
  flex-shrink: 0;
}

.logo {
  width: auto;
  object-fit: contain;
  display: block;
}

.logo-urca {
  height: 17px;
}

.logo-ithemm {
  height: 15px;
}

.bar-sep {
  font-size: 10px;
  opacity: 0.3;
  color: #2c5f9e;
}

/* ── Centre ─────────────────────────────── */
.bar-center {
  display: flex;
  flex-direction: column;
  align-items: center;
  flex: 1;
  min-width: 0;
  line-height: 1.25;
  overflow: hidden;
}

.bar-title {
  font-weight: 600;
  font-size: 9px;
  color: #1a3358;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  letter-spacing: 0.02em;
}

.bar-part {
  font-size: 8px;
  color: #2c5f9e;
  opacity: 0.75;
  white-space: nowrap;
  font-style: italic;
}

/* ── Droite ─────────────────────────────── */
.bar-right {
  display: flex;
  align-items: center;
  gap: 10px;
  flex-shrink: 0;
}

.bar-presenter {
  font-size: 9px;
  font-weight: 600;
  color: #1a3358;
  white-space: nowrap;
  letter-spacing: 0.01em;
}

.bar-pages {
  font-size: 9px;
  font-variant-numeric: tabular-nums;
  background: #2c5f9e;
  color: #fff;
  padding: 1px 7px;
  border-radius: 10px;
  white-space: nowrap;
  font-weight: 500;
  letter-spacing: 0.02em;
}

/* ── Transition douce à l'apparition ────── */
.bar-fade-enter-active,
.bar-fade-leave-active {
  transition: opacity 0.3s ease, transform 0.3s ease;
}

.bar-fade-enter-from,
.bar-fade-leave-to {
  opacity: 0;
  transform: translateY(4px);
}
</style>
