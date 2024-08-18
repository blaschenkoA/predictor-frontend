<template>
	<div>
		<NuxtRouteAnnouncer/>
		<NuxtLayout>
			<NuxtPage/>
		</NuxtLayout>
	</div>
</template>

<style>
.page-enter-active,
.page-leave-active {
	transition: all 0.4s;
}

.page-enter-from,
.page-leave-to {
	opacity: 0;
	filter: blur(1rem);
}

body {
	overflow:hidden;
	height: 100%;
	margin: 0;
	padding: 0;
}
</style>