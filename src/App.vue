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
		<BaseButton label="Замовити Свято"><PartyPopperIcon /></BaseButton>
		<BaseButton label="Поповнити Картку"><CreditCardIcon /></BaseButton>
		<BaseButton label="Атракціони"><FerrisWheelIcon /></BaseButton>
	</main>
</template>

<script setup>
import BaseButton from './components/BaseButton.vue'
import {
	HomeIcon,
	UserIcon,
	PartyPopperIcon,
	CreditCardIcon,
	FerrisWheelIcon,
} from 'lucide-vue-next'
</script>
