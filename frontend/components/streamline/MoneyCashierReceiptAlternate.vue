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
                d="M6.43,9a.27.27,0,0,0-.16.24v.42a.52.52,0,1,1-1,0V9.19A.26.26,0,0,0,5.07,9a1.71,1.71,0,0,1-.75-.54.52.52,0,1,1,.81-.64A.78.78,0,0,0,5.75,8a.64.64,0,0,0,.71-.54c0-.29-.32-.53-.71-.53A1.67,1.67,0,0,1,4,5.4,1.56,1.56,0,0,1,5.07,4a.26.26,0,0,0,.17-.24V3.37a.52.52,0,1,1,1,0v.34A.27.27,0,0,0,6.43,4a1.71,1.71,0,0,1,.75.54.51.51,0,0,1-.09.73.52.52,0,0,1-.72-.09.78.78,0,0,0-.62-.27A.65.65,0,0,0,5,5.4c0,.29.32.53.71.53A1.67,1.67,0,0,1,7.5,7.5,1.58,1.58,0,0,1,6.43,9Z"
            />
            <path
                d="M14,2.25A2.25,2.25,0,0,0,11.75,0H3A2.75,2.75,0,0,0,.25,2.75v10.5a.75.75,0,0,0,.38.65.74.74,0,0,0,.76,0l2-1.17a.26.26,0,0,1,.27,0l1.72,1.15a.76.76,0,0,0,.84,0l1.69-1.13a.28.28,0,0,1,.28,0l1.69,1.13a.72.72,0,0,0,.42.13.76.76,0,0,0,.75-.75v-7A.25.25,0,0,1,11.25,6h2A.76.76,0,0,0,14,5.25ZM9.5,11.38a.25.25,0,0,1-.13.22.24.24,0,0,1-.26,0l-.69-.46a.76.76,0,0,0-.84,0L5.89,12.26a.28.28,0,0,1-.28,0L3.92,11.13A.72.72,0,0,0,3.5,11a.79.79,0,0,0-.39.11l-1,.59a.26.26,0,0,1-.38-.22V2.75A1.25,1.25,0,0,1,3,1.5H9.31a.25.25,0,0,1,.19.09.23.23,0,0,1,.05.21,2.06,2.06,0,0,0-.05.45v9.13Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'MoneyCashierReceiptAlternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
