<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M.79,6.71a1,1,0,0,0,1.42,0L5.07,3.84a.26.26,0,0,1,.28,0A.25.25,0,0,1,5.5,4V9a5,5,0,0,0,5,5h2a1,1,0,0,0,0-2h-2a3,3,0,0,1-3-3V4a.25.25,0,0,1,.15-.23.26.26,0,0,1,.28,0l2.86,2.87a1,1,0,0,0,1.42-1.42l-5-5a1,1,0,0,0-1.42,0l-5,5A1,1,0,0,0,.79,6.71Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceArrowsBendUpLeft2',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
