<template>
<fixed-header>
  <nav class="desktop-nav animated" id="navbar">
            <div class="container-fluid">
            	<div class="row">
            		<div class="col-lg-3 col-md-3">
            			<a href="#" class="logo">
            				<Logo />
            			</a>
                        <a href="" class="hiring-link">Dev</a>
            		</div>
            		<div class="col-lg-6 col-md-6">
            			<ul class="nav">
		                    <li class="nav-item children">
		                    	<a class="nav-link" href="">Integrations <i class="fas fa-caret-down"></i></a>
		                    	<ul class="sub-menu">
									<div class="media">
										<div class="media-left">
											<img src="https://djmmlc8gcwtqv.cloudfront.net/imgs/global/logos/channels-logo.svg" class="img-fluid" alt="channels-logo">
										</div>
										<div class="media-body">
											<a href=""><p class="submenu-heding">Analytics</p></a>
											<a href=""><p class="submenu-pg">Tag Managers for complete marketing</p></a>
											<a href=""><p class="submenu-features">Features <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16"><path fill="#1E7FFF" d="M 8 0L 6.59 1.41L 12.17 7L 0 7L 0 9L 12.17 9L 6.59 14.59L 8 16L 16 8L 8 0Z"></path></svg></p></a>
											<a href=""><p class="submenu-pricing">Pricing <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16"><path fill="#1E7FFF" d="M 8 0L 6.59 1.41L 12.17 7L 0 7L 0 9L 12.17 9L 6.59 14.59L 8 16L 16 8L 8 0Z"></path></svg></p></a>
										</div>
									</div>
									<div class="media mt-4">
										<div class="media-left">
											<img src="https://djmmlc8gcwtqv.cloudfront.net/imgs/global/logos/beams-logo.svg" class="img-fluid" alt="channels-logo">
										</div>
										<div class="media-body">
											<a href=""><p class="submenu-heding">PHP</p></a>
											<a href=""><p class="submenu-pg">Powerful Web Apps</p></a>
											<a href=""><p class="submenu-features">Pricing <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16"><path fill="#1E7FFF" d="M 8 0L 6.59 1.41L 12.17 7L 0 7L 0 9L 12.17 9L 6.59 14.59L 8 16L 16 8L 8 0Z"></path></svg></p></a>
										</div>
									</div>
									<div class="media mt-4">
										<div class="media-left">
											<img src="https://djmmlc8gcwtqv.cloudfront.net/imgs/global/logos/chatkit-logo.svg" class="img-fluid" alt="channels-logo">
										</div>
										<div class="media-body">
											<a href=""><p class="submenu-heding">JavaScript</p></a>
											<a href=""><p class="submenu-pg">Build powerful client side experiences </p></a>
											<a href=""><p class="submenu-features">Pricing <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16"><path fill="#1E7FFF" d="M 8 0L 6.59 1.41L 12.17 7L 0 7L 0 9L 12.17 9L 6.59 14.59L 8 16L 16 8L 8 0Z"></path></svg></p></a>
										</div>
									</div>
								</ul>
		                    </li>
		                    <li class="nav-item children">
		                    	<a class="nav-link" href="">Clients <i class="fas fa-caret-down"></i></a>
		                    	<ul class="sub-menu sub-menu-two">
									<a href="#"><p class="submenu-heding">Process</p></a>
									<a href="#"><p class="submenu-pg">Read the docs to learn how we make your product</p></a>
									<a href="#"><p class="submenu-features">Analytics <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16"><path fill="#1E7FFF" d="M 8 0L 6.59 1.41L 12.17 7L 0 7L 0 9L 12.17 9L 6.59 14.59L 8 16L 16 8L 8 0Z"></path></svg></p></a>
									<a href=""><p class="submenu-pricing">PHP <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16"><path fill="#1E7FFF" d="M 8 0L 6.59 1.41L 12.17 7L 0 7L 0 9L 12.17 9L 6.59 14.59L 8 16L 16 8L 8 0Z"></path></svg></p></a>
									<a href=""><p class="submenu-pricing">JavaScript <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16"><path fill="#1E7FFF" d="M 8 0L 6.59 1.41L 12.17 7L 0 7L 0 9L 12.17 9L 6.59 14.59L 8 16L 16 8L 8 0Z"></path></svg></p></a>
									<a href="#"><p class="submenu-heding mt-4">Tutorials</p></a>
									<a href="#"><p class="submenu-pg">Explore my tutorials</p></a>
									<a href="#"><p class="submenu-heding mt-4">Support</p></a>
									<a href="#"><p class="submenu-pg">Reach out to our support team</p></a>
									<a href="#"><p class="submenu-heding mt-4">Status</p></a>
									<a href="#"><p class="submenu-pg">Check on the status of any of our products</p></a>
								</ul>
		                    </li>
		                    <li class="nav-item children">
		                    	<a class="nav-link" href="">Company <i class="fas fa-caret-down"></i></a>
		                    	<ul class="sub-menu sub-menu-three">
									<a href="#"><p class="submenu-heding">Careers</p></a>
									<a href="#"><p class="submenu-pg">Look at my available jobs and join us on our mission</p></a>
									<a href="#"><p class="submenu-heding mt-5">Joe Blog</p></a>
									<a href="#"><p class="submenu-pg">Read my updates and opinions on technology</p></a>
								</ul>
		                    </li>
		                </ul>
            		</div>

            		<div class="col-lg-3 col-md-3 nav-buttons">
            			<a href="#" class="btn btn-signin">Sign In</a>&nbsp;&nbsp;
            			<a href="#" class="btn btn-signup">Sign Up</a>
            		</div>
            	</div>
            </div>
        </nav>
</fixed-header>
</template>

<script>
import Logo from '~/components/Logo'
import FixedHeader from 'vue-fixed-header'

export default {
  components: {
    Logo,
    FixedHeader
  }
}
</script>
<style>
#navbar.vue-fixed-header--isFixed {
  position: fixed;
  left: 0;
  top: 0;
  width: 100vw;
  z-index: 10000;
}
</style>