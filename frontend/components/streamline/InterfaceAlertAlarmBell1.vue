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
                d="M7.75,12.5H6.25a.75.75,0,0,0,0,1.5h1.5a.75.75,0,0,0,0-1.5Z"
            />
            <path
                d="M3.69,1.36a.76.76,0,0,0,.17-1,.76.76,0,0,0-1-.17A6.78,6.78,0,0,0,0,5.62a.75.75,0,0,0,1.5,0A5.26,5.26,0,0,1,3.69,1.36Z"
            />
            <path
                d="M11.19.14a.76.76,0,0,0-1,.17.76.76,0,0,0,.17,1.05A5.26,5.26,0,0,1,12.5,5.62a.75.75,0,1,0,1.5,0A6.78,6.78,0,0,0,11.19.14Z"
            />
            <path
                d="M12,10a1,1,0,0,1-1-1V5.5a4,4,0,0,0-8,0V9a1,1,0,0,1-1,1,.5.5,0,0,0,0,1H12a.5.5,0,0,0,0-1Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceAlertAlarmBell1',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
