<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M14,7.4a7.08,7.08,0,0,0-14,0A1.65,1.65,0,0,0,1.65,9.32H6a.25.25,0,0,1,.25.25v2.75a.25.25,0,0,1-.25.25H4.25a.75.75,0,0,0,0,1.5h5.5a.75.75,0,0,0,0-1.5H8a.25.25,0,0,1-.25-.25V9.57A.25.25,0,0,1,8,9.32h4.35A1.65,1.65,0,0,0,14,7.4Zm-1.52.37a.16.16,0,0,1-.11.05H1.65a.16.16,0,0,1-.11-.05.17.17,0,0,1,0-.12,5.58,5.58,0,0,1,11,0A.17.17,0,0,1,12.46,7.77Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceLightingLightBulbTableRoundAlternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
