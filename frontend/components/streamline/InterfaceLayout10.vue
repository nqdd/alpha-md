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
                d="M8.25.25A.25.25,0,0,0,8,0H1.94A1.94,1.94,0,0,0,0,1.94V12.06A1.94,1.94,0,0,0,1.94,14H8a.25.25,0,0,0,.25-.25Z"
            />
            <path
                d="M12.06,0H10a.25.25,0,0,0-.25.25v13.5A.25.25,0,0,0,10,14h2.06A1.94,1.94,0,0,0,14,12.06V1.94A1.94,1.94,0,0,0,12.06,0Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceLayout10',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
