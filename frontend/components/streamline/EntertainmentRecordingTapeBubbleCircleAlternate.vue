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
                d="M7,0A7,7,0,0,0,.79,10.24a.23.23,0,0,1,0,.2L.08,12.38a1.17,1.17,0,0,0,.2,1.19A1.17,1.17,0,0,0,1.41,14l2.82-.51a.22.22,0,0,1,.14,0A6.78,6.78,0,0,0,7,14,7,7,0,0,0,7,0ZM7,12.5A5.38,5.38,0,0,1,4.71,12a.85.85,0,0,0-.31-.06H4.26l-2.59.47.7-1.88a.73.73,0,0,0-.06-.66A5.5,5.5,0,1,1,7,12.5Z"
            />
            <path
                d="M9.25,5.25A1.75,1.75,0,0,0,7.5,7a.25.25,0,0,1-.25.25H6.72a.2.2,0,0,1-.16-.07A.22.22,0,0,1,6.5,7V7A1.75,1.75,0,1,0,4.75,8.75h4.5a1.75,1.75,0,0,0,0-3.5Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'EntertainmentRecordingTapeBubbleCircleAlternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
