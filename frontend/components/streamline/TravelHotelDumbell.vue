<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M12.5,3.5h-2A1.5,1.5,0,0,0,9,5v.75A.25.25,0,0,1,8.75,6H5.25A.25.25,0,0,1,5,5.75V5A1.5,1.5,0,0,0,3.5,3.5h-2A1.5,1.5,0,0,0,0,5V9a1.5,1.5,0,0,0,1.5,1.5h2A1.5,1.5,0,0,0,5,9V8.25A.25.25,0,0,1,5.25,8h3.5A.25.25,0,0,1,9,8.25V9a1.5,1.5,0,0,0,1.5,1.5h2A1.5,1.5,0,0,0,14,9V5A1.5,1.5,0,0,0,12.5,3.5Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'TravelHotelDumbell',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
