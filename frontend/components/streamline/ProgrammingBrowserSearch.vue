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
                d="M12.75,0H1.25A1.25,1.25,0,0,0,0,1.25v10.5A1.25,1.25,0,0,0,1.25,13h3a.75.75,0,0,0,0-1.5H1.75a.25.25,0,0,1-.25-.25v-7A.25.25,0,0,1,1.75,4h10.5a.25.25,0,0,1,.25.25v1a.75.75,0,0,0,1.5,0v-4A1.25,1.25,0,0,0,12.75,0Z"
            />
            <path
                d="M13.78,12.72,12.08,11a.24.24,0,0,1,0-.3A3.45,3.45,0,0,0,12.5,9,3.5,3.5,0,1,0,9,12.5,3.45,3.45,0,0,0,10.72,12a.24.24,0,0,1,.3,0l1.7,1.7a.75.75,0,0,0,1.06-1.06ZM9,11a2,2,0,1,1,2-2A2,2,0,0,1,9,11Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'ProgrammingBrowserSearch',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
