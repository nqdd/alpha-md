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
            <path d="M6,9.25a1,1,0,0,1-2,0V4.75a1,1,0,0,1,2,0Z" />
            <path d="M10,9.25a1,1,0,0,1-2,0V4.75a1,1,0,0,1,2,0Z" />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'EntertainmentControlButtonPauseCircleAlternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
