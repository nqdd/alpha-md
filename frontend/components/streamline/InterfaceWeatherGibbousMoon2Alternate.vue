<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M5.62,0A7,7,0,0,0,4.33.12a1,1,0,0,0-.58.34,10.21,10.21,0,0,0,0,13.08,1,1,0,0,0,.58.34A7,7,0,1,0,5.62,0Zm0,12a1.06,1.06,0,0,1-.88-.47,8.22,8.22,0,0,1,0-9.06A1.06,1.06,0,0,1,5.62,2a5,5,0,0,1,0,10Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceWeatherGibbousMoon2Alternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
