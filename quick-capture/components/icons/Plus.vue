<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M14,7a1,1,0,0,0-1-1H8.25A.25.25,0,0,1,8,5.75V1A1,1,0,0,0,6,1V5.75A.25.25,0,0,1,5.75,6H1A1,1,0,0,0,1,8H5.75A.25.25,0,0,1,6,8.25V13a1,1,0,0,0,2,0V8.25A.25.25,0,0,1,8.25,8H13A1,1,0,0,0,14,7Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'Plus',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
