<template>
  <div id="app">
    <iframe allowtransparency frameborder='0' height='160' scrolling='no' src='https://www.strava.com/clubs/623241/latest-rides/aa1a47045f65f38d41da8fb35e23d8373357ed43?show_rides=false' width='300'></iframe>
    <iframe allowtransparency frameborder='0' height='160' scrolling='no' src='https://www.strava.com/clubs/622520/latest-rides/a026c406d22eda97af1ca7cbe30088c44c038e3a?show_rides=false' width='300'></iframe>
    <iframe allowtransparency frameborder='0' height='160' scrolling='no' src='https://www.strava.com/clubs/232813/latest-rides/e6d07cf4484d12cc95df22b3f102db968bcf871b?show_rides=false' width='300'></iframe>
  </div>
</template>

<script>

export default {
  name: 'App',
  
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

iframe:not(:last-child) {
  margin-bottom: 20px;
}

</style>
