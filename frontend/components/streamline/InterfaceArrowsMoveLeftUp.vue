<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M13.78,2.22l-2-2a.75.75,0,0,0-1.06,0l-2,2A.75.75,0,0,0,8.56,3a.74.74,0,0,0,.69.46h1a.25.25,0,0,1,.25.25v6.5a.25.25,0,0,1-.25.25H3.75a.25.25,0,0,1-.25-.25v-1a.75.75,0,0,0-1.28-.53l-2,2a.75.75,0,0,0,0,1.06l2,2a.75.75,0,0,0,1.28-.53v-1A.25.25,0,0,1,3.75,12h6.5A1.76,1.76,0,0,0,12,10.25V3.75a.25.25,0,0,1,.25-.25h1A.74.74,0,0,0,13.94,3,.75.75,0,0,0,13.78,2.22Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceArrowsMoveLeftUp',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
