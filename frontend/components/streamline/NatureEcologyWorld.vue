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
                d="M14,7.54a.5.5,0,0,0-.5-.54H7.41L6,7.53A.92.92,0,0,0,5.53,9l1.1,1.47a.3.3,0,0,1,0,.15v1.23A.23.23,0,0,1,6.6,12a.31.31,0,0,1-.2.07,5.1,5.1,0,0,1-4.47-4.6A.5.5,0,0,0,1.43,7H.52a.52.52,0,0,0-.37.16A.52.52,0,0,0,0,7.54a7,7,0,0,0,14,0Z"
            />
            <path
                d="M1.28,4.28,2.57,3a.25.25,0,0,1,.36,0L6,6A.75.75,0,0,0,7,6,.75.75,0,0,0,7,5L5.74,3.68a.25.25,0,0,1,0-.36L7.28,1.78A.75.75,0,0,0,6.22.72L4.68,2.26a.25.25,0,0,1-.36,0l-1-1a.75.75,0,0,0-1.06,0l-2,2A.75.75,0,0,0,1.28,4.28Z"
            />
            <path
                d="M9.31,5H10a.25.25,0,0,1,.25.25V5.5a.75.75,0,0,0,1.5,0V5.25A.25.25,0,0,1,12,5h.69a.5.5,0,0,0,.43-.27.65.65,0,0,0,0-.56L11.45.32a.48.48,0,0,0-.9,0L8.86,4.17a.65.65,0,0,0,0,.56A.5.5,0,0,0,9.31,5Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'NatureEcologyWorld',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
