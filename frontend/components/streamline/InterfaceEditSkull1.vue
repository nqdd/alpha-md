<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M7,0A6,6,0,0,0,3.36,10.76a1,1,0,0,1,.39.8v.94A1.5,1.5,0,0,0,5.25,14a1,1,0,0,0,1-1v-.75a.75.75,0,0,1,1.5,0V13a1,1,0,0,0,1,1,1.5,1.5,0,0,0,1.5-1.5v-.94a1,1,0,0,1,.39-.8A6,6,0,0,0,7,0ZM4.5,7.25A1.25,1.25,0,1,1,5.75,6,1.25,1.25,0,0,1,4.5,7.25Zm5,0A1.25,1.25,0,1,1,10.75,6,1.25,1.25,0,0,1,9.5,7.25Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceEditSkull1',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
