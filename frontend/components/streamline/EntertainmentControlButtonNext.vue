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
                d="M8.83,5.6,2.42.33A1.54,1.54,0,0,0,1.48,0,1.47,1.47,0,0,0,0,1.47H0V12.53a1.47,1.47,0,0,0,2.4,1.14L8.83,8.4a1.81,1.81,0,0,0,0-2.8Z"
            />
            <rect x="10.99" width="3" height="14" rx="1.25" />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'EntertainmentControlButtonNext',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
