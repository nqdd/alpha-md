<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <g>
            <path
                d="M4.25,13.75A.25.25,0,0,0,4.5,14h5a.25.25,0,0,0,.25-.25V3a2.75,2.75,0,0,0-5.5,0ZM5.75,3a1.25,1.25,0,0,1,2.5,0v.75A.25.25,0,0,1,8,4H6a.25.25,0,0,1-.25-.25Z"
            />
            <path
                d="M14,6.75A2.75,2.75,0,0,0,11.25,4H11a.25.25,0,0,0-.25.25v9.5A.25.25,0,0,0,11,14h.25A2.75,2.75,0,0,0,14,11.25Z"
            />
            <path
                d="M3.25,4.25A.25.25,0,0,0,3,4H2.75A2.75,2.75,0,0,0,0,6.75v4.5A2.75,2.75,0,0,0,2.75,14H3a.25.25,0,0,0,.25-.25Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'TravelAirportBaggage',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
