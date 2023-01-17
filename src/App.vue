<template>
  <n-config-provider :locale="zhCN">
    <router-view></router-view>
  </n-config-provider>
</template>
<script setup lang="ts">
import { zhCN } from 'naive-ui'
</script>
