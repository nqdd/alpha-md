<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M13.25,1a1,1,0,0,1-1,1H7.5a.25.25,0,0,0-.25.25V10a.25.25,0,0,0,.15.23.26.26,0,0,0,.28-.05L10,7.79a1,1,0,0,1,1.42,0,1,1,0,0,1,0,1.42L7,13.71a1,1,0,0,1-1.42,0L1,9.21A1,1,0,1,1,2.46,7.79l2.36,2.37a.26.26,0,0,0,.28.05A.25.25,0,0,0,5.25,10V2a2,2,0,0,1,2-2h5A1,1,0,0,1,13.25,1Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceArrowsBendDownLeft1',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
