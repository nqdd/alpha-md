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
                d="M12.25,12.5H1.75A1.76,1.76,0,0,1,0,10.75V3.25A1.76,1.76,0,0,1,1.75,1.5h10.5A1.76,1.76,0,0,1,14,3.25v7.5A1.76,1.76,0,0,1,12.25,12.5ZM1.75,3a.25.25,0,0,0-.25.25v7.5a.25.25,0,0,0,.25.25h10.5a.25.25,0,0,0,.25-.25V3.25A.25.25,0,0,0,12.25,3Z"
            />
            <path
                d="M10.25,6H3.75a.75.75,0,0,1,0-1.5h6.5a.75.75,0,0,1,0,1.5Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceEditAlignTopHorizontalAlternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
