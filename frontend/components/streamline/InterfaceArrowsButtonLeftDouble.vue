<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <g>
            <path
                d="M7.5,13.71a1,1,0,0,0,0-1.42L2.38,7.18a.27.27,0,0,1,0-.36L7.5,1.71A1,1,0,0,0,7.5.29a1,1,0,0,0-1.41,0L.44,5.94a1.49,1.49,0,0,0,0,2.12l5.65,5.65A1,1,0,0,0,7.5,13.71Z"
            />
            <path
                d="M13.71,12.29,8.59,7.18a.25.25,0,0,1,0-.36l5.12-5.11A1,1,0,1,0,12.29.29L6.65,5.94a1.49,1.49,0,0,0,0,2.12l5.64,5.65a1,1,0,0,0,1.42-1.42Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceArrowsButtonLeftDouble',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
