<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M10.53,11.75H3.47a3.5,3.5,0,0,1-.43-7,.27.27,0,0,0,.2-.14,4.15,4.15,0,0,1,7.52,0,.27.27,0,0,0,.2.14,3.5,3.5,0,0,1-.43,7Zm-7.06-5a1.5,1.5,0,0,0,0,3h7.06a1.5,1.5,0,0,0,0-3,1,1,0,0,0-.25,0A1,1,0,0,1,9.13,6,2.17,2.17,0,0,0,4.87,6a1,1,0,0,1-1.15.78A1,1,0,0,0,3.47,6.75Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceWeatherCloud1Alternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
