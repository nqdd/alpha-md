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
                d="M13.73,8.35,12.11,2.06A2.74,2.74,0,0,0,9.45,0H4.55A2.74,2.74,0,0,0,1.89,2.07L.27,8.35A8.62,8.62,0,0,0,0,10.5,3.5,3.5,0,0,0,3.5,14h7A3.5,3.5,0,0,0,14,10.5,8.62,8.62,0,0,0,13.73,8.35ZM10.5,12.5h-7a2,2,0,0,1,0-4h7a2,2,0,0,1,0,4Z"
            />
            <path d="M7,11H3.5a.5.5,0,0,1,0-1H7a.5.5,0,0,1,0,1Z" />
            <circle cx="10" cy="10.5" r="1" />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'ComputerStorageHardDrive2',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
