<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <g>
            <rect x="7.75" y="4.75" width="6.25" height="3.75" rx="0.25" />
            <rect y="4.75" width="6.25" height="3.75" rx="0.25" />
            <path
                d="M8,10a.25.25,0,0,0-.25.25v3.5A.25.25,0,0,0,8,14h4.06A1.94,1.94,0,0,0,14,12.06V10.25a.25.25,0,0,0-.25-.25Z"
            />
            <path
                d="M6.25,10.25A.25.25,0,0,0,6,10H.25a.25.25,0,0,0-.25.25v1.81A1.94,1.94,0,0,0,1.94,14H6a.25.25,0,0,0,.25-.25Z"
            />
            <path
                d="M13.75,3.25A.25.25,0,0,0,14,3V1.94A1.94,1.94,0,0,0,12.06,0H1.94A1.94,1.94,0,0,0,0,1.94V3a.25.25,0,0,0,.25.25Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceLayout8',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
