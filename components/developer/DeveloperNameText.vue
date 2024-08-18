<script setup lang="ts">

import TextWithFont from "~/components/common/TextWithFont.vue";
</script>

<template>
	<h1 class="text-4xl text-blue-600 pb-4 pt-2">
		<TextWithFont>
			<slot/>
		</TextWithFont>
	</h1>
</template>

<style scoped>
</style>