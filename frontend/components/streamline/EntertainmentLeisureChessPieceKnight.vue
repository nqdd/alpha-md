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
                d="M4,6.2l.36-.06a.3.3,0,0,1,.21.05.29.29,0,0,1,.09.2V9a.5.5,0,0,0,.5.5h4.5a.5.5,0,0,0,.5-.5V2.5A2.51,2.51,0,0,0,7.67,0H6.55a2.48,2.48,0,0,0-.93.18l-3,1.19A2.52,2.52,0,0,0,4,6.2Z"
            />
            <path
                d="M12.42,2a.75.75,0,0,0-.75.75v4.5a.75.75,0,1,0,1.5,0V2.75A.76.76,0,0,0,12.42,2Z"
            />
            <path
                d="M9.47,11H4.86a2,2,0,0,0-2,1.67l-.12.75a.46.46,0,0,0,.11.4.46.46,0,0,0,.38.18h7.82a.46.46,0,0,0,.38-.18.46.46,0,0,0,.11-.4l-.12-.75A2,2,0,0,0,9.47,11Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'EntertainmentLeisureChessPieceKnight',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
