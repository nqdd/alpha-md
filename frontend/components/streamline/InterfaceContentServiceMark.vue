<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M7,0a7,7,0,1,0,7,7A7,7,0,0,0,7,0ZM4,6.25h.5a1.75,1.75,0,0,1,0,3.5H3a.75.75,0,0,1,0-1.5H4.5a.25.25,0,0,0,0-.5H4a1.75,1.75,0,0,1,0-3.5H5.5a.75.75,0,0,1,0,1.5H4a.25.25,0,0,0,0,.5ZM11.75,9a.75.75,0,0,1-1.5,0V7.12A.13.13,0,0,0,10.17,7,.12.12,0,0,0,10,7,.75.75,0,0,1,9,7a.12.12,0,0,0-.14,0,.13.13,0,0,0-.08.12V9a.75.75,0,0,1-1.5,0V5a.74.74,0,0,1,.46-.69.75.75,0,0,1,.82.16l.79.79a.25.25,0,0,0,.36,0l.79-.79a.75.75,0,0,1,.82-.16.74.74,0,0,1,.46.69Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceContentServiceMark',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
