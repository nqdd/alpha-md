<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M7,14A5.08,5.08,0,0,1,2,8.83C2,6.34,5.49,1.37,6.19.4A1,1,0,0,1,7.81.4c.7,1,4.19,5.94,4.19,8.43A5.08,5.08,0,0,1,7,14ZM7.21,3.07a.24.24,0,0,0-.42,0C5.45,5.11,4,7.7,4,8.83A3.09,3.09,0,0,0,7,12a3.09,3.09,0,0,0,3-3.16C10,7.7,8.55,5.11,7.21,3.07Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceWeatherRainDropAlternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
