<script>

export default {
    name: 'Banner.vue',

    data() {
        return {
            bannerItems: [
                {
                    src: '/buy-comics-digital-comics.png',
                    content: 'digital comics'
                },
                {
                    src: '/buy-comics-merchandise.png',
                    content: 'dc merchandise'
                },
                {
                    src: '/buy-comics-subscriptions.png',
                    content: 'subscription'
                },
                {
                    src: '/buy-comics-shop-locator.png',
                    content: 'comic shop locator'
                },
                {
                    src: '/buy-dc-power-visa.svg',
                    content: 'dc power visa'
                }
            ]
        }
    }
}

</script>

<template>
    <div class="container-fluid bg-blue">
        <div class="container py-5">
            <div class="row justify-content-center">
                <div v-for="elem in bannerItems" class="col-lg">
                    <div class="img-wrapper me-2 ">
                        <img :src="elem.src" alt="" class="img-small">
                    </div>
                    <span class="text-uppercase small text-white">{{ elem.content }}</span>
                </div>
            </div>
        </div>
    </div>
</template>