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
                d="M9.75,7.62H4.25a.62.62,0,1,1,0-1.24h5.5a.62.62,0,1,1,0,1.24Z"
            />
            <path
                d="M9.75,5.12H4.25a.62.62,0,1,1,0-1.24h5.5a.62.62,0,1,1,0,1.24Z"
            />
            <path
                d="M9.75,10.12H4.25a.62.62,0,1,1,0-1.24h5.5a.62.62,0,1,1,0,1.24Z"
            />
            <path
                d="M7,14a7,7,0,1,1,7-7A7,7,0,0,1,7,14ZM7,1.5A5.5,5.5,0,1,0,12.5,7,5.51,5.51,0,0,0,7,1.5Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceSettingMenuParallelHamburgerCircleAlternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
