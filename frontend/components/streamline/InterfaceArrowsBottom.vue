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
                d="M6.29,9.71a1,1,0,0,0,1.41,0L12.21,5.2a1,1,0,0,0,0-1.42,1,1,0,0,0-1.41,0L8.42,6.16a.25.25,0,0,1-.27,0A.25.25,0,0,1,8,6V1A1,1,0,0,0,6,1V6a.26.26,0,0,1-.16.23.25.25,0,0,1-.27,0L3.2,3.79a1,1,0,0,0-1.41,0,1,1,0,0,0,0,1.42Z"
            />
            <path d="M3.5,14h7a1,1,0,0,0,0-2h-7a1,1,0,0,0,0,2Z" />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceArrowsBottom',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
