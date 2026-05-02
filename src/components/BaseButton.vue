<template>
	<button
		class="w-full py-3 px-2 bg-white text-[#3c1889] rounded-xl active:scale-95 transition-transform cursor-pointer flex gap-2 text-base whitespace-nowrap items-center justify-start"
	>
		<slot />
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
