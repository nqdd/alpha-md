<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <g>
            <path d="M12,12H2a1,1,0,0,0,0,2H12a1,1,0,0,0,0-2Z" />
            <path
                d="M2.05,10.39A1,1,0,0,0,3.39,10l.84-1.67A.51.51,0,0,1,4.68,8H9.32a.51.51,0,0,1,.45.28L10.61,10a1,1,0,1,0,1.78-.9L8.28.84A1.39,1.39,0,0,0,7,0,1.35,1.35,0,0,0,5.75.79L1.61,9.05A1,1,0,0,0,2.05,10.39ZM6.78,3.2A.23.23,0,0,1,7,3.06a.24.24,0,0,1,.22.14L8.45,5.64a.26.26,0,0,1,0,.24A.22.22,0,0,1,8.22,6H5.78a.25.25,0,0,1-.22-.12.25.25,0,0,1,0-.24Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceTextFormattingText',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
