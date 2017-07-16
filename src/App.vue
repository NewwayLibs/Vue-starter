<template>
	<div id="app">
		<img src="./assets/logo.png">
		<router-view></router-view>
		<links></links>
	</div>
</template>

<script>
  import Links from './components/Links.vue'

  export default {
    name: 'app',
    components: {
      Links
    }
  }
</script>

<style>
	#app {
		font-family: 'Avenir', Helvetica, Arial, sans-serif;
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
		text-align: center;
		color: #2c3e50;
		margin-top: 60px;
	}
</style>
