<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M7,0a7,7,0,1,0,7,7A7,7,0,0,0,7,0ZM4.75,9.25a.75.75,0,0,1-1.5,0V4.75a.75.75,0,0,1,1.5,0Zm6,0a.75.75,0,0,1-.42.67.74.74,0,0,1-.78-.07l-3-2.25a.75.75,0,0,1,0-1.2l3-2.25a.74.74,0,0,1,.78-.07.75.75,0,0,1,.42.67Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'EntertainmentControlButtonPreviousCircle',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
