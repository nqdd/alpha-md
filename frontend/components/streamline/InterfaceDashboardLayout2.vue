<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <g>
            <circle cx="7" cy="7" r="3" />
            <path
                d="M1,5A1,1,0,0,1,0,4V2A2,2,0,0,1,2,0H4A1,1,0,0,1,4,2H2.25A.25.25,0,0,0,2,2.25V4A1,1,0,0,1,1,5Z"
            />
            <path
                d="M13,5a1,1,0,0,1-1-1V2.25A.25.25,0,0,0,11.75,2H10a1,1,0,0,1,0-2h2a2,2,0,0,1,2,2V4A1,1,0,0,1,13,5Z"
            />
            <path
                d="M4,14H2a2,2,0,0,1-2-2V10a1,1,0,0,1,2,0v1.75a.25.25,0,0,0,.25.25H4a1,1,0,0,1,0,2Z"
            />
            <path
                d="M12,14H10a1,1,0,0,1,0-2h1.75a.25.25,0,0,0,.25-.25V10a1,1,0,0,1,2,0v2A2,2,0,0,1,12,14Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceDashboardLayout2',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
