<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M11.25,3.5H2.75a2.75,2.75,0,0,0,0,5.5H3a.26.26,0,0,1,.22.13c.58,1,2.6,1.37,3.79,1.37,2.48,0,3.5-.75,3.83-1.37A.24.24,0,0,1,11.05,9h.2a2.75,2.75,0,0,0,0-5.5ZM3.11,7.27a.26.26,0,0,1-.25.23H2.75a1.25,1.25,0,0,1,0-2.5h.31a.23.23,0,0,1,.18.08.26.26,0,0,1,.07.19ZM8,7.75H6a.75.75,0,0,1,0-1.5H8a.75.75,0,0,1,0,1.5Zm3.25-.25h-.11a.25.25,0,0,1-.25-.23l-.2-2a.22.22,0,0,1,.06-.19A.26.26,0,0,1,10.94,5h.31a1.25,1.25,0,0,1,0,2.5Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'HealthMedicalFluMask',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
