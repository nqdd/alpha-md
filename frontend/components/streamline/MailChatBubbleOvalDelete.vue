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
                d="M12.24,3.18a.25.25,0,0,1,0-.36l1.54-1.54A.75.75,0,0,0,12.72.22L11.18,1.76a.25.25,0,0,1-.36,0L9.28.22A.75.75,0,0,0,8.22,1.28L9.76,2.82a.25.25,0,0,1,0,.36L8.22,4.72a.75.75,0,0,0,0,1.06.75.75,0,0,0,1.06,0l1.54-1.54a.25.25,0,0,1,.36,0l1.54,1.54a.75.75,0,0,0,1.06,0,.75.75,0,0,0,0-1.06Z"
            />
            <path
                d="M11.18,6.35a.25.25,0,0,0-.35,0l-.49.48A2.25,2.25,0,0,1,6.5,5.25a2.21,2.21,0,0,1,.66-1.59l.48-.49a.25.25,0,0,0,0-.35L7,2.15a.22.22,0,0,0-.15-.08A6,6,0,0,0,6,2,6,6,0,0,0,.82,11a.25.25,0,0,1,0,.22L0,13.42A.43.43,0,0,0,.51,14l2.91-.53a.26.26,0,0,1,.15,0A5.83,5.83,0,0,0,6,14a6,6,0,0,0,6-6,5.85,5.85,0,0,0-.07-.85A.22.22,0,0,0,11.85,7Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'MailChatBubbleOvalDelete',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
