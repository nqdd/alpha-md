<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M7,0a7,7,0,1,0,7,7A7,7,0,0,0,7,0ZM9.74,9.74a.87.87,0,0,1-1.24,0L7.18,8.41a.27.27,0,0,0-.36,0L5.5,9.74a.88.88,0,0,1-1.24,0A.85.85,0,0,1,4,9.12a.87.87,0,0,1,.26-.62L5.59,7.18a.27.27,0,0,0,0-.36L4.26,5.5A.88.88,0,0,1,5.5,4.26L6.82,5.59a.27.27,0,0,0,.36,0L8.5,4.26A.88.88,0,1,1,9.74,5.5L8.41,6.82a.27.27,0,0,0,0,.36L9.74,8.5a.87.87,0,0,1,.26.62A.85.85,0,0,1,9.74,9.74Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceDeleteCircle',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
