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
                d="M12.35,6.28,6.22.15A.48.48,0,0,0,5.83,0a.49.49,0,0,0-.37.2L.29,7.1A1.46,1.46,0,0,0,.42,9l3.09,3.09a1.44,1.44,0,0,0,1,.42,1.46,1.46,0,0,0,.86-.29L12.3,7a.53.53,0,0,0,.2-.37A.53.53,0,0,0,12.35,6.28Z"
            />
            <path
                d="M11,12.5a9.42,9.42,0,0,1,1.05-2.67.5.5,0,0,1,.45-.27.48.48,0,0,1,.44.27A9.19,9.19,0,0,1,14,12.5a1.5,1.5,0,0,1-3,0Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceEditFlllColor',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
