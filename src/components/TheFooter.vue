<style></style>

<template>
    <footer>
        <div class="container-fluid" id="footer">
            <div class="container">
                <div class="row">
                    <div class="col-6 py-5">
                        <div class="row">
                            <div class="col-lg-4">
                                <h5 class="text-uppercase text-white">dc comics</h5>
                                <ul class="list-unstyled" v-for="(item) in sectDcComics">
                                    <li class="footer-link"><a :href="item.href"
                                            class="text-decoration-none text-muted small">{{ item.content
                                            }}</a>
                                    </li>
                                </ul>
                                <h5 class="text-uppercase text-white">shop</h5>
                                <ul class="list-unstyled" v-for="(item) in sectShop">
                                    <li class="footer-link"><a :href="item.href"
                                            class="text-decoration-none text-muted small">{{ item.content
                                            }}</a>
                                    </li>
                                </ul>
                            </div>
                            <div class="col-lg-4">
                                <h5 class="text-uppercase text-white">dc</h5>
                                <ul class="list-unstyled" v-for="(item) in sectDc">
                                    <li class="footer-link"><a :href="item.href"
                                            class="text-decoration-none text-muted small">{{ item.content
                                            }}</a>
                                    </li>
                                </ul>
                            </div>
                            <div class="col-lg-4">
                                <h5 class="text-uppercase text-white">sites</h5>
                                <ul class="list-unstyled" v-for="(item) in sectSites">
                                    <li class="footer-link"><a :href="item.href"
                                            class="text-decoration-none text-muted small">{{ item.content
                                            }}</a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>

                    <div class="col-6 bg-logo"></div>
                </div>
            </div>
        </div>
        <div class="container py-4">
            <div class="row">
                <div class="col-lg-2">
                    <a href="#"
                        class="btn btn-outline-primary outline-squared rounded-0 text-white border-3 border border-primary">SIGN-UP
                        NOW!</a>
                </div>
                <div class="col-lg-10 text-end">
                    <span class="text-uppercase text-primary fw-bold me-3">follow us</span>
                    <ul class="list-inline d-inline">
                        <a href="#" class="btn rounded-circle text-tertiary bg-light mx-1"><i
                                class="fa-brands fa-facebook-f"></i></a>
                        <a href="#" class="btn rounded-circle text-tertiary bg-light mx-1"><i
                                class="fa-brands fa-facebook-f"></i></a>
                        <a href="#" class="btn rounded-circle text-tertiary bg-light mx-1"><i
                                class="fa-brands fa-facebook-f"></i></a>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'TheFooter.vue',
    data() {
        return {
            sectDcComics: [
                {
                    content: 'Item1',
                    href: '#'
                },
                {
                    content: 'Item1',
                    href: '#'
                },
                {
                    content: 'Item1',
                    href: '#'
                },
                {
                    content: 'Item1',
                    href: '#'
                },
                {
                    content: 'Item1',
                    href: '#'
                }
            ],
            sectShop: [
                {
                    content: 'Item1',
                    href: '#'
                },
                {
                    content: 'Item1',
                    href: '#'
                },
                {
                    content: 'Item1',
                    href: '#'
                },
                {
                    content: 'Item1',
                    href: '#'
                },
                {
                    content: 'Item1',
                    href: '#'
                }
            ],
            sectDc: [
                {
                    content: 'Item1',
                    href: '#'
                },
                {
                    content: 'Item1',
                    href: '#'
                },
                {
                    content: 'Item1',
                    href: '#'
                },
                {
                    content: 'Item1',
                    href: '#'
                },
                {
                    content: 'Item1',
                    href: '#'
                }
            ],
            sectSites: [
                {
                    content: 'Item1',
                    href: '#'
                },
                {
                    content: 'Item1',
                    href: '#'
                },
                {
                    content: 'Item1',
                    href: '#'
                },
                {
                    content: 'Item1',
                    href: '#'
                },
                {
                    content: 'Item1',
                    href: '#'
                }
            ],

        }
    }
}
</script>