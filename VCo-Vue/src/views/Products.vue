<script>
export default {
    data() {
        return {
            activeTab: 0,
            products: [
                `
                <div class="col-md-6 col-lg-4 col-xl-3" data-bs-toggle="modal" data-bs-target="#modalProduct">
                        <div id="product-1" class="single-product">
                                <div class="part-1">
                                        <ul>
                                            <li><a href="#"><i class="fas fa-shopping-cart"></i></a></li>
                                            <li><a href="#"><i class="fas fa-heart"></i></a></li>
                                            <li><a href="#"><i class="fas fa-plus"></i></a></li>
                                            <li><a href="#"><i class="fas fa-expand"></i></a></li>
                                        </ul>
                                </div>
                                <div class="part-2">
                                        <h3 class="product-title">Veggetable 1</h3>
                                        <h4 class="product-old-price">Rp. 79.000,99</h4>
                                        <h4 class="product-price">Rp. 49.000,99</h4>
                                </div>
                        </div>
                </div>
                <div class="col-md-6 col-lg-4 col-xl-3" data-bs-toggle="modal" data-bs-target="#modalProduct">
                        <div id="product-2" class="single-product">
                                <div class="part-1">
                                        <span class="discount">15% off</span>
                                        <ul>
                                            <li><a href="#"><i class="fas fa-shopping-cart"></i></a></li>
                                            <li><a href="#"><i class="fas fa-heart"></i></a></li>
                                            <li><a href="#"><i class="fas fa-plus"></i></a></li>
                                            <li><a href="#"><i class="fas fa-expand"></i></a></li>
                                        </ul>
                                </div>
                                <div class="part-2">
                                        <h3 class="product-title">Veggetable 2</h3>
                                        <h4 class="product-price">Rp. 49.000,99</h4>
                                </div>
                        </div>
                </div>
                <div class="col-md-6 col-lg-4 col-xl-3" data-bs-toggle="modal" data-bs-target="#modalProduct">
                        <div id="product-3" class="single-product">
                                <div class="part-1">
                                        <ul>
                                            <li><a href="#"><i class="fas fa-shopping-cart"></i></a></li>
                                            <li><a href="#"><i class="fas fa-heart"></i></a></li>
                                            <li><a href="#"><i class="fas fa-plus"></i></a></li>
                                            <li><a href="#"><i class="fas fa-expand"></i></a></li>
                                        </ul>
                                </div>
                                <div class="part-2">
                                        <h3 class="product-title">Veggetable 3</h3>
                                        <h4 class="product-old-price">Rp. 79.000,99</h4>
                                        <h4 class="product-price">Rp. 49.000,99</h4>
                                </div>
                        </div>
                </div>
                <div class="col-md-6 col-lg-4 col-xl-3" data-bs-toggle="modal" data-bs-target="#modalProduct">
                        <div id="product-4" class="single-product">
                                <div class="part-1">
                                        <span class="new">new</span>
                                        <ul>
                                            <li><a href="#"><i class="fas fa-shopping-cart"></i></a></li>
                                            <li><a href="#"><i class="fas fa-heart"></i></a></li>
                                            <li><a href="#"><i class="fas fa-plus"></i></a></li>
                                            <li><a href="#"><i class="fas fa-expand"></i></a></li>
                                        </ul>
                                </div>
                                <div class="part-2">
                                        <h3 class="product-title">Veggetable 4</h3>
                                        <h4 class="product-price">Rp. 49.000,99</h4>
                                </div>
                        </div>
                </div>`,
                `
                <div class="col-md-6 col-lg-4 col-xl-3" data-bs-toggle="modal" data-bs-target="#modalProduct">
                        <div id="product-1" class="single-product">
                                <div class="part-1">
                                        <ul>
                                                <li><a href="#"><i class="fas fa-shopping-cart"></i></a></li>
                                                <li><a href="#"><i class="fas fa-heart"></i></a></li>
                                                <li><a href="#"><i class="fas fa-plus"></i></a></li>
                                                <li><a href="#"><i class="fas fa-expand"></i></a></li>
                                        </ul>
                                </div>
                                <div class="part-2">
                                        <h3 class="product-title">Snack 1</h3>
                                        <h4 class="product-old-price">Rp. 79.000,99</h4>
                                        <h4 class="product-price">Rp. 49.000,99</h4>
                                </div>
                        </div>
                </div>
                <div class="col-md-6 col-lg-4 col-xl-3" data-bs-toggle="modal" data-bs-target="#modalProduct">
                        <div id="product-2" class="single-product">
                                <div class="part-1">
                                        <span class="discount">15% off</span>
                                        <ul>
                                                <li><a href="#"><i class="fas fa-shopping-cart"></i></a></li>
                                                <li><a href="#"><i class="fas fa-heart"></i></a></li>
                                                <li><a href="#"><i class="fas fa-plus"></i></a></li>
                                                <li><a href="#"><i class="fas fa-expand"></i></a></li>
                                        </ul>
                                </div>
                                <div class="part-2">
                                        <h3 class="product-title">Snack 2</h3>
                                        <h4 class="product-price">Rp. 49.000,99</h4>
                                </div>
                        </div>
                </div>
                <div class="col-md-6 col-lg-4 col-xl-3" data-bs-toggle="modal" data-bs-target="#modalProduct">
                        <div id="product-3" class="single-product">
                                <div class="part-1">
                                        <ul>
                                                <li><a href="#"><i class="fas fa-shopping-cart"></i></a></li>
                                                <li><a href="#"><i class="fas fa-heart"></i></a></li>
                                                <li><a href="#"><i class="fas fa-plus"></i></a></li>
                                                <li><a href="#"><i class="fas fa-expand"></i></a></li>
                                        </ul>
                                </div>
                                <div class="part-2">
                                        <h3 class="product-title">Snack 3</h3>
                                        <h4 class="product-old-price">Rp. 79.000,99</h4>
                                        <h4 class="product-price">Rp. 49.000,99</h4>
                                </div>
                        </div>
                </div>
                <div class="col-md-6 col-lg-4 col-xl-3" data-bs-toggle="modal" data-bs-target="#modalProduct">
                        <div id="product-4" class="single-product">
                                <div class="part-1">
                                        <span class="new">new</span>
                                        <ul>
                                                <li><a href="#"><i class="fas fa-shopping-cart"></i></a></li>
                                                <li><a href="#"><i class="fas fa-heart"></i></a></li>
                                                <li><a href="#"><i class="fas fa-plus"></i></a></li>
                                                <li><a href="#"><i class="fas fa-expand"></i></a></li>
                                        </ul>
                                </div>
                                <div class="part-2">
                                        <h3 class="product-title">Snack 4</h3>
                                        <h4 class="product-price">Rp. 49.000,99</h4>
                                </div>
                        </div>
                </div>`,
                `
                <div class="col-md-6 col-lg-4 col-xl-3" data-bs-toggle="modal" data-bs-target="#modalProduct">
                        <div id="product-1" class="single-product">
                                <div class="part-1">
                                        <ul>
                                                <li><a href="#"><i class="fas fa-shopping-cart"></i></a></li>
                                                <li><a href="#"><i class="fas fa-heart"></i></a></li>
                                                <li><a href="#"><i class="fas fa-plus"></i></a></li>
                                                <li><a href="#"><i class="fas fa-expand"></i></a></li>
                                        </ul>
                                </div>
                                <div class="part-2">
                                        <h3 class="product-title">Dessert 1</h3>
                                        <h4 class="product-old-price">Rp. 79.000,99</h4>
                                        <h4 class="product-price">Rp. 49.000,99</h4>
                                </div>
                        </div>
                </div>
                <div class="col-md-6 col-lg-4 col-xl-3" data-bs-toggle="modal" data-bs-target="#modalProduct">
                        <div id="product-2" class="single-product">
                                <div class="part-1">
                                        <span class="discount">15% off</span>
                                        <ul>
                                                <li><a href="#"><i class="fas fa-shopping-cart"></i></a></li>
                                                <li><a href="#"><i class="fas fa-heart"></i></a></li>
                                                <li><a href="#"><i class="fas fa-plus"></i></a></li>
                                                <li><a href="#"><i class="fas fa-expand"></i></a></li>
                                        </ul>
                                </div>
                                <div class="part-2">
                                        <h3 class="product-title">Dessert 2</h3>
                                        <h4 class="product-price">Rp. 49.000,99</h4>
                                </div>
                        </div>
                </div>
                <div class="col-md-6 col-lg-4 col-xl-3" data-bs-toggle="modal" data-bs-target="#modalProduct">
                        <div id="product-3" class="single-product">
                                <div class="part-1">
                                        <ul>
                                                <li><a href="#"><i class="fas fa-shopping-cart"></i></a></li>
                                                <li><a href="#"><i class="fas fa-heart"></i></a></li>
                                                <li><a href="#"><i class="fas fa-plus"></i></a></li>
                                                <li><a href="#"><i class="fas fa-expand"></i></a></li>
                                        </ul>
                                </div>
                                <div class="part-2">
                                        <h3 class="product-title">Dessert 3</h3>
                                        <h4 class="product-old-price">Rp. 79.000,99</h4>
                                        <h4 class="product-price">Rp. 49.000,99</h4>
                                </div>
                        </div>
                </div>
                <div class="col-md-6 col-lg-4 col-xl-3" data-bs-toggle="modal" data-bs-target="#modalProduct">
                        <div id="product-4" class="single-product">
                                <div class="part-1">
                                        <span class="new">new</span>
                                        <ul>
                                                <li><a href="#"><i class="fas fa-shopping-cart"></i></a></li>
                                                <li><a href="#"><i class="fas fa-heart"></i></a></li>
                                                <li><a href="#"><i class="fas fa-plus"></i></a></li>
                                                <li><a href="#"><i class="fas fa-expand"></i></a></li>
                                        </ul>
                                </div>
                                <div class="part-2">
                                        <h3 class="product-title">Dessert 4</h3>
                                        <h4 class="product-price">Rp. 49.000,99</h4>
                                </div>
                        </div>
                </div>`
            ],
            content: '',
            showList: false
        }
    },
    methods: {
        filter(category) {
            if (category == "Veggetable") {
                this.activeTab = 1;
                this.content = this.products[0];
            } else if (category == "Snack") {
                this.activeTab = 2;
                this.content = this.products[1];
            } else if (category == "Dessert") {
                this.activeTab = 3;
                this.content = this.products[2];
            } else {
                this.activeTab = 0;
                this.content = `${this.products[0]}${this.products[1]}${this.products[2]}`;
            }
            this.showList = false;
        },
        filterButton() {
            this.showList = !this.showList;
        }
    },
    mounted(){
        this.filter("All");
    }
}
</script>
<template>
    <main class="page-content">
        <!-- Product List-->
        <section>
                <div class="context-dark">
                <div class="parallax-container">
                        <div class="parallax-content">
                        <div class="container section-66 section-md-110">
                        <div>
                        <h1 class="font-accent"><span class="big">Our Products</span></h1>
                        </div>
                        <ul class="list-inline list-inline-mg list-inline-squared h3 text-uppercase text-light offset-top-4 d-none d-sm-block">
                        <li class="list-inline-item">A variety of great dishes</li>
                        </ul>
                        </div>
                        </div>
                </div>
                </div>
                <div class="container container-wide section-66">
                        <div class="isotope-wrap">
                        <div class="row">
                                <!-- Isotope Filters-->
                                <div class="col-xl-12">
                                <div class="isotope-filters isotope-filters-horizontal">
                                        <ul class="list-inline list-inline-sm">
                                        <li class="list-inline-item d-lg-none">
                                        <p>Choose your category:</p>
                                        </li>
                                        <li class="list-inline-item section-relative">
                                        <button class="isotope-filters-toggle btn btn-sm btn-default" data-custom-toggle="isotope-1" data-custom-toggle-disable-on-blur="true" @click="filterButton()">Filter<span class="caret"></span></button>
                                        <div class="fd__list" v-show="showList">
                                                <ul>
                                                        <li class="list-inline-item fd__item"><a class="text-sbold"
                                                                :class="{ 'active': activeTab == 0 }" @click="filter('All')">All</a></li>
                                                        <li class="list-inline-item fd__item"><a class="text-sbold"
                                                                :class="{ 'active': activeTab == 1 }" @click="filter('Veggetable')">Veggetable</a></li>
                                                        <li class="list-inline-item fd__item"><a class="text-sbold"
                                                                :class="{ active: activeTab == 2 }" @click="filter('Snack')">Snack</a></li>
                                                        <li class="list-inline-item fd__item"><a class="text-sbold"
                                                                :class="{ active: activeTab == 3 }" @click="filter('Dessert')">Dessert</a></li>
                                                </ul>
                                        </div>
                                        <ul class="list-sm-inline isotope-filters-list" id="isotope-1">
                                                <!-- .teamSelector { cursor: pointer; } -->
                                                <!-- span:hover { cursor:pointer; } -->
                                                <li class="list-inline-item"><a class="text-sbold"
                                                :class="{ 'active': activeTab == 0 }" @click="filter('All')">All</a></li>
                                                <li class="list-inline-item"><a class="text-sbold"
                                                :class="{ 'active': activeTab == 1 }" @click="filter('Veggetable')">Veggetable</a></li>
                                                <li class="list-inline-item"><a class="text-sbold"
                                                :class="{ active: activeTab == 2 }" @click="filter('Snack')">Snack</a></li>
                                                <li class="list-inline-item"><a class="text-sbold"
                                                :class="{ active: activeTab == 3 }" @click="filter('Dessert')">Dessert</a></li>
                                        </ul>
                                        </li>
                                        </ul>
                                </div>
                                </div>
                                <div class="col-xl-12 offset-top-34">
                                <section class="section-products">
                                        <div class="container">
                                        <div class="row" v-html="content"></div>
                                        </div>
                                </section>
                                </div>
                        </div>
                        </div>
                </div>

                <!-- Modal -->
                <div class="modal fade" id="modalProduct" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
                        <div class="modal-dialog">
                                <div class="modal-content">
                                        <div class="modal-header">
                                                <h1 class="modal-title fs-5" id="exampleModalLabel">Modal title</h1>
                                                <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                                        </div>
                                        <div class="modal-body">
                                                ...
                                        </div>
                                        <div class="modal-footer">
                                                <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                                                <button type="button" class="btn btn-primary">Save changes</button>
                                        </div>
                                </div>
                        </div>
                </div>
        </section>
    </main>
</template>

<style scoped>
.fd__list {
    position: absolute;
    z-index: 1;
    top: 100%;
    left: 0;
    padding: 4px;
    border: solid 1px rgb(192, 192, 192);
    background: white;
    box-shadow: 1px 1px 1px 1px rgba(0, 0, 0, 0.2);
    margin-top: -1px;
}
.fd__list ul {
        margin: 4px 0 0 0;
        padding: 4px;
        overflow-x: auto;
        overflow-y: scroll;
        max-height: 40vh;
}

.fd__list ul li {
        padding: 4px 1px;
        cursor: pointer;
        list-style: none;
        line-height: 1;
}

.fd__list ul li:hover {
        background: aliceblue;
}        
</style>