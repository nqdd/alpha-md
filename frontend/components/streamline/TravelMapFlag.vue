<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M9.61,3.91a.24.24,0,0,1,0-.32l2-2.36a.77.77,0,0,0,.1-.8A.75.75,0,0,0,11,0H3a.76.76,0,0,0-.75.75v12.5a.75.75,0,0,0,1.5,0V7.75A.25.25,0,0,1,4,7.5h7a.75.75,0,0,0,.68-.43.77.77,0,0,0-.1-.8Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'TravelMapFlag',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
