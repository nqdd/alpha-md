<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M14,1.54A1.5,1.5,0,0,0,12.5,0H1.5A1.5,1.5,0,0,0,0,1.54V4.46a10.13,10.13,0,0,0,6.46,9.4,1.51,1.51,0,0,0,1.08,0h0A10.13,10.13,0,0,0,14,4.46ZM8.12,7A.27.27,0,0,0,8,7.2V9A1,1,0,0,1,6,9V7.2A.27.27,0,0,0,5.88,7,2.25,2.25,0,1,1,8.12,7Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceLockShield',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
