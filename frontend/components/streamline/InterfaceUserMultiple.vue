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
                d="M9.25,1a2.81,2.81,0,0,0-.77.11.26.26,0,0,0-.16.15.24.24,0,0,0,0,.22A4.23,4.23,0,0,1,8.34,6a.24.24,0,0,0,0,.22.26.26,0,0,0,.16.15,2.81,2.81,0,0,0,.77.11,2.75,2.75,0,0,0,0-5.5Z"
            />
            <path
                d="M9.72,8,9.38,8a.27.27,0,0,0-.24.15.25.25,0,0,0,0,.27A6.59,6.59,0,0,1,11,13a2.86,2.86,0,0,1-.1.73.24.24,0,0,0,0,.22.26.26,0,0,0,.2.1H13a1,1,0,0,0,1-1V13A4.89,4.89,0,0,0,9.72,8Z"
            />
            <circle cx="4.75" cy="3.75" r="2.75" />
            <path
                d="M0,13a1,1,0,0,0,1,1H8.5a1,1,0,0,0,1-1V13A4.89,4.89,0,0,0,5.22,8,4.75,4.75,0,0,0,0,12.75Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceUserMultiple',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
