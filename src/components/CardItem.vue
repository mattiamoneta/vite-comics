<script>
export default {
    name: 'CardItem',
    props: {
        cardname: String,
        link: String
    }
}
</script>

<template>
    <div class="card m-3">
        <div class="card-img-wrapper">
            <img :src="link" :alt="cardname">
        </div>
        <div class="card-body p-0 my-3">
            <span class="card-title small">{{ cardname }}</span>
        </div>
    </div>
</template>