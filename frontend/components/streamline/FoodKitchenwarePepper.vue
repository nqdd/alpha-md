<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <g>
            <rect x="4.5" y="5.5" width="5" height="4.5" rx="0.25" />
            <path
                d="M9.5,11h-5a1,1,0,0,0-1,1v1.5A.5.5,0,0,0,4,14h6a.5.5,0,0,0,.5-.5V12A1,1,0,0,0,9.5,11Z"
            />
            <path
                d="M6.25,1.25A.25.25,0,0,1,6,1.5H4.5a1.4,1.4,0,0,0-.58.12A1.5,1.5,0,0,0,3,3a1.5,1.5,0,0,0,.92,1.38,1.4,1.4,0,0,0,.58.12h5a1.53,1.53,0,0,0,1.06-.44,1.5,1.5,0,0,0,0-2.12A1.53,1.53,0,0,0,9.5,1.5H8a.25.25,0,0,1-.25-.25V.75A.7.7,0,0,0,7.7.5.74.74,0,0,0,6.3.5a.7.7,0,0,0,0,.25Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'FoodKitchenwarePepper',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
