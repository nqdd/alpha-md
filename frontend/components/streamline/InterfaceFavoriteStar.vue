<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M13.68,6.39A1,1,0,0,0,13.1,4.6L9.65,4.08a.22.22,0,0,1-.18-.14L7.94.85a1.09,1.09,0,0,0-1.88,0L4.5,4a.3.3,0,0,1-.19.14L.9,4.6A1,1,0,0,0,.32,6.39L2.8,8.84a.23.23,0,0,1,.07.22l-.58,3.41a1,1,0,0,0,1.52,1.1L6.91,12a.31.31,0,0,1,.23,0l3.05,1.61a1,1,0,0,0,1.1-.08,1,1,0,0,0,.42-1L11.14,9a.26.26,0,0,1,.07-.22Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceFavoriteStar',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
