<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M13.44,2.23a1.2,1.2,0,0,0-1.17-.11A13.28,13.28,0,0,1,7,3.25,13.28,13.28,0,0,1,1.73,2.12a1.2,1.2,0,0,0-1.17.11,1.24,1.24,0,0,0-.56,1v7.46a1.24,1.24,0,0,0,.56,1,1.24,1.24,0,0,0,1.18.12A12.91,12.91,0,0,1,7,10.75a13,13,0,0,1,5.27,1.14A1.26,1.26,0,0,0,14,10.73V3.27A1.24,1.24,0,0,0,13.44,2.23Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'ImagePhotoCompsitionHorizontal',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
