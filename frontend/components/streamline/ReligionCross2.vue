<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M11.5,5a1,1,0,0,0-1-1H8.25A.25.25,0,0,1,8,3.75V1A1,1,0,0,0,6,1V3.75A.25.25,0,0,1,5.75,4H3.5a1,1,0,0,0,0,2H5.75A.25.25,0,0,1,6,6.25V13a1,1,0,0,0,2,0V6.25A.25.25,0,0,1,8.25,6H10.5A1,1,0,0,0,11.5,5Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'ReligionCross2',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
