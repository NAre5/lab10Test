<template>
  <div id="app">
    <u><h1>My Beautiful site</h1></u>
    <mycomponent></mycomponent>
  </div>
</template>

<script>
import mycomponent from './components/my-component';
export default {
  name: "App",
  components: {
    mycomponent
  }
};
</script>
