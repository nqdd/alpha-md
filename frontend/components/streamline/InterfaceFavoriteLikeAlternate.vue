<template>
    <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 14 14"
        fill="currentColor"
        :width="size"
        :height="size"
    >
        <path
            d="M14,6.91A1.66,1.66,0,0,0,12.35,5H8.71a.25.25,0,0,1-.25-.25V2.61A1.62,1.62,0,0,0,6.85,1a1.59,1.59,0,0,0-1.36.75L3.17,5.38A.25.25,0,0,1,3,5.5H.5A.5.5,0,0,0,0,6v6.5a.5.5,0,0,0,.5.5H11.56a1.65,1.65,0,0,0,1.63-1.39Z"
        />
    </svg>
</template>
<script>
export default {
    name: 'InterfaceFavoriteLikeAlternate',
    props: {
        size: {
            type: String,
            required: false,
            default: '14',
        },
    },
};
</script>
