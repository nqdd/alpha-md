<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <g>
            <circle cx="10.04" cy="2" r="2" />
            <path
                d="M10.5,9H.25A.25.25,0,0,0,0,9.25v4.5A.25.25,0,0,0,.25,14H10.5a2.5,2.5,0,0,0,0-5ZM2,12.5a1,1,0,1,1,1-1A1,1,0,0,1,2,12.5Zm3.75,0a1,1,0,1,1,1-1A1,1,0,0,1,5.75,12.5Zm3.75,0a1,1,0,1,1,1-1A1,1,0,0,1,9.5,12.5Z"
            />
            <g>
                <rect y="2.5" width="5" height="5" rx="0.5" />
                <path
                    d="M10.5,7.5A4,4,0,0,1,13.58,9a.54.54,0,0,0,.3-.15.49.49,0,0,0,.11-.4A4,4,0,0,0,10,5c-.59,0-2.83.35-3.52,2.16a.24.24,0,0,0,0,.23.23.23,0,0,0,.2.11Z"
                />
            </g>
        </g>
    </svg>
</template>
<script>
export default {
    name: 'ShoppingBusinessProductionBeltUser',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
