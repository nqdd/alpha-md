<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M7.71.29a1,1,0,0,0-1.42,0l-6,6a1,1,0,0,0,0,1.42l6,6a1,1,0,1,0,1.42-1.42L3.84,8.43a.26.26,0,0,1,0-.28A.25.25,0,0,1,4,8h9a1,1,0,0,0,0-2H4a.25.25,0,0,1-.23-.15.26.26,0,0,1,0-.28L7.71,1.71A1,1,0,0,0,7.71.29Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceArrowsLeft',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
