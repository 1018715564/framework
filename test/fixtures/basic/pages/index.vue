<template>
  <div>
    <Head>
      <Title>Basic fixture</Title>
    </Head>
    <h1>Hello Vue 3</h1>
    <div>Config: {{ $config.testConfig }}</div>
  </div>
</template>

<script setup>
const $config = useRuntimeConfig()
</script>
