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
                d="M14,1.64A1.76,1.76,0,0,0,12.25-.11h-1a.75.75,0,0,0,0,1.5h1a.25.25,0,0,1,.25.25v7.5a.25.25,0,0,1-.25.25H1.75a.25.25,0,0,1-.25-.25V1.64a.25.25,0,0,1,.25-.25h1a.75.75,0,1,0,0-1.5h-1A1.76,1.76,0,0,0,0,1.64v7.5a1.75,1.75,0,0,0,1.75,1.75H5a.27.27,0,0,1,.21.12.26.26,0,0,1,0,.23l-.67,1.62a.75.75,0,0,0,.69,1h3.5a.75.75,0,0,0,.69-1l-.67-1.62a.26.26,0,0,1,0-.23A.27.27,0,0,1,9,10.89h3.25A1.75,1.75,0,0,0,14,9.14Z"
            />
            <path
                d="M9.5,2.89a.25.25,0,0,1-.25-.25v-2A.76.76,0,0,0,8.5-.11h-3a.76.76,0,0,0-.75.75v2a.25.25,0,0,1-.25.25.5.5,0,0,0-.5.5v2.5a2,2,0,0,0,2,2H8a2,2,0,0,0,2-2V3.39A.5.5,0,0,0,9.5,2.89ZM7.75,2.64a.25.25,0,0,1-.25.25h-1a.25.25,0,0,1-.25-.25v-1a.25.25,0,0,1,.25-.25h1a.25.25,0,0,1,.25.25Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'ComputerConnectionMonitorLock',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
