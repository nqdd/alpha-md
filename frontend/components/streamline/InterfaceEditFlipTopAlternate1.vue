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
                d="M2.45,12a.73.73,0,0,1-.54-.24,6.88,6.88,0,0,1-1-1.3,7.26,7.26,0,0,1-.47-1A.75.75,0,0,1,1.87,9a5.33,5.33,0,0,0,.37.76,5.48,5.48,0,0,0,.76,1,.75.75,0,0,1,0,1.06A.79.79,0,0,1,2.45,12Z"
            />
            <path
                d="M11.55,12a.79.79,0,0,1-.52-.2.75.75,0,0,1,0-1.06,5.48,5.48,0,0,0,.76-1A4.84,4.84,0,0,0,12.13,9a.75.75,0,0,1,1.4.54,7.22,7.22,0,0,1-.47,1,6.88,6.88,0,0,1-1,1.3A.73.73,0,0,1,11.55,12Z"
            />
            <path
                d="M7,14a6.83,6.83,0,0,1-1.62-.19.74.74,0,0,1-.55-.9.75.75,0,0,1,.9-.56,5.45,5.45,0,0,0,2.54,0,.75.75,0,0,1,.9.56.74.74,0,0,1-.55.9A6.83,6.83,0,0,1,7,14Z"
            />
            <path
                d="M13.23,7.25a.75.75,0,0,1-.75-.69,5.5,5.5,0,0,0-11,0,.77.77,0,0,1-.81.69A.76.76,0,0,1,0,6.44a7,7,0,0,1,14,0,.76.76,0,0,1-.69.81Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'InterfaceEditFlipTopAlternate1',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
