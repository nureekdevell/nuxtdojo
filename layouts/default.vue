<!-- @format -->

<template>
	<div>
		<header class="shadow-sm bg-white">
			<nav class="container mx-auto p-4 flex justify-between">
				<NuxtLink class="text-2xl font-bold" to="/">Dily</NuxtLink>
				<ul class="flex gap-4 items-center">
					<li class="text-lg"><NuxtLink to="/">Home</NuxtLink></li>
					<li class="text-lg"><NuxtLink to="/about">About</NuxtLink></li>
					<li class="text-lg btn">
						<NuxtLink to="/products">Products</NuxtLink>
					</li>
				</ul>
			</nav>
		</header>

		<div class="container flex mx-auto p-4">
			<slot />
		</div>
	</div>
</template>

<script setup></script>

<style>
.router-link-exact-active {
	color: #12b488;
}
</style>
