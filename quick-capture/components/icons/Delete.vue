<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M8.71,7.19a.28.28,0,0,1,0-.38l5-5a1.06,1.06,0,0,0,0-1.52,1.06,1.06,0,0,0-1.52,0l-5,5a.28.28,0,0,1-.38,0l-5-5A1.06,1.06,0,0,0,.32.32a1.06,1.06,0,0,0,0,1.52l5,5a.28.28,0,0,1,0,.38l-5,5a1.06,1.06,0,0,0,0,1.52,1.06,1.06,0,0,0,1.52,0l5-5a.28.28,0,0,1,.38,0l5,5a1.07,1.07,0,0,0,1.52-1.52Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceDelete1',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
