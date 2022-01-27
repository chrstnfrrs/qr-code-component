<template>
  <QRComponent />
</template>

<script>
import QRComponent from './components/QRComponent.vue';

export default {
  name: 'App',
  components: {
    QRComponent,
  },
};
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css?family=Outfit');

html {
  font-family: Outfit, Helvetica, Arial, sans-serif;
  src: local('Outfit'), local('Outfit'), url(https://fonts.googleapis.com/css?family=Outfit) format('woff2');
  font-display: swap;
}

body {
  margin: 0;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color: hsl(212, 45%, 89%);
}

p {
  font-size: 0.9375rem;
}

#app {
  min-height: 100vh;
  min-width: 100vw;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
