<script setup lang="ts">
import TextWithFont from "~/components/common/TextWithFont.vue";

const props = defineProps<{
	page: string
	name: string
	to: string
}>()
</script>

<template>
	<NuxtLink :to="props.to"
	          class="uppercase tracking-wide nav-link-text block py-2 pr-4 pl-3 text-blue-600 font-bold rounded bg-primary-200 lg:bg-transparent lg:text-primary-700 lg:p-0 dark:text-white"
	          aria-current="page">
		<TextWithFont>
			{{props.name}}
		</TextWithFont>
	</NuxtLink>
</template>

<style scoped>
</style>