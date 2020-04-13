<template>
  <div id="app">
    <iframe allowtransparency frameborder='0' height='160' scrolling='no' src='https://www.strava.com/clubs/623241/latest-rides/aa1a47045f65f38d41da8fb35e23d8373357ed43?show_rides=false' width='300'></iframe>
    <iframe allowtransparency frameborder='0' height='160' scrolling='no' src='https://www.strava.com/clubs/622520/latest-rides/a026c406d22eda97af1ca7cbe30088c44c038e3a?show_rides=false' width='300'></iframe>
    <iframe allowtransparency frameborder='0' height='160' scrolling='no' src='https://www.strava.com/clubs/232813/latest-rides/e6d07cf4484d12cc95df22b3f102db968bcf871b?show_rides=false' width='300'></iframe>
    <iframe allowtransparency frameborder='0' height='160' scrolling='no' src='https://www.strava.com/clubs/623691/latest-rides/f6fbaef2c1fb8b2290b0b30f9bd0e5349d178812?show_rides=false' width='300'></iframe>
    <iframe allowtransparency frameborder='0' height='160' scrolling='no' src='https://www.strava.com/clubs/622664/latest-rides/c217105223a08ff63c92409a7a8275465b373eb0?show_rides=false' width='300'></iframe>
    <iframe allowtransparency frameborder='0' height='160' scrolling='no' src='https://www.strava.com/clubs/623310/latest-rides/5c9c40a114b3db1cf3370e2106ff2c73b1f9a1c3?show_rides=false' width='300'></iframe>
    <iframe allowtransparency frameborder='0' height='160' scrolling='no' src='https://www.strava.com/clubs/623368/latest-rides/4787a207557a9963a3e5ad439b448ba17d87b9f0?show_rides=false' width='300'></iframe>
  </div>
</template>

<script>

export default {
  name: 'App',
  
}
</script>

<style>
body{
  background: whitesmoke;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}

iframe {
  margin: 20px;
}

</style>
