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
                d="M11.25,14H2.75A2.75,2.75,0,0,1,0,11.25V2.75A2.75,2.75,0,0,1,2.75,0h8.5A2.75,2.75,0,0,1,14,2.75v8.5A2.75,2.75,0,0,1,11.25,14ZM2.75,1.5A1.25,1.25,0,0,0,1.5,2.75v8.5A1.25,1.25,0,0,0,2.75,12.5h8.5a1.25,1.25,0,0,0,1.25-1.25V2.75A1.25,1.25,0,0,0,11.25,1.5Z"
            />
            <rect x="3.5" y="9" width="7" height="2" rx="0.75" />
            <path
                d="M10.45,7.2a.52.52,0,0,1-.48.3H4a.52.52,0,0,1-.48-.3.5.5,0,0,1,.08-.56l3-3.47a.55.55,0,0,1,.8,0l3,3.47A.5.5,0,0,1,10.45,7.2Z"
            />
        </g>
    </svg>
</template>
<script>
export default {
    name: 'ComputerKeyboardEjectAlternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
