<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M13.85.15A.5.5,0,0,0,13.32,0L.32,5A.51.51,0,0,0,0,5.51.48.48,0,0,0,.34,6L6.1,7.9,8,13.66a.48.48,0,0,0,.46.34h0A.51.51,0,0,0,9,13.68l5-13A.5.5,0,0,0,13.85.15Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'TravelMapNavigationArrow1',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
