<template>
    <svg :width="size" :height="size" viewBox="0 0 24 24">
        <path
            fill="currentColor"
            d="M22 3H7c-.69 0-1.23.35-1.59.88L0 12l5.41 8.11c.36.53.9.89 1.59.89h15c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zm0 16H7.07L2.4 12l4.66-7H22v14zm-11.59-2L14 13.41L17.59 17L19 15.59L15.41 12L19 8.41L17.59 7L14 10.59L10.41 7L9 8.41L12.59 12L9 15.59z"
        ></path>
    </svg>
</template>

<script lang="ts">
import { Component, Vue, Prop } from 'vue-property-decorator';

@Component({
    name: 'BackspaceIcon',
})
export default class BackspaceIcon extends Vue {
    @Prop({ default: 20 }) readonly size: number | undefined;
}
</script>
