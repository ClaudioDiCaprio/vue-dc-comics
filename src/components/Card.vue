<template>
    <div class="comic-sachet">
        <a href="">
            <img class="comic-cover" :src="stats.thumb" :alt="stats.series">
            <span class="comic-title">{{stats.series}}</span>
        </a>
    </div>
</template>

<script>
export default {
    name: 'Card',
    props: {
        stats: Object,
    }
}
</script>

<style scoped lang="scss">
    .comic-sachet {
        a {
            text-decoration: none;
        }
        width: calc(100% / 6);
        padding: 5px;
        margin-bottom: 50px;
        color: white;
        &:hover {
            transform: scale(1.02);
        }
        .comic-cover {
            width: 100%;
            display: block;
            aspect-ratio: 1;
            object-fit: cover;
            object-position: top;
            margin-bottom: 20px;
        }
        .comic-title {
            color: white;
        }
    }
</style>