<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M7,0a7,7,0,1,0,7,7A7,7,0,0,0,7,0ZM9.44,6a.74.74,0,0,1-.69.46H8a.25.25,0,0,0-.25.25V10a.75.75,0,0,1-1.5,0V6.75A.25.25,0,0,0,6,6.5H5.25A.74.74,0,0,1,4.56,6a.75.75,0,0,1,.16-.82L6.47,3.47a.75.75,0,0,1,1.06,0L9.28,5.22A.75.75,0,0,1,9.44,6Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceArrowsUpCircle1',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
