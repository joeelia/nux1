<template>
	<div lang="en">
		<header>
		<meta charset="utf-8">
  		<meta name="viewport" content="width=device-width, initial-scale=1.0">
  			<TopBar />
  			<DesktopNav />
  			<MobileNav />
  		</header>
   		<nuxt/>
   		<Footer />
	</div>
</template>
<script>
import DesktopNav from '~/components/DesktopNav'
import MobileNav from '~/components/MobileNav'
import TopBar from '~/components/TopBar'
import Footer from '~/components/Footer'
export default {
 components: {
    DesktopNav,
    MobileNav,
    TopBar,
    Footer
  },
  mounted(){
	
  }
}
</script>
<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}
.navbar.vue-fixed-header--isFixed {
  position: fixed;
  left: 0;
  top: 0;
  width: 100vw;
}
.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}
</style>