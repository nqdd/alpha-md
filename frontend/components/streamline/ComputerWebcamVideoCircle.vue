<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M7,0a7,7,0,1,0,7,7A7,7,0,0,0,7,0Zm3.5,8.39a.49.49,0,0,1-.22.41.53.53,0,0,1-.46.06l-.73-.33a.26.26,0,0,0-.23,0,.23.23,0,0,0-.11.2A.76.76,0,0,1,8,9.5H4.25a.76.76,0,0,1-.75-.75V5.25a.76.76,0,0,1,.75-.75H8a.76.76,0,0,1,.75.75.23.23,0,0,0,.11.2.26.26,0,0,0,.23,0l.72-.32h0a.53.53,0,0,1,.46.06.49.49,0,0,1,.22.41Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'ComputerWebcamVideoCircle',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
