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
                d="M11,1h-.25a.25.25,0,0,0-.25.25V1.5A1.5,1.5,0,0,1,9,3H5A1.5,1.5,0,0,1,3.5,1.5V1.25A.25.25,0,0,0,3.25,1H3A1.5,1.5,0,0,0,1.5,2.5v10A1.5,1.5,0,0,0,3,14h8a1.5,1.5,0,0,0,1.5-1.5V2.5A1.5,1.5,0,0,0,11,1Z"
            />
            <rect x="4.5" width="5" height="2" rx="0.5" />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceFileClipboard',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
