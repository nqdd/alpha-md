<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M5.28,10.47,3,8.18a.26.26,0,0,1-.06-.28.25.25,0,0,1,.23-.15h7.68a.25.25,0,0,1,.23.15.26.26,0,0,1-.06.28L8.72,10.47a.75.75,0,0,0,1.06,1.06l4-4a.75.75,0,0,0,0-1.06l-4-4A.75.75,0,1,0,8.72,3.53L11,5.82a.26.26,0,0,1,.06.28.25.25,0,0,1-.23.15H3.16a.25.25,0,0,1-.23-.15A.26.26,0,0,1,3,5.82L5.28,3.53A.75.75,0,0,0,4.22,2.47l-4,4a.75.75,0,0,0,0,1.06l4,4a.75.75,0,0,0,1.06-1.06Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceArrowsHorizontal',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
