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
                d="M10.75,14H3.25A1.76,1.76,0,0,1,1.5,12.25V1.75A1.76,1.76,0,0,1,3.25,0h7.5A1.76,1.76,0,0,1,12.5,1.75v10.5A1.76,1.76,0,0,1,10.75,14ZM3.25,1.5A.25.25,0,0,0,3,1.75v10.5a.25.25,0,0,0,.25.25h7.5a.25.25,0,0,0,.25-.25V1.75a.25.25,0,0,0-.25-.25Z"
            />
            <path
                d="M5.25,11a.76.76,0,0,1-.75-.75V3.75a.75.75,0,0,1,1.5,0v6.5A.76.76,0,0,1,5.25,11Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceEditAlignLeftVerticalAlternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
