<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <g>
            <path
                d="M7,14a7,7,0,1,1,7-7A7,7,0,0,1,7,14ZM7,1.5A5.5,5.5,0,1,0,12.5,7,5.51,5.51,0,0,0,7,1.5Z"
            />
            <path
                d="M4.75,10a.74.74,0,0,1-.53-.22.75.75,0,0,1,0-1.06l4.5-4.5A.75.75,0,0,1,9.78,5.28l-4.5,4.5A.74.74,0,0,1,4.75,10Z"
            />
            <circle cx="5" cy="5" r="1" />
            <circle cx="9" cy="9" r="1" />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'ShoppingStoreDiscountPercentCircleAlternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
