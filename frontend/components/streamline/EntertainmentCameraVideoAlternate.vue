<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M13.5,8.75a1.23,1.23,0,0,0-.59-1.06,1.26,1.26,0,0,0-1.22-.06l-.17.09a.25.25,0,0,1-.33-.09,3,3,0,0,0-.2-.29.21.21,0,0,1-.06-.21A.26.26,0,0,1,11.07,7,3.24,3.24,0,1,0,7.4,1.77a.24.24,0,0,1-.21.08A.28.28,0,0,1,7,1.73,3.49,3.49,0,1,0,3,6.84.23.23,0,0,1,3.14,7a.22.22,0,0,1-.05.23A2.21,2.21,0,0,0,2.5,8.75v3A2.25,2.25,0,0,0,4.75,14h4.5a2.24,2.24,0,0,0,1.94-1.12.26.26,0,0,1,.33-.1l.17.09a1.26,1.26,0,0,0,1.22-.06,1.23,1.23,0,0,0,.59-1.06ZM9.75,2.25A1.75,1.75,0,1,1,8,4,1.76,1.76,0,0,1,9.75,2.25ZM6.66,5.77a.24.24,0,0,1,.2-.09.27.27,0,0,1,.2.11l.22.3a.25.25,0,0,1-.19.41H6.53a.25.25,0,0,1-.16-.44A4,4,0,0,0,6.66,5.77ZM2,3.5a2,2,0,1,1,2,2A2,2,0,0,1,2,3.5Zm10,7.44a.22.22,0,0,1-.12.21.23.23,0,0,1-.24,0l-.56-.27a.71.71,0,0,0-.72,0,.74.74,0,0,0-.36.64v.19a.76.76,0,0,1-.75.75H4.75A.76.76,0,0,1,4,11.75v-3A.76.76,0,0,1,4.75,8h4.5a.76.76,0,0,1,.75.75v.19a.75.75,0,0,0,1.08.67l.56-.27a.23.23,0,0,1,.24,0,.22.22,0,0,1,.12.21Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'EntertainmentCameraVideoAlternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
