<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <g>
            <rect x="5" y="1" width="9" height="7" rx="1.5" />
            <path
                d="M9.88,10.5H4.12A1.63,1.63,0,0,1,2.5,8.88V5.12a.63.63,0,0,1,1.25,0V8.88a.38.38,0,0,0,.37.37H9.88a.63.63,0,0,1,0,1.25Z"
            />
            <path
                d="M7.62,13h-6A1.63,1.63,0,0,1,0,11.38v-4a.63.63,0,1,1,1.25,0v4a.38.38,0,0,0,.37.37h6a.63.63,0,1,1,0,1.25Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceAlignLayers2',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
