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
                d="M9.79,13.91,5.47,12.46A.75.75,0,0,1,6,11l4.31,1.45a.26.26,0,0,0,.32-.16l1.91-5.69a.26.26,0,0,0-.11-.3.77.77,0,0,1-.5-1,.73.73,0,0,1,.93-.48l.31.14a1.75,1.75,0,0,1,.79,2.08L12,12.81A1.75,1.75,0,0,1,9.79,13.91Z"
            />
            <path
                d="M10.5,1.75A1.76,1.76,0,0,0,8.75,0h-7A1.75,1.75,0,0,0,0,1.75v6A1.75,1.75,0,0,0,1.75,9.5h7A1.76,1.76,0,0,0,10.5,7.75Zm-9,0a.25.25,0,0,1,.25-.25h7A.25.25,0,0,1,9,1.75v4.5a.25.25,0,0,1-.25.25h-7a.25.25,0,0,1-.25-.25Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'ImagePhotoPolaroid',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
