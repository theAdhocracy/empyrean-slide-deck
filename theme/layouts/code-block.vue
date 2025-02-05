<script setup lang="ts">
const props = defineProps({
	codepen: {
		type: String,
		required: true,
	},
	title: {
		type: String,
		required: true,
	},
});
</script>

<template>
	<div class="slidev-layout code-block">
		<slot />
		<iframe
			height="300"
			style="width: 100%"
			scrolling="no"
			:title="title"
			:src="`https://codepen.io/theadhocracy/embed/${codepen}?default-tab=result`"
			frameborder="no"
			loading="lazy"
			allowtransparency="true"
			allowfullscreen="true"
		>
			See the Pen
			<a :href="`https://codepen.io/theadhocracy/pen/${codepen}`"
				>{ title }</a
			>
			by Murray (<a href="https://codepen.io/theadhocracy"
				>@theadhocracy</a
			>) on <a href="https://codepen.io">CodePen</a>.
		</iframe>
	</div>
</template>
