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
                d="M10.23,9a.25.25,0,0,0-.23.25v2A1.25,1.25,0,0,1,8.75,12.5h-6A1.25,1.25,0,0,1,1.5,11.25v-6A1.25,1.25,0,0,1,2.75,4H7.26a.27.27,0,0,0,.19-.08.25.25,0,0,0,.06-.2,1.55,1.55,0,0,1,0-.22V2.75a.25.25,0,0,0-.25-.25H2.75A2.75,2.75,0,0,0,0,5.25v6A2.75,2.75,0,0,0,2.75,14h6a2.75,2.75,0,0,0,2.75-2.75V8.94a.24.24,0,0,0-.12-.21.25.25,0,0,0-.25,0A2.48,2.48,0,0,1,10.23,9Z"
            />
            <g>
                <path d="M10,5.5a1,1,0,1,0,1,1A1,1,0,0,0,10,5.5Z" />
                <path
                    d="M10,0A1,1,0,0,0,9,1V3.5a1,1,0,0,0,2,0V1A1,1,0,0,0,10,0Z"
                />
            </g>
        </g>
    </svg>
</template>
<script>
export default {
    name: 'PhoneNotificationApplication2Alternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
