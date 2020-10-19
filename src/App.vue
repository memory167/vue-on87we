<template>
	<div id="app">
		<HelloWorld msg="Welcome to Your Vue.js App" />
		<div class="title">
			<p>title</p>
		</div>
	</div>
</template>

<script>
	import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
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
	}

	.title {
		width: 60px;
		height: 60px;
		color: red;
	}
</style>