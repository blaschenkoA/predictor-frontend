<script setup lang="ts">
const props = defineProps<{
	paras: string[]
}>()
</script>

<template>
	<ul>
		<li v-for="para in paras" class="my-1.5 ms-6 point list-decimal text-lg tracking-wide">{{para}}</li>
	</ul>
</template>

<style scoped>
.point {
	font-family: "Fira Sans Condensed";
}
</style>