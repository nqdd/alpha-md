<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M9.73,3.75l2.1-2.52a.77.77,0,0,0,.1-.8A.75.75,0,0,0,11.25,0H3A1,1,0,0,0,2,1V13a1,1,0,0,0,2,0V7.5h7.25a.75.75,0,0,0,.68-.43.77.77,0,0,0-.1-.8ZM8.17,3.27a.75.75,0,0,0,0,1L9.31,5.59a.25.25,0,0,1-.2.41H4.25A.25.25,0,0,1,4,5.75v-4a.25.25,0,0,1,.25-.25H9.11a.25.25,0,0,1,.2.41Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'TravelMapFlagAlternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
