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
                d="M13.56,13.56a1.49,1.49,0,0,0,0-2.12L10.87,8.75a.26.26,0,0,1,0-.3,5.58,5.58,0,0,0,.68-2.7A5.75,5.75,0,1,0,5.75,11.5a5.58,5.58,0,0,0,2.7-.68.26.26,0,0,1,.3,0l2.69,2.69a1.5,1.5,0,0,0,2.12,0ZM1.5,5.75A4.25,4.25,0,1,1,5.75,10,4.26,4.26,0,0,1,1.5,5.75Z"
            />
            <path
                d="M7.44,6.73A1.61,1.61,0,0,0,5.75,5.21c-.37,0-.69-.24-.69-.52s.32-.51.69-.51a.75.75,0,0,1,.59.26.52.52,0,0,0,.71.08.5.5,0,0,0,.08-.7,1.66,1.66,0,0,0-.72-.52.26.26,0,0,1-.16-.23V3a.5.5,0,0,0-.5-.5.5.5,0,0,0-.5.5v.07a.25.25,0,0,1-.16.24,1.53,1.53,0,0,0-1,1.39A1.61,1.61,0,0,0,5.75,6.21c.37,0,.69.24.69.52s-.32.52-.69.52A.78.78,0,0,1,5.15,7a.5.5,0,0,0-.7-.09.5.5,0,0,0-.08.7,1.6,1.6,0,0,0,.72.53.24.24,0,0,1,.16.23v.15a.5.5,0,0,0,.5.5.5.5,0,0,0,.5-.5V8.36a.27.27,0,0,1,.16-.24A1.52,1.52,0,0,0,7.44,6.73Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'MoneyCashSearchDollar',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
