<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M8.34,14a1.21,1.21,0,0,1-1.14-.82L5.65,8.51a.31.31,0,0,0-.16-.16L.82,6.8a1.2,1.2,0,0,1,0-2.26L12.37.08a1.21,1.21,0,0,1,1.28.27h0a1.19,1.19,0,0,1,.27,1.27L9.46,13.23A1.21,1.21,0,0,1,8.34,14ZM2.75,5.39a.24.24,0,0,0-.16.24.25.25,0,0,0,.17.23L6.67,7.17a.22.22,0,0,1,.16.16l1.31,3.91a.25.25,0,0,0,.23.17.24.24,0,0,0,.24-.16l3.46-9a.24.24,0,0,0-.32-.32Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'TravelMapNavigationArrowAlternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
