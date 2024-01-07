<!-- @format -->

<template>
	<div>
		<header class="shadow-sm bg-white">
			<nav class="container mx-auto p-4 flex justify-between">
				<NuxtLink class="text-2xl font-bold" to="/products"
					>Nuxt Dojo Products</NuxtLink
				>
			</nav>
		</header>

		<div class="container flex mx-auto p-4">
			<slot />
		</div>
		<footer>
			<div class="container mx-auto p-4 flex">
				<ul class="flex gap-4">
					<li><NuxtLink to="/">Home</NuxtLink></li>
					<li><NuxtLink to="/about">About</NuxtLink></li>
					<li><NuxtLink to="/products">Products</NuxtLink></li>
				</ul>
			</div>
		</footer>
	</div>
</template>

<script setup></script>

<style></style>
