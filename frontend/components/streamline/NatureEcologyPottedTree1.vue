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
                d="M6.07,6.87a.26.26,0,0,1,.18.24V8a.75.75,0,0,0,1.5,0V7.11a.26.26,0,0,1,.18-.24,3.5,3.5,0,1,0-1.86,0Zm.18-2.25a.75.75,0,0,1,1.5,0v1.5a.75.75,0,1,1-1.5,0Z"
            />
            <path
                d="M9.5,9.5h-5a.52.52,0,0,0-.38.17.53.53,0,0,0-.12.4l.5,3.5A.51.51,0,0,0,5,14H9a.51.51,0,0,0,.5-.43l.5-3.5a.53.53,0,0,0-.12-.4A.52.52,0,0,0,9.5,9.5Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'NatureEcologyPottedTree1',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
