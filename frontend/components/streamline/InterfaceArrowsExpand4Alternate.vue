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
                d="M10,14H1.75A1.76,1.76,0,0,1,0,12.25V4a.76.76,0,0,1,.75-.75A.76.76,0,0,1,1.5,4v8.25a.25.25,0,0,0,.25.25H10A.75.75,0,0,1,10,14Z"
            />
            <path
                d="M12.5,0h-8A1.5,1.5,0,0,0,3,1.5v8A1.5,1.5,0,0,0,4.5,11h8A1.5,1.5,0,0,0,14,9.5v-8A1.5,1.5,0,0,0,12.5,0Zm-1,6.75a.74.74,0,0,1-1.29.51l-1-1a.24.24,0,0,0-.35,0L7,8A.75.75,0,1,1,6,7l1.8-1.8a.24.24,0,0,0,0-.35l-1-1a.76.76,0,0,1-.23-.53.76.76,0,0,1,.75-.75h3.5a.76.76,0,0,1,.75.75Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceArrowsExpand4Alternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
