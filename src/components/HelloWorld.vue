<template>
	<div :user="user" :favorites="favorites"></div>
</template>

<script>
	export default {
		name: 'HelloWorld',
		data() {
			return {
				user: {
					name: 'John',
					age: 25,
				},
				favorites: ['Pizza', 'Marbles', 'Birds'],
			};
		},
	};
</script>
