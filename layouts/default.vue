<script setup lang="ts">
</script>

<template>
	<div>
		<header>
			<nav class="bg-white border-gray-200 px-4 lg:px-6 py-2.5 dark:bg-gray-800 border-b-2">
				<div class="flex flex-wrap justify-between items-center mx-auto max-w-screen-xl">
					<NavigationLogo/>
					<div class="hidden justify-between items-center w-full lg:flex lg:w-auto lg:order-1">
						<ul class="flex flex-col mt-4 font-medium lg:flex-row lg:space-x-8 lg:mt-0">
							<li>
								<NavigationLink page="index" name="Главная" to="/"/>
							</li>
							<li>
								<NavigationLink page="developers" name="Разработчики" to="/developers"/>
							</li>
							<li>
								<NavigationLink page="risks" name="Риски" to="/risks"/>
							</li>
							<li>
								<NavigationLink page="forecast" name="Предсказания" to="/forecast"/>
							</li>
						</ul>
					</div>
				</div>
			</nav>
		</header>
		<div class="content overflow-y-auto">
			<slot/>
		</div>
	</div>
</template>

<style scoped>
.content {
	height: calc(100svh - 3.5rem);
}
</style>