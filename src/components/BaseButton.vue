<template>
	<button
		class="w-full py-3 bg-white text-[#3c1889] rounded-xl active:scale-95 transition-transform cursor-pointer"
	>
		{{ label }}
	</button>
</template>

<script setup>
defineProps(['label'])
</script>

<style scoped>
/* Any button-specific polish goes here */
button {
	/* Inherits Montserrat from body, but we ensure it's bold */
	font-weight: 700;
	text-transform: uppercase;
}
</style>
