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
                d="M3.75,7.5V7.39a.32.32,0,0,0,0-.14,3.5,3.5,0,1,1,6.06,0,.31.31,0,0,0,0,.13v.87A.25.25,0,0,0,10,8.5h.75l.42,0a.28.28,0,0,0,.25-.12A5.5,5.5,0,1,0,3.34,9.82a.24.24,0,0,0,.27,0,.23.23,0,0,0,.14-.22Z"
            />
            <path
                d="M12.75,12a2,2,0,0,0-2-2H8.5a.25.25,0,0,1-.25-.25V7.5a1.5,1.5,0,0,0-3,0v6.25A.25.25,0,0,0,5.5,14h7a.25.25,0,0,0,.25-.25Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceIdFingerPrintScan',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
