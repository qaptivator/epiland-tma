<template>
	<!-- Your existing Header -->
	<header class="flex p-4 justify-center items-center w-full bg-[#3c1889]">
		<img
			src="/logo.svg"
			alt="Logo"
			class="h-4 invert"
		/>
	</header>

	<main class="p-4 flex flex-col gap-4">
		<!-- Now you can use your replicatable buttons! -->
		<BaseButton label="Замовити Свято" />
		<BaseButton label="Поповнити Картку" />
		<BaseButton label="Атракціони" />
	</main>
</template>

<script setup>
import BaseButton from './components/BaseButton.vue'
</script>
