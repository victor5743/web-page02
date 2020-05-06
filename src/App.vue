<template>
	<div class="bg-gray-900 text-white flex min-h-screen" id="app">
		<Sidebar />
		<div class="w-full mx-24">
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat illum eveniet quod
			maiores quia? Nulla, quis dolores modi repudiandae tempora, dolore incidunt ullam
			totam rerum nam ipsa officiis earum cum.
		</div>
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
