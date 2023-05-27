<script>

export default {
    data() {
        return {
            content: `<div class="col-12 col-lg-4 isotope-item">
                    <div class="inset-lg-right-20">
                        <!-- Pricing Box type 1-->
                        <ul class="box-pricing box-pricing-type-1 list-unstyled">
                        <li class="box-pricing-item">
                            <div class="box-pricing-title big text-uppercase text-spacing-120">
                            <div class="box-pricing-name text-darker font-weight-bold">Old Timer's Vege</div>
                            <div class="box-pricing-dots"></div>
                            <div class="box-pricing-price h5 font-weight-bold">$22.00</div>
                            </div>
                            <div class="box-pricing-desc text-dark offset-top-10">( Two eggs cooked to order with grits, sawmill gravy, homemade buttermilk biscuits &amp; real butter  )
                            </div>
                        </li>
                        <li class="box-pricing-item">
                            <div class="box-pricing-title big text-uppercase text-spacing-120">
                            <div class="box-pricing-name text-darker font-weight-bold">Fresh Start Sampler</div>
                            <div class="box-pricing-dots"></div>
                            <div class="box-pricing-price h5 font-weight-bold">$37.00</div>
                            </div>
                            <div class="box-pricing-desc text-dark offset-top-10">( Start your day with a mix of low fat vanilla yogurt, fresh seasonal fruit topped with our honey mix )
                            </div>
                        </li>
                        <li class="box-pricing-item">
                            <div class="box-pricing-title big text-uppercase text-spacing-120">
                            <div class="box-pricing-name text-darker font-weight-bold">Double Vege Breakfast</div>
                            <div class="box-pricing-dots"></div>
                            <div class="box-pricing-price h5 font-weight-bold">$42.00</div>
                            </div>
                            <div class="box-pricing-desc text-dark offset-top-10">( Three eggs cooked to order with a full order of bacon and sausage patties )
                            </div>
                        </li>
                        <li class="box-pricing-item">
                            <div class="box-pricing-title big text-uppercase text-spacing-120">
                            <div class="box-pricing-name text-darker font-weight-bold">Crab &amp; avocado bruschetta</div>
                            <div class="box-pricing-dots"></div>
                            <div class="box-pricing-price h5 font-weight-bold">$19.00</div>
                            </div>
                            <div class="box-pricing-desc text-dark offset-top-10">( Fresh white&amp;brown crab, crunchy fennel, smashed avocado, yoghurt &amp; chilli )
                            </div>
                        </li>
                        </ul>
                    </div>
                </div>`,
            activeTab: 0
        }
    },
    methods: {
        filter(category) {
            if (category == "Veggetable") {
                this.activeTab = 0;
                this.content = `<div class="col-12 col-lg-4 isotope-item">
                    <div class="inset-lg-right-20">
                        <!-- Pricing Box type 1-->
                        <ul class="box-pricing box-pricing-type-1 list-unstyled">
                        <li class="box-pricing-item">
                            <div class="box-pricing-title big text-uppercase text-spacing-120">
                            <div class="box-pricing-name text-darker font-weight-bold">Old Timer's Vege</div>
                            <div class="box-pricing-dots"></div>
                            <div class="box-pricing-price h5 font-weight-bold">$22.00</div>
                            </div>
                            <div class="box-pricing-desc text-dark offset-top-10">( Two eggs cooked to order with grits, sawmill gravy, homemade buttermilk biscuits &amp; real butter  )
                            </div>
                        </li>
                        <li class="box-pricing-item">
                            <div class="box-pricing-title big text-uppercase text-spacing-120">
                            <div class="box-pricing-name text-darker font-weight-bold">Fresh Start Sampler</div>
                            <div class="box-pricing-dots"></div>
                            <div class="box-pricing-price h5 font-weight-bold">$37.00</div>
                            </div>
                            <div class="box-pricing-desc text-dark offset-top-10">( Start your day with a mix of low fat vanilla yogurt, fresh seasonal fruit topped with our honey mix )
                            </div>
                        </li>
                        <li class="box-pricing-item">
                            <div class="box-pricing-title big text-uppercase text-spacing-120">
                            <div class="box-pricing-name text-darker font-weight-bold">Double Vege Breakfast</div>
                            <div class="box-pricing-dots"></div>
                            <div class="box-pricing-price h5 font-weight-bold">$42.00</div>
                            </div>
                            <div class="box-pricing-desc text-dark offset-top-10">( Three eggs cooked to order with a full order of bacon and sausage patties )
                            </div>
                        </li>
                        <li class="box-pricing-item">
                            <div class="box-pricing-title big text-uppercase text-spacing-120">
                            <div class="box-pricing-name text-darker font-weight-bold">Crab &amp; avocado bruschetta</div>
                            <div class="box-pricing-dots"></div>
                            <div class="box-pricing-price h5 font-weight-bold">$19.00</div>
                            </div>
                            <div class="box-pricing-desc text-dark offset-top-10">( Fresh white&amp;brown crab, crunchy fennel, smashed avocado, yoghurt &amp; chilli )
                            </div>
                        </li>
                        </ul>
                    </div>
                </div>`;
            } else if (category == "Snack") {
                this.activeTab = 1;
                this.content = `<div class="col-12 col-lg-4 isotope-item">
                    <div class="inset-lg-right-20">
                        <!-- Pricing Box type 1-->
                        <ul class="box-pricing box-pricing-type-1 list-unstyled">
                        <li class="box-pricing-item">
                            <div class="box-pricing-title big text-uppercase text-spacing-120">
                            <div class="box-pricing-name text-darker font-weight-bold">Old Timer's Snack</div>
                            <div class="box-pricing-dots"></div>
                            <div class="box-pricing-price h5 font-weight-bold">$22.00</div>
                            </div>
                            <div class="box-pricing-desc text-dark offset-top-10">( Two eggs cooked to order with grits, sawmill gravy, homemade buttermilk biscuits &amp; real butter  )
                            </div>
                        </li>
                        <li class="box-pricing-item">
                            <div class="box-pricing-title big text-uppercase text-spacing-120">
                            <div class="box-pricing-name text-darker font-weight-bold">Fresh Start Snack</div>
                            <div class="box-pricing-dots"></div>
                            <div class="box-pricing-price h5 font-weight-bold">$37.00</div>
                            </div>
                            <div class="box-pricing-desc text-dark offset-top-10">( Start your day with a mix of low fat vanilla yogurt, fresh seasonal fruit topped with our honey mix )
                            </div>
                        </li>
                        <li class="box-pricing-item">
                            <div class="box-pricing-title big text-uppercase text-spacing-120">
                            <div class="box-pricing-name text-darker font-weight-bold">Double Sugar Snack</div>
                            <div class="box-pricing-dots"></div>
                            <div class="box-pricing-price h5 font-weight-bold">$42.00</div>
                            </div>
                            <div class="box-pricing-desc text-dark offset-top-10">( Three eggs cooked to order with a full order of bacon and sausage patties )
                            </div>
                        </li>
                        <li class="box-pricing-item">
                            <div class="box-pricing-title big text-uppercase text-spacing-120">
                            <div class="box-pricing-name text-darker font-weight-bold">Crab &amp; avocado Ice Cream</div>
                            <div class="box-pricing-dots"></div>
                            <div class="box-pricing-price h5 font-weight-bold">$19.00</div>
                            </div>
                            <div class="box-pricing-desc text-dark offset-top-10">( Fresh white&amp;brown crab, crunchy fennel, smashed avocado, yoghurt &amp; chilli )
                            </div>
                        </li>
                        </ul>
                    </div>
                </div>`;
            } else if (category == "Dessert") {
                this.activeTab = 2;
                this.content = `<div class="col-12 col-lg-4 isotope-item">
                    <div class="inset-lg-right-20">
                        <!-- Pricing Box type 1-->
                        <ul class="box-pricing box-pricing-type-1 list-unstyled">
                        <li class="box-pricing-item">
                            <div class="box-pricing-title big text-uppercase text-spacing-120">
                            <div class="box-pricing-name text-darker font-weight-bold">Old Timer's Pancake</div>
                            <div class="box-pricing-dots"></div>
                            <div class="box-pricing-price h5 font-weight-bold">$22.00</div>
                            </div>
                            <div class="box-pricing-desc text-dark offset-top-10">( Two eggs cooked to order with grits, sawmill gravy, homemade buttermilk biscuits &amp; real butter  )
                            </div>
                        </li>
                        <li class="box-pricing-item">
                            <div class="box-pricing-title big text-uppercase text-spacing-120">
                            <div class="box-pricing-name text-darker font-weight-bold">Fresh Start Lemon</div>
                            <div class="box-pricing-dots"></div>
                            <div class="box-pricing-price h5 font-weight-bold">$37.00</div>
                            </div>
                            <div class="box-pricing-desc text-dark offset-top-10">( Start your day with a mix of low fat vanilla yogurt, fresh seasonal fruit topped with our honey mix )
                            </div>
                        </li>
                        <li class="box-pricing-item">
                            <div class="box-pricing-title big text-uppercase text-spacing-120">
                            <div class="box-pricing-name text-darker font-weight-bold">Double Ice Fresh</div>
                            <div class="box-pricing-dots"></div>
                            <div class="box-pricing-price h5 font-weight-bold">$42.00</div>
                            </div>
                            <div class="box-pricing-desc text-dark offset-top-10">( Three eggs cooked to order with a full order of bacon and sausage patties )
                            </div>
                        </li>
                        <li class="box-pricing-item">
                            <div class="box-pricing-title big text-uppercase text-spacing-120">
                            <div class="box-pricing-name text-darker font-weight-bold">Crab &amp; avocado bruschetta</div>
                            <div class="box-pricing-dots"></div>
                            <div class="box-pricing-price h5 font-weight-bold">$19.00</div>
                            </div>
                            <div class="box-pricing-desc text-dark offset-top-10">( Fresh white&amp;brown crab, crunchy fennel, smashed avocado, yoghurt &amp; chilli )
                            </div>
                        </li>
                        </ul>
                    </div>
                </div>`;
            }
        }
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
                                    <button class="isotope-filters-toggle btn btn-sm btn-default" data-custom-toggle="isotope-1" data-custom-toggle-disable-on-blur="true">Filter<span class="caret"></span></button>
                                    <ul class="list-sm-inline isotope-filters-list" id="isotope-1">
                                        <!-- .teamSelector { cursor: pointer; } -->
                                        <!-- span:hover { cursor:pointer; } -->
                                        <li class="list-inline-item"><a class="text-sbold"
                                            :class="{ 'active': activeTab == 0 }" @click="filter('Veggetable')">Veggetable</a></li>
                                        <li class="list-inline-item"><a class="text-sbold"
                                            :class="{ active: activeTab == 1 }" @click="filter('Snack')">Snack</a></li>
                                        <li class="list-inline-item"><a class="text-sbold"
                                            :class="{ active: activeTab == 2 }" @click="filter('Dessert')">Dessert</a></li>
                                    </ul>
                                    </li>
                                </ul>
                            </div>
                        </div>
                        <div class="col-xl-12 offset-top-34">
                            <div class="row" v-html="content">

                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>
</template>