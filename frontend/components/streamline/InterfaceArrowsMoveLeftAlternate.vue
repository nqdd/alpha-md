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
                d="M7,7a.76.76,0,0,0-.75-.75H3.16a.25.25,0,0,1-.23-.15A.26.26,0,0,1,3,5.82L4.28,4.53A.75.75,0,0,0,3.22,3.47l-3,3a.75.75,0,0,0,0,1.06l3,3a.75.75,0,0,0,1.06,0,.75.75,0,0,0,0-1.06L3,8.18a.26.26,0,0,1-.06-.28.25.25,0,0,1,.23-.15H6.25A.76.76,0,0,0,7,7Z"
            />
            <path
                d="M14,1.75A1.76,1.76,0,0,0,12.25,0h-2A1.76,1.76,0,0,0,8.5,1.75v10.5A1.76,1.76,0,0,0,10.25,14h2A1.76,1.76,0,0,0,14,12.25Zm-1.5,10.5a.25.25,0,0,1-.25.25h-2a.25.25,0,0,1-.25-.25V1.75a.25.25,0,0,1,.25-.25h2a.25.25,0,0,1,.25.25Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceArrowsMoveLeftAlternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
