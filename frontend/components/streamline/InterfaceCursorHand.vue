<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M10.58,5.64,7.77,5.15a.5.5,0,0,1-.42-.49V1.75a1.75,1.75,0,0,0-3.5,0V6.54a.24.24,0,0,1-.14.22l-.94.47a2.51,2.51,0,0,0-1.2,3.16l1.07,2.67A1.49,1.49,0,0,0,4,14h6.45A1.51,1.51,0,0,0,12,12.71l.61-4.27A2.49,2.49,0,0,0,10.58,5.64Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceCursorHand',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
