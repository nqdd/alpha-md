<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M10.75,0H3.25A1.25,1.25,0,0,0,2,1.25v11.5A1.25,1.25,0,0,0,3.25,14h7.5A1.25,1.25,0,0,0,12,12.75V1.25A1.25,1.25,0,0,0,10.75,0ZM7,12.5a1,1,0,1,1,1-1A1,1,0,0,1,7,12.5Zm3-4a.5.5,0,0,1-.5.5h-5A.5.5,0,0,1,4,8.5v-6A.5.5,0,0,1,4.5,2h5a.5.5,0,0,1,.5.5Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'CatergoriesPhone',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
