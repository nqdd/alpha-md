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
                d="M13.9,8.84,10.06,3.73a1.5,1.5,0,0,0-2.15,0L.12,13.05a.49.49,0,0,0-.07.54.51.51,0,0,0,.45.29h13a.5.5,0,0,0,.5-.5V9.14A.51.51,0,0,0,13.9,8.84ZM11.19,10a.94.94,0,0,1-1,0l-.8-.56a1,1,0,0,0-1.08,0L7.46,10a.92.92,0,0,1-1,0L5.59,9.5a.5.5,0,0,1-.11-.74l3.1-3.69a.5.5,0,0,1,.78,0l2.82,3.68a.5.5,0,0,1-.13.73Z"
            />
            <path
                d="M3,5.62A2.75,2.75,0,1,1,5.75,2.88,2.75,2.75,0,0,1,3,5.62ZM3,1.38a1.5,1.5,0,1,0,1.5,1.5A1.5,1.5,0,0,0,3,1.38Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'TravelPlacesMountain',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
