<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <g>
            <circle cx="7" cy="7" r="1.5" />
            <path
                d="M14,12.75A1.25,1.25,0,0,1,12.75,14h-5a.75.75,0,0,1,0-1.5h4.5a.25.25,0,0,0,.25-.25V7.75a.75.75,0,0,1,1.5,0Z"
            />
            <path
                d="M.75,7A.76.76,0,0,1,0,6.25v-5A1.25,1.25,0,0,1,1.25,0h5A.76.76,0,0,1,7,.75a.76.76,0,0,1-.75.75H1.75a.25.25,0,0,0-.25.25v4.5A.76.76,0,0,1,.75,7Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceArrowsDiagonalScrollPoint2',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
