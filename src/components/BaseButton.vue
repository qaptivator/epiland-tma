<template>
	<button
		:class="[
			'w-full py-3 px-2 bg-white text-[#3c1889] border-[#3c1889] border-2 rounded-xl active:scale-95 transition-transform cursor-pointer flex gap-2 items-center font-bold uppercase',
			vertical
				? 'flex-col justify-center text-center'
				: 'flex-row justify-start',
		]"
	>
		<slot />

		<span :class="['leading-tight', vertical ? 'text-xs' : 'text-base']">
			{{ label }}
		</span>
	</button>
</template>

<script setup>
defineProps({
	label: String,
	vertical: {
		type: Boolean,
		default: false,
	},
})
</script>
