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
                d="M11.37,6.17A.48.48,0,0,0,11,6H3a.51.51,0,0,0-.5.55l.75,7a.5.5,0,0,0,.5.45h6.5a.5.5,0,0,0,.5-.45l.75-7A.48.48,0,0,0,11.37,6.17Z"
            />
            <path
                d="M12.5,2.79H10a.25.25,0,0,1-.25-.25V1.75A1.76,1.76,0,0,0,8,0H6A1.75,1.75,0,0,0,4.25,1.72v.83A.25.25,0,0,1,4,2.79H1.5a1,1,0,0,0,0,2h11a1,1,0,0,0,0-2Zm-6.75-1A.25.25,0,0,1,6,1.5H8a.25.25,0,0,1,.25.25v.79A.25.25,0,0,1,8,2.79H6a.29.29,0,0,1-.18-.07.26.26,0,0,1-.07-.18Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceDeleteBin1',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
