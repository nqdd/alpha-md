<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M12.5,13.25a.76.76,0,0,0-.75-.75H11.5a.25.25,0,0,1-.25-.25v-1.5a4.25,4.25,0,0,0-1.9-3.54.24.24,0,0,1,0-.42,4.25,4.25,0,0,0,1.9-3.54V1.75a.25.25,0,0,1,.25-.25h.25A.76.76,0,0,0,12.5.75.76.76,0,0,0,11.75,0H2.25A.76.76,0,0,0,1.5.75a.76.76,0,0,0,.75.75H2.5a.25.25,0,0,1,.25.25v1.5a4.25,4.25,0,0,0,1.9,3.54.24.24,0,0,1,0,.42,4.25,4.25,0,0,0-1.9,3.54v1.5a.25.25,0,0,1-.25.25H2.25a.75.75,0,0,0,0,1.5h9.5A.76.76,0,0,0,12.5,13.25ZM4.25,1.75A.25.25,0,0,1,4.5,1.5h5a.25.25,0,0,1,.25.25v1.5a2.75,2.75,0,0,1-5.5,0Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceTimeHourGlass',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
