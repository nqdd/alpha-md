<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <g>
            <rect y="5" width="6.25" height="3.5" rx="1" />
            <path
                d="M7.5,13.5A.5.5,0,0,0,8,14h5.5a.5.5,0,0,0,.5-.5V13a2,2,0,0,0-2-2H10.25a.25.25,0,0,1-.25-.25v-2a1.25,1.25,0,0,0-2.5,0Z"
            />
            <rect width="6.25" height="3.5" rx="1" />
            <rect x="7.75" width="6.25" height="3.5" rx="1" />
            <path
                d="M13,5H8.75a1,1,0,0,0-1,1v.2a2.59,2.59,0,0,1,1-.2,2.75,2.75,0,0,1,2.71,2.29.26.26,0,0,0,.25.21H13a1,1,0,0,0,1-1V6A1,1,0,0,0,13,5Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceLoginFingerPassword',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
