<script>
  export default {
    data() {
      return {
        home: window.location.pathname == '/' ? 1 : 0,
        about: window.location.pathname == '/about' ? 1 : 0,
        product: window.location.pathname == '/product' ? 1 : 0,
        contact: window.location.pathname == '/contact' ? 1 : 0,
      }
    }
  }
</script>

<template>
  <!-- <header class="page-head slider-menu-position">
    <nav class="rd-navbar rd-navbar-default rd-navbar-transparent" data-lg-auto-height="true" data-md-layout="rd-navbar-fixed" data-lg-layout="rd-navbar-static" data-lg-stick-up="true">
      <div class="rd-navbar-inner">
        
        <div class="rd-navbar-panel">
          
          <button class="rd-navbar-toggle" data-rd-navbar-toggle=".rd-navbar, .rd-navbar-nav-wrap"><span></span></button>
          
          <div class="rd-navbar-brand"><a href="index.html"><img style='margin-top: -5px;margin-left: -15px;' width='218' height='32' src='images/logo/Logo PSD V1 12-02-2023.png' alt=''/></a></div>
        </div>
        <div class="rd-navbar-menu-wrap">
          <div class="rd-navbar-nav-wrap">
            <div class="rd-navbar-mobile-scroll">
              !MOBILE!
              <div class="rd-navbar-mobile-brand"><a href="index.html"><img style='margin-top: -5px;margin-left: -15px;' width='218' height='32' src='images/logo/Logo PSD V1 12-02-2023.png' alt=''/></a></div>
              <div class="form-search-wrap">
                <form class="form-search" action="#" method="GET">
                  <div class="form-group">
                    <label class="form-label form-search-label form-label-sm" for="rd-navbar-form-search-widget">Search</label>
                    <input class="form-search-input input-sm form-control form-control-gray-lightest input-sm" id="rd-navbar-form-search-widget" type="text" name="s" autocomplete="off"/>
                  </div>
                  <button class="form-search-submit" type="submit"><span class="mdi mdi-magnify"></span></button>
                </form>
              </div>
              
              <ul class="rd-navbar-nav">
                <li><a href="index.html"><span>Home</span></a>
                </li>
                <li><a href="about.html"><span>About Us</span></a>
                </li>
                <li class="active"><a href="product.html"><span>Products</span></a>
                </li>
                <li><a href="contacts.html"><span>Contacts</span></a>
                </li>
              </ul>
            </div>
          </div>
          
          <div class="rd-navbar-search"><a class="rd-navbar-search-toggle mdi" data-rd-navbar-toggle=".rd-navbar-inner,.rd-navbar-search" href="#"><span></span></a>
            <form class="rd-navbar-search-form search-form-icon-right" action="#" method="GET">
              <div class="form-group">
                <label class="form-label" for="rd-navbar-search-form-input">Type and hit enter...</label>
                <input class="rd-navbar-search-form-input form-control form-control-gray-lightest" id="rd-navbar-search-form-input" type="text" name="s" autocomplete="off"/>
              </div>
            </form>
          </div>
        </div>
      </div>
    </nav>
  </header> -->

  <header class="page-head slider-menu-position">
    <nav class="navbar navbar-expand-lg navbar-dark" style="background-color: #110a06;">
      <a class="navbar-brand" href="/">
        <img src="@/assets/images/logo/logo-header.png" width="70" height="55" alt="">
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item" :class="{ 'active': home == 1 }">
            <a class="nav-link" href="/">Home</a>
          </li>
          <li class="nav-item" :class="{ 'active': about == 1 }">
            <a class="nav-link" href="/about">About</a>
          </li>
          <li class="nav-item" :class="{ 'active': product == 1 }">
            <a class="nav-link" href="/product">Product</a>
          </li>
          <li class="nav-item" :class="{ 'active': contact == 1 }">
            <a class="nav-link" href="/contact">Contact</a>
          </li>
        </ul>
      </div>
    </nav>
  </header>
</template>

<style scoped>

</style>