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
                d="M12,0H3A2,2,0,0,0,1,2V9.48a.29.29,0,0,1,0,.09L.09,12A1.5,1.5,0,0,0,1.5,14,1.74,1.74,0,0,0,1.89,14L5.38,13H12a2,2,0,0,0,2-2V2A2,2,0,0,0,12,0Zm.5,11a.5.5,0,0,1-.5.5H5.32a.69.69,0,0,0-.2,0l-3.62,1,1-2.58a.8.8,0,0,0,0-.26V2A.5.5,0,0,1,3,1.5h9a.5.5,0,0,1,.5.5Z"
            />
            <path
                d="M9.75,4.5A1.75,1.75,0,0,0,8,6.25a.25.25,0,0,1-.25.25H7.22a.2.2,0,0,1-.16-.07A.22.22,0,0,1,7,6.28v0A1.75,1.75,0,1,0,5.25,8h4.5a1.75,1.75,0,0,0,0-3.5Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'EntertainmentRecordingTapeBubbleSquareAlternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
