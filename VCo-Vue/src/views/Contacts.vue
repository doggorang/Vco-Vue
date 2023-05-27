<template>
    <main class="page-content">
        <!-- Section Intro-->
        <section class="context-dark">
          <div class="parallax-container">
            <div class="parallax-content">
              <div class="container">
                <div class="section-110 row justify-content-sm-center align-items-sm-center">
                  <div class="col-lg-8"><img src="@/assets/images/logo/logo.png" alt="" width="175" height="173">
                    <h1 class="font-accent"><span class="big">Contacts</span></h1>
                    <ul class="list-inline list-inline-dashed p">
                      <li class="list-inline-item"><a href="/">Home</a></li>
                      <li class="list-inline-item">Contacts
                      </li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </section>
        <!-- Contact Us-->
        <section class="section-98 section-lg-110 text-xl-left">
          <div class="container">
            <div class="row justify-content-sm-center justify-content-sm-center">
              <div class="col-xl-4">
                <h3 class="text-uppercase font-weight-bold">How to Find us</h3>
                <hr class="divider hr-xl-left-0 bg-mantis">
                <p>Email us with any questions or inquiries or use our contact data. We would be happy to answer you as soon as possible.</p>
                <address class="contact-info offset-top-50">
                  <div class="h6 text-uppercase font-weight-bold text-picton-blue letter-space-none offset-top-none">Intense Restaurant</div>
                  <p>9863 - 9867 MILL ROAD, CAMBRIDGE, MG09 99HT.</p>
                  <dl class="offset-top-0">
                    <dt>Telephone</dt>
                    <dd><a href="tel:#">+1 800 603 6035</a></dd>
                  </dl>
                  <dl>
                    <dt>E-mail:</dt>
                    <dd><a href="mailto:#">mail@demolink.org</a></dd>
                  </dl>
                </address>
                <address class="contact-info offset-top-50">
                  <div class="h6 text-uppercase font-weight-bold text-picton-blue letter-space-none">Intense Cafe</div>
                  <p>9870 ST VINCENT PLACE, GLASGOW, DC 45 FR 45.</p>
                  <dl class="offset-top-0">
                    <dt>Telephone</dt>
                    <dd><a href="tel:#">+1 800 559 6580</a></dd>
                  </dl>
                  <dl>
                    <dt>E-mail:</dt>
                    <dd><a href="mailto:#">mail@demolink.org</a></dd>
                  </dl>
                </address>
              </div>
              <div class="col-md-8 offset-top-66 offset-xl-top-0">
                <h3 class="text-uppercase font-weight-bold">Get in touch</h3>
                <hr class="divider hr-xl-left-0 bg-mantis">
                <!-- RD Mailform-->
                <form class="text-left" data-form-output="form-output-global" data-form-type="contact" method="post" action="">
                  <div class="row">
                    <div class="col-xl-6">
                      <div class="form-group">
                        <label class="form-label form-label-outside" for="contact-us-name">Name:</label>
                        <input class="form-control" id="contact-us-name" type="text" name="name" data-constraints="@Required">
                      </div>
                    </div>
                    <div class="col-xl-6 offset-top-20 offset-xl-top-0">
                      <div class="form-group">
                        <label class="form-label form-label-outside" for="contact-us-email">E-Mail:</label>
                        <input class="form-control" id="contact-us-email" type="email" name="email" data-constraints="@Required @Email">
                      </div>
                    </div>
                    <div class="col-xl-12 offset-top-20">
                      <div class="form-group">
                        <label class="form-label form-label-outside" for="contact-us-message">Message:</label>
                        <textarea class="form-control" id="contact-us-message" name="message" data-constraints="@Required"></textarea>
                      </div>
                    </div>
                  </div>
                  <div class="group-sm text-center text-xl-left offset-top-30">
                    <button class="btn btn-primary" type="submit">Send</button>
                    <button class="btn btn-default" type="reset">Reset</button>
                  </div>
                </form>
              </div>
            </div>
          </div>
        </section>
    </main>
</template>