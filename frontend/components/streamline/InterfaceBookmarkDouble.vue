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
                d="M8,3H3A1.5,1.5,0,0,0,1.5,4.5v9a.48.48,0,0,0,.29.45.49.49,0,0,0,.54-.07l3-2.58a.24.24,0,0,1,.32,0l3,2.58A.52.52,0,0,0,9,14,.54.54,0,0,0,9.21,14a.48.48,0,0,0,.29-.45v-9A1.5,1.5,0,0,0,8,3Z"
            />
            <path
                d="M11.75,11.25A.76.76,0,0,1,11,10.5V1.75a.25.25,0,0,0-.25-.25H5A.76.76,0,0,1,4.25.75.76.76,0,0,1,5,0h5.75A1.76,1.76,0,0,1,12.5,1.75V10.5A.76.76,0,0,1,11.75,11.25Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceBookmarkDouble',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
