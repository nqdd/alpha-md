<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M7,0a7,7,0,1,0,7,7A7,7,0,0,0,7,0ZM8,12.5a1,1,0,1,1,1-1A1,1,0,0,1,8,12.5Zm-1.25-3a1.22,1.22,0,0,0-1.15.83l-.11.57a.77.77,0,0,1-.74.6H4.6A.77.77,0,0,1,4,10.6L4.14,10v0L5,5.6a.76.76,0,1,1,1.48.3L6.12,7.72a.25.25,0,0,0,.06.22A.27.27,0,0,0,6.4,8a2,2,0,0,1,.41,0A2.5,2.5,0,1,0,4.25,5.5a.75.75,0,0,1-1.5,0,4,4,0,1,1,4,4Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'MoneyCurrencyPolkaDotCircle',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
