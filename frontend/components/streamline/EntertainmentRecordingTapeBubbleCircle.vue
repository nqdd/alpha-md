<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <g>
            <circle cx="9.75" cy="7" r="0.75" />
            <circle cx="4.25" cy="7" r="0.75" />
            <path
                d="M7,0A7,7,0,0,0,0,7a6.89,6.89,0,0,0,1,3.55.25.25,0,0,1,0,.22L0,13.32a.51.51,0,0,0,.09.5A.5.5,0,0,0,.59,14L4,13.37a.22.22,0,0,1,.14,0A7,7,0,1,0,7,0ZM9.75,9.25H4.25A2.25,2.25,0,1,1,6.5,7a2.3,2.3,0,0,1,0,.45.23.23,0,0,0,0,.21.25.25,0,0,0,.19.09h.62a.25.25,0,0,0,.19-.09.23.23,0,0,0,0-.21A2.3,2.3,0,0,1,7.5,7,2.25,2.25,0,1,1,9.75,9.25Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'EntertainmentRecordingTapeBubbleCircle',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
