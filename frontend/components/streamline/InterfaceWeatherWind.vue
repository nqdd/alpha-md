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
                d="M7.5,5H.75a.75.75,0,0,1,0-1.5H7.5a1,1,0,0,0,0-2A.76.76,0,0,1,6.75.75.76.76,0,0,1,7.5,0a2.5,2.5,0,0,1,0,5Z"
            />
            <path
                d="M11.5,11.25a.75.75,0,0,1,0-1.5,1,1,0,0,0,0-2H2.75a.75.75,0,0,1,0-1.5H11.5a2.5,2.5,0,0,1,0,5Z"
            />
            <path
                d="M7.25,14a.75.75,0,0,1,0-1.5,1,1,0,0,0,0-2H1.75a.75.75,0,0,1,0-1.5h5.5a2.5,2.5,0,0,1,0,5Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceWeatherWind',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
