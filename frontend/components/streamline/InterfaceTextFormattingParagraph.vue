<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M14,.75A.76.76,0,0,0,13.25,0H4.75a4.75,4.75,0,0,0,0,9.5H5.5a.25.25,0,0,1,.25.25v3.5a.75.75,0,0,0,1.5,0V1.75A.25.25,0,0,1,7.5,1.5h1a.25.25,0,0,1,.25.25v11.5a.75.75,0,0,0,1.5,0V1.75a.25.25,0,0,1,.25-.25h2.75A.76.76,0,0,0,14,.75Zm-8.25,7A.25.25,0,0,1,5.5,8H4.75a3.25,3.25,0,0,1,0-6.5H5.5a.25.25,0,0,1,.25.25Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceTextFormattingParagraph',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
