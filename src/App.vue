<template>
	<img alt="Vue logo" src="./assets/amuzil400x400.png">
	<HelloWorld msg="Welcome to Our Brand New Site"/>
</template>

<script lang="ts">
import {Options, Vue} from 'vue-class-component';
import HelloWorld from './components/HelloWorld.vue';

@Options({
	components: {
		HelloWorld,
	},
})
export default class App extends Vue {
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
</style>
