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
                d="M10.17,7.62l-4,2.75a.7.7,0,0,1-.42.13A.76.76,0,0,1,5,9.75V4.25a.74.74,0,0,1,.4-.66.76.76,0,0,1,.77,0l4,2.75a.75.75,0,0,1,0,1.24Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'EntertainmentControlButtonPlayCircleAlternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
