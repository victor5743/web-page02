<template>
	<div
		class="bg-gray-900 text-white flex min-h-screen font-roboto tracking-wider"
		id="app"
	>
		<Sidebar />
		<Content />
	</div>
</template>

<script>
import Sidebar from './components/Sidebar.vue';
import Content from './components/Content.vue';

export default {
	name: 'App',
	components: {
		Sidebar,
		Content,
	},
};
</script>
