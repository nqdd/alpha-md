<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M11.23,13.68a1,1,0,0,1-1.42.05c-.42-.4-1.48-1.42-2.65-2.71a.22.22,0,0,0-.32,0c-1.17,1.29-2.23,2.31-2.65,2.71a1,1,0,0,1-1.38-1.46c.86-.8,1.83-1.8,2.74-2.83a.26.26,0,0,0,0-.32C4.17,7.36,3,5.44,3,4A3.83,3.83,0,0,1,7,0a3.83,3.83,0,0,1,4,4c0,1.44-1.17,3.36-2.56,5.12a.26.26,0,0,0,0,.32c.91,1,1.88,2,2.74,2.83A1,1,0,0,1,11.23,13.68ZM7,2A1.85,1.85,0,0,0,5,4,7.63,7.63,0,0,0,6.8,7.44a.25.25,0,0,0,.4,0A7.63,7.63,0,0,0,9,4,1.85,1.85,0,0,0,7,2Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'HealthMedicalRibbon1',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
