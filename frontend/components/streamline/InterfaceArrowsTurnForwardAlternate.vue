<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M10.71.79l3,3a1,1,0,0,1,0,1.42l-3,3a1,1,0,0,1-1.42,0A1,1,0,0,1,9,7.5V5.75a.25.25,0,0,0-.25-.25H5.12A3.08,3.08,0,0,0,2.06,7.9,3,3,0,0,0,5,11.5H9a1,1,0,0,1,0,2H5.22A5.16,5.16,0,0,1,0,9,5,5,0,0,1,5,3.5H8.75A.25.25,0,0,0,9,3.25V1.5A1,1,0,0,1,9.29.79,1,1,0,0,1,10.71.79Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceArrowsTurnForwardAlternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
