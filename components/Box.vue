<script setup>
defineProps({
  type: {
    type: String,
    default: 'info',
  }
})
</script>
<template>
  <div class="custom-box" :class="'box-' + type">
    <slot />
  </div>
</template>
<style scoped>
.custom-box {
  padding: 0.75rem 1rem;
  border-radius: 0.25rem;
  margin: 1rem 0;
  font-size: 0.70rem;
  line-height: 1.4;
}

/* On force le style pour les balises générées par le Markdown à l'intérieur */
.custom-box :deep(p) {
  margin: 0 !important;
  font-size: 1em !important; 
  line-height: inherit !important;
  font-style: italic !important;
}

.box-info {
  background: #f4f7fb;
  border-left: 4px solid #2c5f9e;
  color: #1a3358;
}
.box-key {
  background: #f0fdf4;
  border-left: 4px solid #10b981;
  color: #064e3b;
}
.box-alert {
  background: #fffbeb;
  border-left: 4px solid #f59e0b;
  color: #78350f;
}
</style>
