<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M13.78,2.22l-2-2A.75.75,0,0,0,11,.06a.74.74,0,0,0-.46.69v1a.25.25,0,0,1-.25.25H3.75A1.76,1.76,0,0,0,2,3.75v6.5a.25.25,0,0,1-.25.25h-1A.74.74,0,0,0,.06,11a.75.75,0,0,0,.16.82l2,2a.75.75,0,0,0,1.06,0l2-2A.75.75,0,0,0,5.44,11a.74.74,0,0,0-.69-.46h-1a.25.25,0,0,1-.25-.25V3.75a.25.25,0,0,1,.25-.25h6.5a.25.25,0,0,1,.25.25v1a.75.75,0,0,0,1.28.53l2-2A.75.75,0,0,0,13.78,2.22Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceArrowsMoveRightDown',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
