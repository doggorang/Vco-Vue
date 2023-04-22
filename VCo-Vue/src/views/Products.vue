<script>

export default {
    data() {
        return {
            content: "<H1>TEST</H1>"
        }
    },
    methods: {
        filter(category) {
            alert(category);
            /*
            <button @click="filter('what')">Say what</button>
            handle changes content dalam method ini
            <div isotope>{{ content }}
                supaya content ikut berubah
            */
        }
    }
}
</script>
<template>
    <main class="page-content">
        <!-- Section Intro-->
        <section class="context-dark">
            <div class="parallax-container" data-parallax-img="images/intro-01-1920x955.jpg">
            <div class="parallax-content">
                <div class="container">
                <div class="section-110 row justify-content-sm-center align-items-sm-center">
                    <div class="col-lg-8"><img src="../assets/images/icon/Icon PSD V1 12-02-2023.ico" alt="" width="175" height="173">
                    <h1 class="font-accent"><span class="big">Typography</span></h1>
                    <ul class="list-inline list-inline-dashed p">
                        <li class="list-inline-item"><a href="index.html">Home</a></li>
                        <li class="list-inline-item">Typography
                        </li>
                    </ul>
                    </div>
                </div>
                </div>
            </div>
            </div>
        </section>
        <!-- Heading Style-->
        <section class="section novi-background section-66 section-md-top-110">
            <div class="container">
            <h2>Heading Styles</h2>
            <hr class="divider divider-md bg-mantis">
            <div class="row text-left offset-top-66">
                <div class="col-lg-8">
                <div>
                    <h1>Heading 1 </h1><small class="d-block d-sm-inline text-dark">Secondary text</small>
                    <p>
                    Ei sumo eruditi sadipscing nec, scripta epicurei ut eam. Duo ut fastidii platonem, eu soleat salutandi neglegentur est. Erant harum malorum eum ne, his ut scaevola consectetuer, duo ex suavitate liberavisse. Has brute graecis an, quis docendi ad ius.
                    
                    </p>
                    <p>
                    Vel nihil percipitur ei. Fugit option oportere est in, te dignissim philosophia mea, duo diceret eruditi ea. In eum porro bonorum, ut stet partiendo efficiantur vis. No errem platonem consectetuer quo, legimus tincidunt percipitur pri id. No nec congue libris interpretaris, te elitr impedit definiebas his.
                    
                    </p>
                </div>
                <div class="offset-top-50">
                    <h2>Heading 2 </h2><small class="d-block d-sm-inline text-dark">Secondary text</small>
                    <p>
                    Ei sumo eruditi sadipscing nec, scripta epicurei ut eam. Duo ut fastidii platonem, eu soleat salutandi neglegentur est. Erant harum malorum eum ne, his ut scaevola consectetuer, duo ex suavitate liberavisse. Has brute graecis an, quis docendi ad ius.
                    
                    </p>
                    <p>
                    Vel nihil percipitur ei. Fugit option oportere est in, te dignissim philosophia mea, duo diceret eruditi ea. In eum porro bonorum, ut stet partiendo efficiantur vis. No errem platonem consectetuer quo, legimus tincidunt percipitur pri id. No nec congue libris interpretaris, te elitr impedit definiebas his.
                    
                    </p>
                </div>
                <div class="offset-top-50">
                    <h3>Heading 3 </h3><small class="d-block d-sm-inline text-dark">Secondary text</small>
                    <p>
                    Te partem omnesque eligendi has, nam ex persius lobortis. His ex amet facilis, ne vix diceret dolorum. Veniam nonumes sit an. Sit et possit hendrerit, ne his doming mnesarchum.
                    
                    </p>
                    <p>
                    Ei tollit euismod cum, augue labore euripidis mel ex, ut corpora appellantur deterruisset mel. Quo et consulatu suscipiantur. In sed homero habemus neglegentur, ipsum putant periculis an nec. Usu mollis admodum vivendum at.
                    
                    </p>
                </div>
                <div class="offset-top-50">
                    <h4>Heading 4 </h4><small class="d-block d-sm-inline text-dark">Secondary text</small>
                    <p>
                    Tollit fuisset mei ea, has no omnium accumsan, exerci dolorem praesent an mei. Ne etiam labores fabellas duo. Ex ubique melius ius, mea numquam atomorum no. Pri ei graece audiam, discere graecis ancillae id mea. Summo ignota virtute in sit. Mundi moderatius pri te, te tota minimum oportere eum.
                    
                    </p>
                </div>
                <div class="offset-top-50">
                    <h5>Heading 5 </h5><small class="d-block d-sm-inline text-dark">Secondary text</small>
                    <p>
                    Sea quod soleat dolorum id. Tale lobortis laboramus eum no, ius vocibus pertinacia scribentur ex, qui consul semper no. Ne dicunt ponderum maiestatis sea, vix tollit eripuit scaevola ne. Sea te paulo delenit laoreet. Ius et sint mentitum, alia cibo vitae ad quo, ius ne antiopam sententiae.
                    
                    </p>
                </div>
                <div class="offset-top-50">
                    <h6>Heading 6 </h6><small class="d-block d-sm-inline text-dark">Secondary text</small>
                    <p>Ad posse doming appareat mea. Ex vix doctus minimum. Eleifend praesent cu pri, sed dicant laudem putent at. Sed eu dico summo habemus, sit in decore regione recusabo. Per ad tacimates mediocritatem.</p>
                </div>
                </div>
                <div class="col-lg-4 offset-top-50 offset-lg-top-0">
                <h1>Heading 1</h1>
                <h2>Heading 2</h2>
                <h3>Heading 3</h3>
                <h4>Heading 4</h4>
                <h5>Heading 5</h5>
                <h6>Heading 6</h6>
                <p class="big">Big paragraph</p>
                <p>Default paragraph</p>
                <p class="small">Small paragraph</p>
                </div>
            </div>
            </div>
        </section>
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
                            <li class="list-inline-item"><a class="text-sbold active" data-isotope-filter="*" data-isotope-group="menu" href="#">All</a></li>
                            <li class="list-inline-item"><a class="text-sbold" data-isotope-filter="Breakfasts" data-isotope-group="menu" href="#">Breakfasts</a></li>
                            <li class="list-inline-item"><a class="text-sbold" data-isotope-filter="Lunches" data-isotope-group="menu" href="#">Lunches</a></li>
                            <li class="list-inline-item"><a class="text-sbold" data-isotope-filter="Dinners" data-isotope-group="menu" href="#">Dinners</a></li>
                            <li class="list-inline-item"><a class="text-sbold" data-isotope-filter="Desserts" data-isotope-group="menu" href="#">Desserts</a></li>
                            <li class="list-inline-item"><a class="text-sbold" data-isotope-filter="Drinks" data-isotope-group="menu" href="#">Drinks</a></li>
                        </ul>
                        </li>
                    </ul>
                    </div>
                </div>
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
        <!-- Text Alignment-->
        <section class="section novi-background section-66">
            <div class="container">
            <h2>Text Alignment</h2>
            <hr class="divider divider-md bg-mantis">
            <h3 class="text-center offset-md-top-66">Centered Text</h3>
            <p class="text-center">Ei sumo eruditi sadipscing nec, scripta epicurei ut eam. Duo ut fastidii platonem, eu soleat salutandi neglegentur est. Erant harum malorum eum ne, his ut scaevola consectetuer, duo ex suavitate liberavisse. Has brute graecis an, quis docendi ad ius.</p>
            <h3 class="offset-top-50 text-left">Left aligned text</h3>
            <p class="text-left">Vel nihil percipitur ei. Fugit option oportere est in, te dignissim philosophia mea, duo diceret eruditi ea. In eum porro bonorum, ut stet partiendo efficiantur vis. No errem platonem consectetuer quo, legimus tincidunt percipitur pri id. No nec congue libris interpretaris, te elitr impedit definiebas his.</p>
            <h3 class="offset-top-50 text-right">Right aligned text</h3>
            <p class="text-right">
                Te partem omnesque eligendi has, nam ex persius lobortis. His ex amet facilis, ne vix diceret dolorum. Veniam nonumes sit an. Sit et possit hendrerit, ne his doming mnesarchum.
                
            </p>
            </div>
        </section>
        <!-- Text Formatting-->
        <section class="section novi-background section-66">
            <div class="container">
            <h2>Text Formatting</h2>
            <hr class="divider divider-md bg-mantis">
            <p class="offset-top-66">This is normal text</p>
            <p class="text-light">This is light text</p>
            <p class="txt-bold">This is bold text</p>
            <p><em>This is emphasized text</em></p>
            <p class="font-italic">This is italic text</p>
            <p class="big">This is big text</p>
            <p><small>This is small text</small></p>
            <p><strong>This is strong text</strong></p>
            <p>This is<sub> subscript </sub>and<sup> superscript </sup> text</p>
            <p><ins>This is text inserted to the document</ins></p>
            <p>
                <del>This is text deleted from the document</del>
            </p>
            <p><code>This is code text</code></p>
            <p>
                <mark>This is hightlighted text</mark>
            </p>
            </div>
        </section>
        <!-- Text Helper Classes-->
        <section class="section novi-background section-66">
            <div class="container">
            <h2>Text Helper Classes</h2>
            <hr class="divider divider-md bg-mantis">
            <p class="text-muted offset-top-66">This is muted text</p>
            <p class="text-success">This is success text</p>
            <p class="text-warning">This is warning text</p>
            <p class="text-danger">This is danger text</p>
            <p class="text-info">This is info text</p>
            <p class="text-primary">This is primary text</p>
            <p class="text-deluge">This is deluge text</p>
            <p class="text-picton">This is picton text</p>
            <p><span class="text-mantis">This is primary empasized text</span></p>
            <p><span class="text-blue-gray">This is deluge empasized text</span></p>
            <p><span class="text-malibu-2">This is picton empasized text</span></p>
            <p class="text-uppercase">This text is uppercased</p>
            <p class="text-capitalize">This text is capitalized</p>
            <p class="text-lowercase">This text is lowercased</p>
            </div>
        </section>
        <!-- Image Floating-->
        <section class="section novi-background section-66">
            <div class="container">
            <h2>Image Floating</h2>
            <hr class="divider divider-md bg-mantis">
            <div class="row offset-top-66">
                <div class="col-12 text-left"><img class="img-fluid pull-md-left" src="images/portfolio-16-370x280.jpg" alt="">
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
        <!-- Text Dropcaps-->
        <section class="section novi-background section-66 section-md-bottom-110">
            <div class="container">
            <h2>Text Dropcaps</h2>
            <hr class="divider divider-md bg-mantis">
            <p class="offset-top-50 dropcap dropcap-dark text-left">
                No sit hinc alienum, has eligendi inciderint id. Eu pri alii habemus voluptaria. Volumus philosophia usu in. Deseruisse expetendis per ex, sale ocurreret te est. Nam eu stet graeci veritus, quod temporibus cum at.
                
                
            </p>
            </div>
        </section>
    </main>
</template>