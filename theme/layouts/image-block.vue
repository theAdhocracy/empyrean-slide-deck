<script setup lang="ts">
const props = defineProps({
	image: {
		type: String,
		required: true,
	},
	alt: {
		type: String,
		required: true,
	},
	caption: {
		type: String,
		required: false,
	},
});
</script>

<template>
	<div class="slidev-layout image-block">
		<slot />
		<figure>
			<img :src="image" :alt="alt" />
			<figcaption v-if="caption">
				{{ caption }}
			</figcaption>
		</figure>
	</div>
</template>
