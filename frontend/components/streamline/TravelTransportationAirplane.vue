<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M14,3.25a1,1,0,0,0-1-1H11.55a1,1,0,0,0-1,.76l-.34,1.31a.27.27,0,0,1-.3.19L5.2,3.64a4.49,4.49,0,0,0-3.6.86A4.13,4.13,0,0,0,0,7.71a1.51,1.51,0,0,0,.46,1.1,1.58,1.58,0,0,0,1.1.44H5.17a.25.25,0,0,1,.22.12l.82,1.23a2.61,2.61,0,0,0,2.18,1.15h.88a1,1,0,0,0,.88-.48.94.94,0,0,0,0-1l-.35-.69a.21.21,0,0,1,0-.24.26.26,0,0,1,.22-.12h2.37A1.53,1.53,0,0,0,14,7.75Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'TravelTransportationAirplane',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
