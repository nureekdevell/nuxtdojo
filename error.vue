<template>
	<div class="mt-7 text-center card">
		<p class="mt-7">{{ error.statusCode }}</p>
		<p class="mt-7">{{ error.message }}</p>
		<button @click="handClearError" class="btn my-t">Go Home...</button>
	</div>
</template>

<script setup>
defineProps(['error']);

const handClearError = () => clearError({ redirect: '/' });
</script>

<style scoped></style>
