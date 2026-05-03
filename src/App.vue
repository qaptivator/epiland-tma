<template>
	<div class="h-screen flex flex-col">
		<header
			class="flex p-4 justify-center items-center w-full bg-[#3c1889] h-10"
		>
			<img
				src="/logo.svg"
				alt="Logo"
				class="h-4 invert"
			/>
		</header>
		<main class="p-4 flex flex-col gap-4 h-full">
			<BaseButton label="Атракціони"><FerrisWheelIcon /></BaseButton>
			<BaseButton label="Кафе"><CoffeeIcon /></BaseButton>
			<div class="flex-1" />
			<div class="flex gap-4">
				<BaseButton
					vertical
					label="Замовити Свято"
					><PartyPopperIcon
				/></BaseButton>
				<BaseButton
					vertical
					label="Поповнити Картку"
					><CreditCardIcon
				/></BaseButton>
			</div>
		</main>
	</div>
</template>
<script setup>
import BaseButton from './components/BaseButton.vue'
import {
	HomeIcon,
	UserIcon,
	PartyPopperIcon,
	CreditCardIcon,
	FerrisWheelIcon,
	CoffeeIcon,
} from 'lucide-vue-next'
</script>
