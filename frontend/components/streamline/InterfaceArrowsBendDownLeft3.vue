<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M.79,7.29a1,1,0,0,1,1.42,0l2.86,2.87a.26.26,0,0,0,.28.05A.25.25,0,0,0,5.5,10V5a5,5,0,0,1,5-5h2a1,1,0,0,1,0,2h-2a3,3,0,0,0-3,3v5a.25.25,0,0,0,.15.23.26.26,0,0,0,.28-.05l2.86-2.87a1,1,0,1,1,1.42,1.42l-5,5a1,1,0,0,1-1.42,0l-5-5A1,1,0,0,1,.79,7.29Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceArrowsBendDownLeft3',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
