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
                d="M14,.75A.76.76,0,0,0,13.25,0h-5A.76.76,0,0,0,7.5.75a.76.76,0,0,0,.75.75h2.59a.25.25,0,0,1,.23.15.26.26,0,0,1-.06.28L8.72,4.22A.75.75,0,0,0,9.78,5.28L12.07,3a.26.26,0,0,1,.28-.06.25.25,0,0,1,.15.23V5.75a.75.75,0,0,0,1.5,0Z"
            />
            <path
                d="M.75,14h5a.75.75,0,0,0,0-1.5H3.16a.25.25,0,0,1-.23-.15A.26.26,0,0,1,3,12.07L5.28,9.78A.75.75,0,0,0,4.22,8.72L1.93,11a.26.26,0,0,1-.28.06.25.25,0,0,1-.15-.23V8.25A.76.76,0,0,0,.75,7.5.76.76,0,0,0,0,8.25v5A.76.76,0,0,0,.75,14Z"
            />
            <path
                d="M4.78,3.72A.75.75,0,1,0,3.72,4.78l5.5,5.5a.75.75,0,0,0,1.06-1.06Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceArrowsExpandDiagonal1',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
