<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M10.89,3.16a.5.5,0,0,0-.71-.33A1.51,1.51,0,0,1,8,1.5,1.52,1.52,0,0,1,8.17.82a.52.52,0,0,0,0-.44A.51.51,0,0,0,7.84.11,3.35,3.35,0,0,0,7,0,4,4,0,0,0,3,4V8.5A1.5,1.5,0,0,0,4.5,10a.25.25,0,0,1,.25.25v1.5a2.25,2.25,0,0,0,4.5,0v-1.5A.25.25,0,0,1,9.5,10,1.5,1.5,0,0,0,11,8.5V4A3.35,3.35,0,0,0,10.89,3.16ZM7.75,11.75a.75.75,0,0,1-1.5,0v-1.5A.25.25,0,0,1,6.5,10h1a.25.25,0,0,1,.25.25Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'FoodIceCream1',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
