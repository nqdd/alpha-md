<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M.29,7.71l6,6a1,1,0,0,0,1.42,0l6-6a1,1,0,1,0-1.42-1.42L8.43,10.16a.26.26,0,0,1-.28.05A.25.25,0,0,1,8,10V1A1,1,0,0,0,6,1v9a.25.25,0,0,1-.15.23.26.26,0,0,1-.28-.05L1.71,6.29A1,1,0,0,0,.29,7.71Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceArrowsDown',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
