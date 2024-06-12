<script setup lang="ts">
import './List.scss'
</script>
<template>
  <div>
    <ul class="listContent">
      <li class="listCheck"><img src="../../assets/img/check.svg" /> <slot /></li>
    </ul>
  </div>
</template>
