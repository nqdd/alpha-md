<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M12.29,7.79,10.93,9.16a.25.25,0,0,1-.36,0L4.84,3.43a.25.25,0,0,1,0-.36L6.21,1.71A1,1,0,0,0,5.5,0H1A1,1,0,0,0,0,1V5.5a1,1,0,0,0,1.71.71L3.07,4.84a.25.25,0,0,1,.36,0l5.73,5.73a.25.25,0,0,1,0,.36L7.79,12.29A1,1,0,0,0,8.5,14H13a1,1,0,0,0,1-1V8.5a1,1,0,0,0-1.71-.71Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceArrowsDiagonal2Alternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
