<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M12,4A2,2,0,1,0,9,5.74a.25.25,0,0,1,.1.33A1.26,1.26,0,0,1,8,6.75H6a2.82,2.82,0,0,0-.92.16.28.28,0,0,1-.22,0,.26.26,0,0,1-.11-.21V4a.24.24,0,0,1,.14-.23,2,2,0,1,0-1.78,0A.24.24,0,0,1,3.25,4v6a.24.24,0,0,1-.14.23,2,2,0,1,0,1.78,0A.24.24,0,0,1,4.75,10V9.5A1.25,1.25,0,0,1,6,8.25H8A2.74,2.74,0,0,0,10.7,6a.28.28,0,0,1,.14-.18A2,2,0,0,0,12,4Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceHierarchy6',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
