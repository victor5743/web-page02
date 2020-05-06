<template>
	<div class="bg-gray-900" id="app">
		<Sidebar />
	</div>
</template>

<script>
import Sidebar from './components/Sidebar.vue';

export default {
	name: 'App',
	components: {
		Sidebar,
	},
};
</script>

<style src="./assets/tailwind.css"></style>
