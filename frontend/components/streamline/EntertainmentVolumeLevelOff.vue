<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M6.69,1a1.35,1.35,0,0,0-.8.27L3.07,4.42a.27.27,0,0,1-.19.08H1.75A1.76,1.76,0,0,0,0,6.25v1.5A1.76,1.76,0,0,0,1.75,9.5H2.88a.27.27,0,0,1,.19.08l2.82,3.15a1.35,1.35,0,0,0,.8.27A1.31,1.31,0,0,0,8,11.69V2.31A1.31,1.31,0,0,0,6.69,1Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'EntertainmentVolumeLevelOff',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
