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
                d="M6.5,13.71a1,1,0,0,1,0-1.42l5.12-5.11a.27.27,0,0,0,0-.36L6.5,1.71A1,1,0,0,1,6.5.29a1,1,0,0,1,1.41,0l5.65,5.65a1.49,1.49,0,0,1,0,2.12L7.91,13.71A1,1,0,0,1,6.5,13.71Z"
            />
            <path
                d="M.29,12.29,5.41,7.18a.25.25,0,0,0,0-.36L.29,1.71A1,1,0,0,1,1.71.29L7.35,5.94a1.49,1.49,0,0,1,0,2.12L1.71,13.71A1,1,0,0,1,.29,12.29Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceArrowsButtonRightDuoble',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
