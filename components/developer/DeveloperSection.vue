<script setup lang="ts">
const props = defineProps<{
	imgSrc: string
}>()
</script>

<template>
	<div class="w-full flex flex-row gap-8 px-16 py-10">
		<NuxtImg fit="cover" :src=props.imgSrc width="300" height="300" class="rounded-3xl"></NuxtImg>
		<div class="flex flex-col">
			<slot/>
		</div>

	</div>
</template>

<style scoped>

</style>