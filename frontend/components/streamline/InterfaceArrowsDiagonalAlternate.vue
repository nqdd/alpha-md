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
                d="M10,4.25V.75A.76.76,0,0,0,9.19,0H5.75A.75.75,0,0,0,5,.75a.74.74,0,0,0,.24.55l1,1a.24.24,0,0,1,0,.35L1,8A.75.75,0,1,0,2,9l5.3-5.29a.24.24,0,0,1,.35,0l1,1,0,0h0A.72.72,0,0,0,9.25,5,.76.76,0,0,0,10,4.25Z"
            />
            <path
                d="M4,9.75v3.5a.76.76,0,0,0,.81.75H8.25A.75.75,0,0,0,9,13.25a.74.74,0,0,0-.24-.55l-1-1a.24.24,0,0,1,0-.35L13,6A.75.75,0,0,0,12,5l-5.3,5.29a.24.24,0,0,1-.35,0l-1-1,0,0h0A.72.72,0,0,0,4.75,9,.76.76,0,0,0,4,9.75Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceArrowsDiagonalAlternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
