<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M14,7a7,7,0,1,0-7,7A7,7,0,0,0,14,7ZM9.28,8.78,7.53,10.53a.75.75,0,0,1-1.06,0L4.72,8.78A.75.75,0,0,1,4.56,8a.74.74,0,0,1,.69-.46H6a.25.25,0,0,0,.25-.25V4a.75.75,0,0,1,1.5,0V7.25A.25.25,0,0,0,8,7.5h.75A.74.74,0,0,1,9.44,8,.75.75,0,0,1,9.28,8.78Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceArrowsDownCircle1',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
