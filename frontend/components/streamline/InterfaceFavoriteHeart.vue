<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M13.84,3.91A4,4,0,0,0,11,1.08,4.17,4.17,0,0,0,7.17,2.37a.25.25,0,0,1-.34,0A4.17,4.17,0,0,0,3,1.08,4,4,0,0,0,.16,3.91a3.9,3.9,0,0,0,1,3.87l5.52,5.09a.51.51,0,0,0,.68,0l5.53-5.11A3.87,3.87,0,0,0,13.84,3.91Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceFavoriteHeart',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
