<script setup lang="ts">

</script>

<template>
	<div class="-mx-4 my-4 flex flex-row gap-4">
		<div class="bg-gray-800 w-1 min-w-1 max-w-1">

		</div>
		<span class="italic q-text text-lg text-gray-800"><slot/></span>
	</div>

</template>

<style scoped>
.q-text{
	font-family: "Fira Sans Condensed";
}
</style>