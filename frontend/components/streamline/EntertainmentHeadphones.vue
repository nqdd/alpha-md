<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M13.14,7.67A.26.26,0,0,1,13,7.45V6.52a6,6,0,0,0-12,0v.93a.26.26,0,0,1-.14.22A1.5,1.5,0,0,0,0,9v3a1.5,1.5,0,0,0,1.5,1.5H3A1.5,1.5,0,0,0,4.5,12V9A1.5,1.5,0,0,0,3.21,7.54.26.26,0,0,1,3,7.29V6.52a4,4,0,0,1,8,0v.77a.26.26,0,0,1-.21.25A1.5,1.5,0,0,0,9.5,9v3a1.5,1.5,0,0,0,1.5,1.5h1.5A1.5,1.5,0,0,0,14,12V9A1.5,1.5,0,0,0,13.14,7.67Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'EntertainmentHeadphones',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
