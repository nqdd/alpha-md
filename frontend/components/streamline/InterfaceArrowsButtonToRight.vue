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
                d="M12.9,7a1.51,1.51,0,0,1-.44,1.06L6.81,13.71a1,1,0,0,1-1.41,0,1,1,0,0,1,0-1.42l5.11-5.11a.25.25,0,0,0,0-.36L5.4,1.71A1,1,0,0,1,5.4.29a1,1,0,0,1,1.41,0l5.65,5.65A1.51,1.51,0,0,1,12.9,7Z"
            />
            <path d="M3.1,1V13a1,1,0,0,1-2,0V1a1,1,0,0,1,2,0Z" />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceArrowsButtonToRight',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
