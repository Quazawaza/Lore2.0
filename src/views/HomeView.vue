<script setup>

import Msg from '../components/Msg.vue'

</script>

<template>
  <Loader v-if="isLoading"/>
  <template v-else>
    <Msg></Msg>
  </template>
</template>