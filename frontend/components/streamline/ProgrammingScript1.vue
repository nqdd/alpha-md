<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M14,2.5A2.5,2.5,0,0,0,11.5,0H4.75A2.75,2.75,0,0,0,2,2.75v6.5a.25.25,0,0,1-.25.25h-.5A1.25,1.25,0,0,0,0,10.75v.5A2.75,2.75,0,0,0,2.75,14h4.5A2.75,2.75,0,0,0,10,11.25V2.75A1.27,1.27,0,0,1,11.25,1.5a1.37,1.37,0,0,1,1.05.4.37.37,0,0,1-.3.6h-.25a.29.29,0,0,0-.18.07.24.24,0,0,0-.07.18v2a.25.25,0,0,0,.25.25h1A1.25,1.25,0,0,0,14,3.75ZM2.75,12.5A1.25,1.25,0,0,1,1.5,11.25.25.25,0,0,1,1.75,11H6a.25.25,0,0,1,.25.25A1.25,1.25,0,0,0,7.5,12.5Zm5-4.62H4.25a.63.63,0,0,1,0-1.26h3.5a.63.63,0,0,1,0,1.26Zm0-3.5H5.5a.63.63,0,0,1,0-1.26H7.75a.63.63,0,0,1,0,1.26Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'ProgrammingScript1',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
