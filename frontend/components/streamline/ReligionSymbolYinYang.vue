<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <g>
            <circle cx="5" cy="9.5" r="1.25" />
            <path
                d="M7,0a7,7,0,1,0,7,7A7,7,0,0,0,7,0Zm.84,12A1,1,0,0,1,7,12.5,5.5,5.5,0,0,1,5.67,1.66a.27.27,0,0,1,.26.1.26.26,0,0,1,0,.28C5.15,3.3,4.59,5.28,7,7,9.15,8.54,8.55,10.66,7.84,12ZM9,5.75A1.25,1.25,0,1,1,10.25,4.5,1.25,1.25,0,0,1,9,5.75Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'ReligionSymbolYinYang',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
