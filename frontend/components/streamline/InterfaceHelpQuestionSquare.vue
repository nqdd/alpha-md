<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M14,1.5A1.5,1.5,0,0,0,12.5,0H1.5A1.5,1.5,0,0,0,0,1.5v11A1.5,1.5,0,0,0,1.5,14h11A1.5,1.5,0,0,0,14,12.5ZM7,11.75a1,1,0,1,1,1-1A1,1,0,0,1,7,11.75Zm.92-3.91a.26.26,0,0,0-.17.24v.17a.75.75,0,0,1-1.5,0v-1A.76.76,0,0,1,7,6.5,1.25,1.25,0,1,0,5.75,5.25a.75.75,0,0,1-1.5,0A2.75,2.75,0,1,1,7.92,7.84Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceHelpQuestionSquare',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
