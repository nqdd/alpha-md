<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <g>
            <circle cx="11.5" cy="2.5" r="2.5" />
            <path
                d="M7.51,2.74a.25.25,0,0,0-.25-.24H2a2,2,0,0,0-2,2V12a2,2,0,0,0,2,2H9.5a2,2,0,0,0,2-2V6.74a.25.25,0,0,0-.24-.25A4,4,0,0,1,7.51,2.74Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'PhoneNotificationApplication1',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
