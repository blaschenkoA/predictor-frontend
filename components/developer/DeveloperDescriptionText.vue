<script setup lang="ts">
import TextWithFont from "~/components/common/TextWithFont.vue";
</script>

<template>
	<h1 class="text-lg text-blue-800 py-1">
		<TextWithFont><slot/></TextWithFont>
	</h1>
</template>

<style scoped>
</style>