<script setup lang="ts">

import TextWithFont from "~/components/common/TextWithFont.vue";
</script>

<template>
	<div>
		<NuxtLink to="https://t.me/default_predictor_bot" target="_blank">
			<div class="transition duration-150 ease-in-out hover:bg-blue-700 px-6 py-6 w-fit bg-blue-600 max-w-96 items-center content-center rounded-3xl flex flex-1 flex-col gap-8">
				<Icon name="mingcute:telegram-fill" class="text-white w-full size-32"/>
				<span class="text-lg tracking-wide text-center text-white font-semibold">
					<TextWithFont>
						С информацией о предсказаниях вы можете ознакомиться в нашем Telegram боте!
					</TextWithFont>
				</span>
			</div>
		</NuxtLink>
	</div>


</template>

<style scoped>
</style>