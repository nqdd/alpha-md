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
                d="M7,10a.51.51,0,0,0,.48.28.5.5,0,0,0,.44-.33L9.66,5A.5.5,0,0,0,9,4.36L4.12,6.11a.48.48,0,0,0-.33.44A.47.47,0,0,0,4.06,7L5.94,8a.29.29,0,0,1,.11.11Z"
            />
            <path
                d="M7,14a7,7,0,1,1,7-7A7,7,0,0,1,7,14ZM7,1.5A5.5,5.5,0,1,0,12.5,7,5.51,5.51,0,0,0,7,1.5Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'TravelMapLocationCompass1Alternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
