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
                d="M5.62,2h-1a.25.25,0,0,1-.25-.25v-1a.75.75,0,0,0-1.5,0v1A.25.25,0,0,1,2.62,2h-1a.75.75,0,0,0,0,1.5h1a.25.25,0,0,1,.25.25v1a.75.75,0,0,0,1.5,0v-1a.25.25,0,0,1,.25-.25h1a.75.75,0,1,0,0-1.5Z"
            />
            <path
                d="M9.88,14A3.25,3.25,0,0,1,7.63,8.41V2.25a2.25,2.25,0,1,1,4.5,0V8.4A3.25,3.25,0,0,1,9.88,14Zm0-12.5a.75.75,0,0,0-.75.75v6.5a.77.77,0,0,1-.3.6,1.71,1.71,0,0,0-.7,1.4,1.75,1.75,0,0,0,3.5,0,1.72,1.72,0,0,0-.71-1.4.76.76,0,0,1-.29-.6V2.25A.76.76,0,0,0,9.88,1.5Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceWeatherTemperatureHot',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
