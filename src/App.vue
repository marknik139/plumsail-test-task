<template>
  <div id="app">
    <weather-app />
  </div>
</template>

<script>
import WeatherApp from "@/components/WeatherApp.vue";

export default {
  name: 'weatherCards',
  components: { WeatherApp },
}

</script>
<style>
body {
  display: flex;
  justify-content: center;
  align-items: center;
  font-family: Roboto, Arial, sans-serif;
}
</style>
