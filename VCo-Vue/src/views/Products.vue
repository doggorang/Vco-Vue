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
            <!-- Image Floating-->
            <section class="section novi-background section-66">
                <div class="container">
                    <h2>Image Floating</h2>
                    <hr class="divider divider-md bg-mantis">
                    <div class="row offset-top-66">
                        <div class="col-12 text-left"><img class="img-fluid pull-md-left" src="images/portfolio-16-370x280.jpg" alt="gambar370x280">
                        <h3 class="offset-top-34 offset-md-top-0">This image is left floated</h3>
                        <p>Ei tollit euismod cum, augue labore euripidis mel ex, ut corpora appellantur deterruisset mel. Quo et consulatu suscipiantur. In sed homero habemus neglegentur, ipsum putant periculis an nec. Usu mollis admodum vivendum at.</p>
                        <p>Tollit fuisset mei ea, has no omnium accumsan, exerci dolorem praesent an mei. Ne etiam labores fabellas duo. Ex ubique melius ius, mea numquam atomorum no. Pri ei graece audiam, discere graecis ancillae id mea. Summo ignota virtute in sit. Mundi moderatius pri te, te tota minimum oportere eum.</p>
                        <p>Sea quod soleat dolorum id. Tale lobortis laboramus eum no, ius vocibus pertinacia scribentur ex, qui consul semper no. Ne dicunt ponderum maiestatis sea, vix tollit eripuit scaevola ne.</p>
                        </div>
                    </div>
                    <div class="row offset-top-50">
                        <div class="col-12 text-left text-md-right"><img class="d-inline-block img-fluid pull-md-right" src="images/portfolio-15-370x280.jpg" alt="">
                        <h3 class="offset-top-34 offset-md-top-0">This image is right floated</h3>
                        <p>Ad posse doming appareat mea. Ex vix doctus minimum. Eleifend praesent cu pri, sed dicant laudem putent at. Sed eu dico summo habemus, sit in decore regione recusabo. Per ad tacimates mediocritatem.</p>
                        <p>Integre delenit luptatum ei has, usu graecis democritum ei, eum ea iusto dictas concludaturque. Labore epicuri reformidans ad vis, in his quot doctus eripuit. Sit nominati senserit et. Quo causae blandit repudiandae in. Id vim dico liberavisse philosophia, vim mazim constituam ei.</p>
                        <p>
                            Ius eu paulo zril rationibus, ex vim porro consul voluptaria, sit habemus principes concludaturque ut. Ut nam suas graeco accusata. Pri no consulatu consetetur, eu cum eros saepe. Duo melius officiis senserit an, vix solum eruditi delectus ex, mel solet putant adversarium eu. Sit eu oratio persius, munere apeirian ne mei.
                            
                        </p>
                        </div>
                    </div>
                </div>
            </section>
        </section>
    </main>
</template>