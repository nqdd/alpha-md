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
                d="M12.14,13A1.87,1.87,0,0,1,11,12.58L6.15,8.63a2.11,2.11,0,0,1,0-3.26L11,1.42A1.82,1.82,0,0,1,12.14,1,1.87,1.87,0,0,1,14,2.85v8.3A1.87,1.87,0,0,1,12.14,13Zm0-10.5a.35.35,0,0,0-.22.08l-4.81,4a.6.6,0,0,0,0,.94l4.81,4a.37.37,0,0,0,.58-.27V2.85A.36.36,0,0,0,12.14,2.5Z"
            />
            <path
                d="M2.5,13.5H2a2,2,0,0,1-2-2v-9a2,2,0,0,1,2-2h.5a2,2,0,0,1,2,2v9A2,2,0,0,1,2.5,13.5ZM2,2a.5.5,0,0,0-.5.5v9A.5.5,0,0,0,2,12h.5a.5.5,0,0,0,.5-.5v-9A.5.5,0,0,0,2.5,2Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'EntertainmentControlButtonPreviousAlternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
