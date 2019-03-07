<template>
  <div >
    <!-- == START OF MENU 07 (large desktop header--07 is hidden on mobiles (iPhone, iPad, etc) and this one is to be opened on burger tap) ==-->
    <nav data-menu-index="07" class="menu menu--07 js-menu">
      <div class="menu__container">
        <button type="button" class="menu__closer js-close-menu">close</button>
        <div class="menu__box">
          <ul class="menu__list">
            <li class="menu__item"><a href="#" class="menu__link">About</a></li>
            <li class="menu__item"><a href="#" class="menu__link">Team</a></li>
            <li class="menu__item"><a href="#" class="menu__link">Pricing</a></li>
            <li class="menu__item"><a href="#" class="menu__link">Press</a></li>
            <li class="menu__item"><a href="#" class="menu__link">Contact</a></li>
          </ul><a href="#" class="button button--white button--gray-shadow">sign up</a>
        </div>
      </div>
    </nav>
    <div class="cover cover--10">
      <!-- == START OF HEADER 07 ==-->
      <nav class="header header--07">
        <div class="container header__container">
          <div class="header__left_box"><a href="#" title="Home" class="header__logo_box"><img src="../img/etc/logo--circle--black.svg" alt="Phoenix UI kit logo" class="header__logo_img"></a></div>
          <div class="header__center_box">
            <ul class="header__menu_list header__item--desktop">
              <li class="header__menu_item"><a href="#" class="header__menu_link">about</a></li>
              <li class="header__menu_item"><a href="#" class="header__menu_link">tour</a></li>
              <li class="header__menu_item"><a href="#" class="header__menu_link">pricing</a></li>
              <li class="header__menu_item"><a href="#" class="header__menu_link">blog</a></li>
              <li class="header__menu_item"><a href="#" class="header__menu_link">contact</a></li>
            </ul>
          </div>
          <div class="header__right_box"><a href="#" class="button button--white button--gray-shadow header__item--desktop">sign up</a>
            <button type="button" data-menu-index="07" class="header__burger_button header__burger_button--black js-open-menu header__item--mobile"></button>
          </div>
        </div>
      </nav>
      <!-- == END OF HEADER 07 ==-->
      <div class="container">
        <div class="cover__content_box">
          <h2 class="cover__title cover__title--10"><span class="cover__title_text cover__title_text--10">Start Your Imaginations</span></h2>
          <div class="cover__image_box--10">
            <div class="cover__button_box--10">
              <button data-popup-target="video" type="button" class="cover__button--10 button button--blue button--blue-shadow button--round button--play-icon js-open-popup"></button>
            </div><img src="img/pictures/pic--keyboard-image.png" class="cover__image">
          </div>
        </div>
        <div class="cover__features_box">
          <div class="row">
            <div class="col-xs-12 col-md-6 col-lg-3 cover__features__item--10">
              <h3 class="cover__feature_title">Ready to use</h3><span class="cover__feature_text">Phoenix works perfect in all modern browsers (Chrome, Safari, Firefox etc).</span>
            </div>
            <div class="col-xs-12 col-md-6 col-lg-3 cover__features__item--10">
              <h3 class="cover__feature_title">Clean design</h3><span class="cover__feature_text">A combination of the unique layout and material design best practices is what the Phoenix loved for.</span>
            </div>
            <div class="col-xs-12 col-md-6 col-lg-3 cover__features__item--10">
              <h3 class="cover__feature_title">bootstrap based</h3><span class="cover__feature_text">Most popular 1170px grid and all the Bootstrap components are at your service.</span>
            </div>
            <div class="col-xs-12 col-md-6 col-lg-3 cover__features__item--10">
              <h3 class="cover__feature_title">unique icons</h3><span class="cover__feature_text">Phoenix is an SVG based instrument, meaning all icons  are sharp and look awesome everywhere.</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
