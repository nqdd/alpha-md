<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <g>
            <circle cx="4.5" cy="8" r="1.5" />
            <path
                d="M12.75,3.5H10a.25.25,0,0,1-.25-.25v-.5a2.75,2.75,0,0,0-5.5,0v.5A.25.25,0,0,1,4,3.5H1.25A1.25,1.25,0,0,0,0,4.75v8A1.25,1.25,0,0,0,1.25,14h11.5A1.25,1.25,0,0,0,14,12.75v-8A1.25,1.25,0,0,0,12.75,3.5Zm-7-.75a1.25,1.25,0,0,1,2.5,0v.5A.25.25,0,0,1,8,3.5H6a.25.25,0,0,1-.25-.25Zm6.75,7.54a.25.25,0,0,1-.15.23.25.25,0,0,1-.27,0L10.26,8.79a1.13,1.13,0,0,0-1.55.06L5.36,12.42a.27.27,0,0,1-.19.08H1.75a.25.25,0,0,1-.25-.25v-7A.25.25,0,0,1,1.75,5h10.5a.25.25,0,0,1,.25.25Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'TravelPlacesPaintingAlternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
