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
                d="M7,14a7,7,0,1,1,7-7A7,7,0,0,1,7,14ZM7,1.5A5.5,5.5,0,1,0,12.5,7,5.51,5.51,0,0,0,7,1.5Z"
            />
            <circle cx="9" cy="5" r="1" />
            <circle cx="5" cy="5" r="1" />
            <path
                d="M9.64,10.25A.77.77,0,0,1,9,9.94,2.5,2.5,0,0,0,5,9.94a.75.75,0,1,1-1.22-.88,4,4,0,0,1,6.5,0,.76.76,0,0,1-.17,1A.79.79,0,0,1,9.64,10.25Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'MailSmileySadFaceAlternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
