<template>
    <svg :width="size" :height="size" viewBox="0 0 24 24">
        <path
            fill="currentColor"
            d="m4 12l1.41 1.41L11 7.83V20h2V7.83l5.58 5.59L20 12l-8-8l-8 8z"
        ></path>
    </svg>
</template>

<script lang="ts">
import { Component, Vue, Prop } from 'vue-property-decorator';

@Component
export default class ArrowUpIcon extends Vue {
    @Prop({ default: 20 }) readonly size: number | undefined;
}
</script>
