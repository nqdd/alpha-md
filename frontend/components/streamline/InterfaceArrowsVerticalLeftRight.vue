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
                d="M3,10.41.33,7.79a1.11,1.11,0,0,1,0-1.58L3,3.59A.74.74,0,0,1,4,3.59.75.75,0,0,1,4,4.65L1.84,6.82a.24.24,0,0,0,0,.35L4,9.35A.75.75,0,0,1,3,10.41Z"
            />
            <path
                d="M10,10.41a.75.75,0,0,1,0-1.06l2.17-2.18a.24.24,0,0,0,0-.35L10,4.65a.75.75,0,0,1,0-1.06.74.74,0,0,1,1.06,0l2.62,2.62a1.11,1.11,0,0,1,0,1.58l-2.62,2.62A.75.75,0,0,1,10,10.41Z"
            />
            <path
                d="M7,14a.76.76,0,0,1-.75-.75V.75a.75.75,0,0,1,1.5,0v12.5A.76.76,0,0,1,7,14Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceArrowsVerticalLeftRight',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
