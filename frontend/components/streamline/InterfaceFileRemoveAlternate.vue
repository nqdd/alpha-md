<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <g>
            <path d="M1,11H6A1,1,0,0,0,6,9H1a1,1,0,0,0,0,2Z" />
            <path
                d="M13.78,4,10,.22A.75.75,0,0,0,9.5,0H3.75A1.76,1.76,0,0,0,2,1.75v5.5a.25.25,0,0,0,.25.25h1a.25.25,0,0,0,.25-.25V1.75a.25.25,0,0,1,.25-.25H9.09a.26.26,0,0,1,.17.07l3.17,3.17a.26.26,0,0,1,.07.17v7.34a.25.25,0,0,1-.25.25H2.34a.25.25,0,0,0-.24.33A1.75,1.75,0,0,0,3.75,14h8.5A1.76,1.76,0,0,0,14,12.25V4.5A.75.75,0,0,0,13.78,4Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceFileRemoveAlternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
