<script>

export default {
    data() {
        return {
            content: "<H1>All</H1>"
        }
    },
    methods: {
        filter(category) {
            this.content = `<H1>${category}</H1>`;
        }
    }
}
</script>
<template>
    <main class="page-content">
        <!-- Product List-->
        <section>
            <div class="context-dark">
            <div class="parallax-container" data-parallax-img="images/image-01-1920x963.jpg">
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
                            <li class="list-inline-item"><a class="text-sbold active" href="#" @click="filter('Veggetable')">Veggetable</a></li>
                            <li class="list-inline-item"><a class="text-sbold" href="#" @click="filter('Snack')">Snack</a></li>
                            <li class="list-inline-item"><a class="text-sbold" href="#" @click="filter('Desserts')">Desserts</a></li>
                        </ul>
                        </li>
                    </ul>
                    </div>
                </div>
                <div v-html="content"></div>
                <!-- Isotope Content-->
                <div class="col-xl-12 offset-top-34">
                    <div class="isotope" data-isotope-layout="fitRows" data-isotope-group="menu">
                    <div class="row">
                        <div class="col-12 col-lg-4 isotope-item" data-filter="Breakfasts">
                        <div class="inset-lg-right-20">
                            <!-- Pricing Box type 1-->
                            <ul class="box-pricing box-pricing-type-1 list-unstyled">
                            <li class="box-pricing-item">
                                <div class="box-pricing-title big text-uppercase text-spacing-120">
                                <div class="box-pricing-name text-darker font-weight-bold">Old Timer's Breakfast</div>
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
                                <div class="box-pricing-name text-darker font-weight-bold">Double Meat Breakfast</div>
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
                        </div>
                        <div class="col-12 col-lg-4 isotope-item" data-filter="Lunches">
                        <div class="inset-lg-right-20">
                            <!-- Pricing Box type 1-->
                            <ul class="box-pricing box-pricing-type-1 list-unstyled">
                            <li class="box-pricing-item">
                                <div class="box-pricing-title big text-uppercase text-spacing-120">
                                <div class="box-pricing-name text-darker font-weight-bold">Turkey milanese</div>
                                <div class="box-pricing-dots"></div>
                                <div class="box-pricing-price h5 font-weight-bold">$22.00</div>
                                </div>
                                <div class="box-pricing-desc text-dark offset-top-10">( Stuffed with prosciutto &amp; provolone, breadcrumbed &amp; topped with a free-range egg &amp; black summer truffle. )
                                </div>
                            </li>
                            <li class="box-pricing-item">
                                <div class="box-pricing-title big text-uppercase text-spacing-120">
                                <div class="box-pricing-name text-darker font-weight-bold">Fritto misto</div>
                                <div class="box-pricing-dots"></div>
                                <div class="box-pricing-price h5 font-weight-bold">$37.00</div>
                                </div>
                                <div class="box-pricing-desc text-dark offset-top-10">( Mixed seasonal flash-fried sustainable fish &amp; shellfish served with chunky Italian tartare sauce &amp; lemon. )
                                </div>
                            </li>
                            <li class="box-pricing-item">
                                <div class="box-pricing-title big text-uppercase text-spacing-120">
                                <div class="box-pricing-name text-darker font-weight-bold">Italian steak frites</div>
                                <div class="box-pricing-dots"></div>
                                <div class="box-pricing-price h5 font-weight-bold">$42.00</div>
                                </div>
                                <div class="box-pricing-desc text-dark offset-top-10">( Flash-grilled prime beef steak, served with Italian-spiced skinny fries &amp; crunchy vegetable slaw. )
                                </div>
                            </li>
                            <li class="box-pricing-item">
                                <div class="box-pricing-title big text-uppercase text-spacing-120">
                                <div class="box-pricing-name text-darker font-weight-bold">Baked Crespelle</div>
                                <div class="box-pricing-dots"></div>
                                <div class="box-pricing-price h5 font-weight-bold">$19.00</div>
                                </div>
                                <div class="box-pricing-desc text-dark offset-top-10">( Spinach, Westcombe ricotta &amp; basil baked in gluten-free buckwheat pancakes with smoked mozzarella, sweet buttery leeks, Sicilian tomato sauce &amp; Parmesan. )
                                </div>
                            </li>
                            </ul>
                        </div>
                        </div>
                        <div class="col-12 col-lg-4 isotope-item" data-filter="Dinners">
                        <div class="inset-lg-right-20">
                            <!-- Pricing Box type 1-->
                            <ul class="box-pricing box-pricing-type-1 list-unstyled">
                            <li class="box-pricing-item">
                                <div class="box-pricing-title big text-uppercase text-spacing-120">
                                <div class="box-pricing-name text-darker font-weight-bold">Our famous prawn linguine</div>
                                <div class="box-pricing-dots"></div>
                                <div class="box-pricing-price h5 font-weight-bold">$22.00</div>
                                </div>
                                <div class="box-pricing-desc text-dark offset-top-10">( Fried garlicky prawns, fennel, tomatoes, chilli, saffron, fish broth &amp; lemony rocket. )
                                </div>
                            </li>
                            <li class="box-pricing-item">
                                <div class="box-pricing-title big text-uppercase text-spacing-120">
                                <div class="box-pricing-name text-darker font-weight-bold">Gnocchi genovese</div>
                                <div class="box-pricing-dots"></div>
                                <div class="box-pricing-price h5 font-weight-bold">$37.00</div>
                                </div>
                                <div class="box-pricing-desc text-dark offset-top-10">( Potato gnocchi with green beans, crushed purple potatoes, basil pesto, toasted pine nuts, bella lodi &amp; ricotta. )
                                </div>
                            </li>
                            <li class="box-pricing-item">
                                <div class="box-pricing-title big text-uppercase text-spacing-120">
                                <div class="box-pricing-name text-darker font-weight-bold">Penne carbonara</div>
                                <div class="box-pricing-dots"></div>
                                <div class="box-pricing-price h5 font-weight-bold">$42.00</div>
                                </div>
                                <div class="box-pricing-desc text-dark offset-top-10">( Crispy chunks of smoked pancetta, sweet buttery leeks, lemon &amp; a traditional carbonara sauce. )
                                </div>
                            </li>
                            <li class="box-pricing-item">
                                <div class="box-pricing-title big text-uppercase text-spacing-120">
                                <div class="box-pricing-name text-darker font-weight-bold">Three-cheese caramelle</div>
                                <div class="box-pricing-dots"></div>
                                <div class="box-pricing-price h5 font-weight-bold">$19.00</div>
                                </div>
                                <div class="box-pricing-desc text-dark offset-top-10">( Beautiful filled pasta with ricotta, provolone, bella lodi &amp; spinach, served with creamy tomato, garlic, basil &amp; rosé wine sauce. )
                                </div>
                            </li>
                            </ul>
                        </div>
                        </div>
                        <div class="col-12 col-lg-4 isotope-item" data-filter="Desserts">
                        <div class="inset-lg-right-20">
                            <!-- Pricing Box type 1-->
                            <ul class="box-pricing box-pricing-type-1 list-unstyled">
                            <li class="box-pricing-item">
                                <div class="box-pricing-title big text-uppercase text-spacing-120">
                                <div class="box-pricing-name text-darker font-weight-bold">Tiramisù</div>
                                <div class="box-pricing-dots"></div>
                                <div class="box-pricing-price h5 font-weight-bold">$22.00</div>
                                </div>
                                <div class="box-pricing-desc text-dark offset-top-10">( The classic Italian dessert topped with chocolate shavings &amp; orange zest. )
                                </div>
                            </li>
                            <li class="box-pricing-item">
                                <div class="box-pricing-title big text-uppercase text-spacing-120">
                                <div class="box-pricing-name text-darker font-weight-bold">Rasbery &amp; honeycomb pavlova</div>
                                <div class="box-pricing-dots"></div>
                                <div class="box-pricing-price h5 font-weight-bold">$37.00</div>
                                </div>
                                <div class="box-pricing-desc text-dark offset-top-10">( Rippled, gooey meringue, zesty cream, macerated raspberries, smashed honeycomb &amp; fresh mint. )
                                </div>
                            </li>
                            <li class="box-pricing-item">
                                <div class="box-pricing-title big text-uppercase text-spacing-120">
                                <div class="box-pricing-name text-darker font-weight-bold">Molten chocolate praline pudding</div>
                                <div class="box-pricing-dots"></div>
                                <div class="box-pricing-price h5 font-weight-bold">$42.00</div>
                                </div>
                                <div class="box-pricing-desc text-dark offset-top-10">( Warm chocolate cake with a liquid praline centre, served with salted caramel ice cream &amp; praline.  )
                                </div>
                            </li>
                            <li class="box-pricing-item">
                                <div class="box-pricing-title big text-uppercase text-spacing-120">
                                <div class="box-pricing-name text-darker font-weight-bold">Orange blossom polenta cake</div>
                                <div class="box-pricing-dots"></div>
                                <div class="box-pricing-price h5 font-weight-bold">$19.00</div>
                                </div>
                                <div class="box-pricing-desc text-dark offset-top-10">( Polenta cake studded with candied fruit, served with whipped creme fraiche &amp; pomegranate. )
                                </div>
                            </li>
                            </ul>
                        </div>
                        </div>
                        <div class="col-12 col-lg-4 isotope-item" data-filter="Drinks">
                        <div class="inset-lg-right-20">
                            <!-- Pricing Box type 1-->
                            <ul class="box-pricing box-pricing-type-1 list-unstyled">
                            <li class="box-pricing-item">
                                <div class="box-pricing-title big text-uppercase text-spacing-120">
                                <div class="box-pricing-name text-darker font-weight-bold">Raspberry mule</div>
                                <div class="box-pricing-dots"></div>
                                <div class="box-pricing-price h5 font-weight-bold">$22.00</div>
                                </div>
                                <div class="box-pricing-desc text-dark offset-top-10">( Vodka, raspberry purée &amp; fresh lime juice topped with ginger beer )
                                </div>
                            </li>
                            <li class="box-pricing-item">
                                <div class="box-pricing-title big text-uppercase text-spacing-120">
                                <div class="box-pricing-name text-darker font-weight-bold">La dolce vita</div>
                                <div class="box-pricing-dots"></div>
                                <div class="box-pricing-price h5 font-weight-bold">$37.00</div>
                                </div>
                                <div class="box-pricing-desc text-dark offset-top-10">( Saliza amaretto, triple sec &amp; sugar syrup shaken up with fresh lemon &amp; cranberry juice )
                                </div>
                            </li>
                            <li class="box-pricing-item">
                                <div class="box-pricing-title big text-uppercase text-spacing-120">
                                <div class="box-pricing-name text-darker font-weight-bold">Montepulciano d’abruzzo</div>
                                <div class="box-pricing-dots"></div>
                                <div class="box-pricing-price h5 font-weight-bold">$42.00</div>
                                </div>
                                <div class="box-pricing-desc text-dark offset-top-10">( Cherry &amp; chocolate flavours are typical of this well-known grape )
                                </div>
                            </li>
                            <li class="box-pricing-item">
                                <div class="box-pricing-title big text-uppercase text-spacing-120">
                                <div class="box-pricing-name text-darker font-weight-bold">Sauvignon blanc</div>
                                <div class="box-pricing-dots"></div>
                                <div class="box-pricing-price h5 font-weight-bold">$19.00</div>
                                </div>
                                <div class="box-pricing-desc text-dark offset-top-10">( Herby aromas &amp; melon flavours )
                                </div>
                            </li>
                            </ul>
                        </div>
                        </div>
                    </div>
                    </div>
                </div>
                </div>
            </div>
            </div>
        </section>
    </main>
</template>