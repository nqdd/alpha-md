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
                d="M14,2a2,2,0,0,0-2-2H2A2,2,0,0,0,0,2V12a2,2,0,0,0,2,2H12a2,2,0,0,0,2-2Zm-2,9.75a.25.25,0,0,1-.25.25H2.25A.25.25,0,0,1,2,11.75V2.25A.25.25,0,0,1,2.25,2h2.5A.25.25,0,0,1,5,2.25V5.5a.5.5,0,0,0,.5.5h3A.5.5,0,0,0,9,5.5V2.25A.25.25,0,0,1,9.25,2h2.5a.25.25,0,0,1,.25.25Z"
            />
            <path d="M7.25,9a.75.75,0,0,0,0,1.5h2.5a.75.75,0,0,0,0-1.5Z" />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'ShippingBox1Alternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
