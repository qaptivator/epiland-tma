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
			<BaseButton
				label="Замовити Свято"
				variant="primary"
				><PartyPopperIcon
			/></BaseButton>
			<BaseButton
				label="Поповнити Картку"
				variant="primary"
				><CreditCardIcon
			/></BaseButton>
			<BaseButton label="Атракціони"><FerrisWheelIcon /></BaseButton>
			<BaseButton label="Кафе"><CoffeeIcon /></BaseButton>
			<BaseButton label="Зв'язатися з нами"><PhoneIcon /></BaseButton>
			<BaseButton label="Про нас"><InfoIcon /></BaseButton>
			<div class="flex-1" />
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
	PhoneIcon,
	InfoIcon,
} from 'lucide-vue-next'
</script>
