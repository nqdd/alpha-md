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
                d="M13.74,7.06,11.93,1.23A1.72,1.72,0,0,0,10.26,0H3.74A1.74,1.74,0,0,0,2.06,1.23L.26,7.06A5.73,5.73,0,0,0,0,8.75v3.5A1.76,1.76,0,0,0,1.75,14h10.5A1.76,1.76,0,0,0,14,12.25V8.75A5.73,5.73,0,0,0,13.74,7.06ZM12.5,12.25a.25.25,0,0,1-.25.25H1.75a.25.25,0,0,1-.25-.25V8.75a.25.25,0,0,1,.25-.25h10.5a.25.25,0,0,1,.25.25Z"
            />
            <path d="M7,11H3.5a.5.5,0,0,1,0-1H7a.5.5,0,0,1,0,1Z" />
            <circle cx="10" cy="10.5" r="1" />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'ComputerStorageHardDrive1',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
