<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M12.25,2.5H10.5V1.75A1.76,1.76,0,0,0,8.75,0h-7A1.76,1.76,0,0,0,0,1.75v9.5A2.75,2.75,0,0,0,2.75,14h5a2.75,2.75,0,0,0,2.75-2.75V10h1.75A1.76,1.76,0,0,0,14,8.25v-4A1.76,1.76,0,0,0,12.25,2.5ZM3.75,9.25a.75.75,0,0,1-1.5,0v-5a.75.75,0,0,1,1.5,0Zm4,0a.75.75,0,0,1-1.5,0v-5a.75.75,0,0,1,1.5,0Zm4.75-1a.25.25,0,0,1-.25.25h-1.5a.25.25,0,0,1-.25-.25v-4A.25.25,0,0,1,10.75,4h1.5a.25.25,0,0,1,.25.25Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'FoodDrinksBeerMugAlternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
