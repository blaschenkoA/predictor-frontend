<script setup lang="ts">
import SelectedLink from "~/components/navigation/SelectedLink.vue";
import UnselectedLink from "~/components/navigation/UnselectedLink.vue";

const router = useRouter()

const props = defineProps<{
	page: string,
	name: string,
	to: string
}>()
</script>

<template>
	<SelectedLink v-if="router.currentRoute.value.name == props.page"
	              :name="props.name"
	              :page="props.page"
	              :to="props.to"/>
	<UnselectedLink v-else
	                :name="props.name"
	                :page="props.page"
	                :to="props.to"/>
</template>

<style scoped>

</style>