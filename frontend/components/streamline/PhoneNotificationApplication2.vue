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
                d="M10,9A2.5,2.5,0,0,1,7.5,6.5a2.46,2.46,0,0,1,.42-1.36.28.28,0,0,0,0-.28A2.46,2.46,0,0,1,7.5,3.5V2.75a.25.25,0,0,0-.25-.25H2a2,2,0,0,0-2,2V12a2,2,0,0,0,2,2H9.5a2,2,0,0,0,2-2V8.94a.24.24,0,0,0-.12-.21.25.25,0,0,0-.25,0A2.39,2.39,0,0,1,10,9Z"
            />
            <g>
                <path d="M10,5.5a1,1,0,1,0,1,1A1,1,0,0,0,10,5.5Z" />
                <path
                    d="M10,0A1,1,0,0,0,9,1V3.5a1,1,0,0,0,2,0V1A1,1,0,0,0,10,0Z"
                />
            </g>
        </g>
    </svg>
</template>
<script>
export default {
    name: 'PhoneNotificationApplication2',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
