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
                d="M13.3,6A1.5,1.5,0,0,0,14,4.89a1.52,1.52,0,0,0-.43-1.23L10.36.46A1.5,1.5,0,0,0,8.05.7L6,3.81l-4.3,1a1.11,1.11,0,0,0-.54,1.86l6.16,6.15a1.11,1.11,0,0,0,.78.33,1,1,0,0,0,.3-.05,1.12,1.12,0,0,0,.78-.81l1-4.3Z"
            />
            <path
                d="M2.72,10.2a.24.24,0,0,0-.35,0L.29,12.27a1,1,0,0,0,0,1.41,1,1,0,0,0,1.42,0l2.07-2.07a.24.24,0,0,0,0-.35Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceEditPin2',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
