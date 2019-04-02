<template>
        <nav class="mobile-nav">
        	<div class="container-fluid">
        		<div class="clear-fix">
        			<div class="float-left">
        				<a href="#" class="logo">
            				<Logo />
            			</a>
                        <a href="" class="hiring-link">Dev</a>
        			</div>
        			<div class="float-right">
        				<div class="site-nav" :class="{ 'site-nav--open': showMobileMenu }">
        					<h5>Products</h5>
        					<div class="primary-area">
        						<div class="media">
        							<div class="media-left">
        								<img src="https://djmmlc8gcwtqv.cloudfront.net/imgs/global/logos/channels-logo.svg" class="img-fluid">
        							</div>
        							<div class="media-body">
        								<a href="#"><p>Analytics</p></a>
        							</div>
        						</div>
        						<div class="media">
        							<div class="media-left">
        								<img src="https://djmmlc8gcwtqv.cloudfront.net/imgs/global/logos/beams-logo.svg" class="img-fluid">
        							</div>
        							<div class="media-body">
        								<a href="#"><p>PHP</p></a>
        							</div>
        						</div>
        						<div class="media">
        							<div class="media-left">
        								<img src="https://djmmlc8gcwtqv.cloudfront.net/imgs/global/logos/chatkit-logo.svg" class="img-fluid">
        							</div>
        							<div class="media-body">
        								<a href="#"><p>JavaScript</p></a>
        							</div>
        						</div>
        					</div>
        					<div class="secondary-area">
        						<div class="row lists">
        							<a href="#">Docs</a>
        							<a href="#">Tutorials</a>
        							<a href="#">Support</a>
        							<a href="#">Careers</a>
        							<a href="#">Joe Blog</a>
        						</div>
        						<div class="buttons mt-2">
        							<a href="#" class="btn btn-signin">Sign In</a>&nbsp;&nbsp;
            						<a href="#" class="btn btn-signup">Sign Up</a>
        						</div>
        					</div>
        				</div>
        				<div class="menu-toggle" :class="{ 'open': showMobileMenu }" @click="showMobileMenu = !showMobileMenu">
						    <div class="hamburger"></div>
						</div>
        			</div>
        		</div>
        	</div>
        </nav>
</template>

<script>
import Logo from '~/components/Logo'
export default {
  components: {
    Logo
  },
  data: function () {
  	return {
    	showMobileMenu: false
     }
  },
  methods: {
  	menuToggle(){
  	}
  }
}
</script>
