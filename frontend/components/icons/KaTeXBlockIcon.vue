<template>
    <svg :width="size" :height="size" viewBox="0 0 24 24">
        <path
            fill="currentColor"
            d="M12.187 4.14c-.964-.723-2.345-.07-2.398 1.134L9.712 7H12a1 1 0 1 1 0 2H9.623l-.393 8.85c-.13 2.931-3.593 4.41-5.801 2.479l-.087-.076a1 1 0 0 1 1.317-1.506l.087.076c.946.829 2.43.194 2.486-1.062L7.622 9H6a1 1 0 0 1 0-2h1.71l.08-1.815c.126-2.81 3.347-4.332 5.597-2.645l.213.16a1 1 0 1 1-1.2 1.6l-.213-.16Zm.895 8.906a.5.5 0 0 1 .693.225l.813 1.727l-3.295 3.295a1 1 0 0 0 1.414 1.414l2.786-2.786l.78 1.657a2.5 2.5 0 0 0 3.853.864l.51-.42a1 1 0 1 0-1.272-1.543l-.51.42a.5.5 0 0 1-.771-.172l-1.087-2.309l2.711-2.711a1 1 0 1 0-1.414-1.414l-2.202 2.202l-.506-1.075a2.5 2.5 0 0 0-3.467-1.126l-.6.33a1 1 0 0 0 .964 1.752l.6-.33Z"
        ></path>
    </svg>
</template>

<script lang="ts">
import { Component, Vue, Prop } from 'vue-property-decorator';

@Component
export default class ImageIcon extends Vue {
    @Prop({ default: 20 }) readonly size: number | undefined;
}
</script>
