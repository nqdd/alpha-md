<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M7,0a7,7,0,1,0,7,7A7,7,0,0,0,7,0Zm3,9.5a1,1,0,0,1-2,0V8.25A.25.25,0,0,0,7.75,8H6.25A.25.25,0,0,0,6,8.25V9.5a1,1,0,0,1-2,0v-5a1,1,0,0,1,2,0V5.75A.25.25,0,0,0,6.25,6h1.5A.25.25,0,0,0,8,5.75V4.5a1,1,0,0,1,2,0Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'HealthMedicalHospitalCircle',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
