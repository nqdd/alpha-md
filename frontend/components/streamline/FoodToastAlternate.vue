<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M11.5,0h-9A2.5,2.5,0,0,0,.91,4.43.25.25,0,0,1,1,4.62V13a1,1,0,0,0,1,1H12a1,1,0,0,0,1-1V4.62a.25.25,0,0,1,.09-.19A2.5,2.5,0,0,0,11.5,0ZM4.25,7.25a.75.75,0,0,1-.49-1.32l3.5-3a.75.75,0,0,1,1,1.14l-3.5,3A.76.76,0,0,1,4.25,7.25Zm6,1.07-3.5,3a.75.75,0,1,1-1-1.14l3.5-3a.75.75,0,0,1,1,1.14Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'FoodToastAlternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
