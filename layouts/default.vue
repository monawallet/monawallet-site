<template>
  <div>
  <header>
  <Header />
  </header>
  <nuxt />
  <footer class="footer">
  <Footer />
  </footer>
  </div>
</template>

<script>
import Header from '~/components/Header.vue'
import Footer from '~/components/Footer.vue'
export default {
  name: 'navbar',
  components: {
    Header,
    Footer
  }
}
</script>

<style>
@import url(http://fonts.googleapis.com/css?family=Raleway);

html, body {
    margin: 0;
}
.terms, .privacy {
    padding-top: 3.25rem;
}
.navbar {
    padding: 10px;
    padding-right: 20px;
    background: linear-gradient(90deg,#ff8f8b 2%,#ffce69);
    width: 100%;
}

.navbar-item {
    color: #fff;
    font-weight: bold;
}
.navbar-menu {
    background: rgba(0,0,0,0);
}
.navbar-burger {
    color: #fff;
    font-weight: bold;
}

@media screen and (min-width: 700px) {
    #splash > div {
        display: table-cell;
        vertical-align: middle;
        padding: 1em 0em;
        height: 85vh;
    }
    #splash #left {
        text-align: left;
    }
    #splash #right {
        text-align: left;
    }
    #splash .iphone {
        width: 288px;
        height: 576px;
    }
    #screenshots img {
        max-width: 200px;
    }
    #description-mobile {
        display: none;
    }
}
@media screen and (max-width: 700px) {
    #splash .iphone {
        width: 192px;
        height: 384px;
        display: inline-block;
    }
    #splash #left{
        padding : 30px 10px;
    }
    #screenshots img {
        max-width: 100px;
    }
    #description {
        display: none;
    }
    #description-mobile {
        margin: auto;
        max-width: 600px;
        padding: 10px;
    }
    #appstore {
        text-align: left;
    }
}
img.appstore {
    max-width: 120px;
}
.iphone {
    background-size: contain;
    position: relative;
    width: 720px;
    height: 1440px;
}
.iphone img {
    position: absolute;
    top: 17.9%;
    left: 14%;
    width: 73%;
}
h1, h2, h3, h4, h5, h6 {
    font-family: "Raleway", sans-serif;
    font-weight: normal;
}
#screenshots {
    margin-bottom: 2em;
}
#screenshots img {
    border: 1px solid white;
    box-shadow: 0px 0px 2px rgba(0,0,0,0.5);
    margin: 1em;
}

.footer {
    left: 0px;
    bottom: 0px;
    width: 100vw;
    height: 130px;
    background-color: #A3463F;
    color: #d5dae0;
    text-align: center;
    padding-top: 36px;
}
.footer .fab {
    margin: 0 10px;
}
.fab {
    color:#fff
}
.fa-envelope {
    font-size: 1.6em;
}
.columns ul {
    margin: 0;
    width: 95vw;
}
</style>