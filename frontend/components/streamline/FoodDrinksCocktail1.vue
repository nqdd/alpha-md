<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M12.16,1.91A1.25,1.25,0,0,0,11.1,0H2.9A1.25,1.25,0,0,0,1.84,1.91L6.17,8.84a.53.53,0,0,1,.08.27v3.14A.25.25,0,0,1,6,12.5H4.5a.75.75,0,0,0,0,1.5h5a.75.75,0,0,0,0-1.5H8a.25.25,0,0,1-.25-.25V9.11a.53.53,0,0,1,.08-.27Zm-2-.41a.23.23,0,0,1,.21.13.23.23,0,0,1,0,.25l-.94,1.5a.25.25,0,0,1-.21.12H4.74a.25.25,0,0,1-.21-.12l-.94-1.5a.23.23,0,0,1,0-.25A.23.23,0,0,1,3.8,1.5Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'FoodDrinksCocktail1',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
