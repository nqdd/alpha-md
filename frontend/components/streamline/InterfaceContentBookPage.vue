<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M10.88,0H2.12a.79.79,0,0,0-.39.11.75.75,0,0,0-.35.64v9.5a1.73,1.73,0,0,0,1,1.56l4,2a1.7,1.7,0,0,0,.79.19,1.83,1.83,0,0,0,.92-.26,1.76,1.76,0,0,0,.83-1.49A.25.25,0,0,1,9.12,12h1.76a1.75,1.75,0,0,0,1.74-1.75V1.75A1.74,1.74,0,0,0,10.88,0Zm.24,10.25a.25.25,0,0,1-.24.25H9.12a.25.25,0,0,1-.24-.25V4.37a1.76,1.76,0,0,0-1-1.57L6.25,2a.25.25,0,0,1,.11-.47h4.52a.25.25,0,0,1,.24.25Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceContentBookPage',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
