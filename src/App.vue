<!-- <template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template> -->
<template>
    <nav id="navbarExample" class="navbar navbar-expand-lg fixed-top navbar-light" aria-label="Main navigation">
        <div class="container">
            <a class="navbar-brand logo-text" href="#"><img src="assets/images/Variant7.png" alt="logo"
                    class="logo-style"></a>
            <button class="navbar-toggler p-0 border-0" type="button" id="navbarSideCollapse"
                aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="navbar-collapse offcanvas-collapse" id="navbarsExampleDefault">
                <ul class="navbar-nav ms-auto navbar-nav-scroll">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#header">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#details">Benefit</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact</a>
                    </li>
                </ul>
                <span class="nav-item">
                    <a class="btn-solid-sm" href="https://forms.gle/czYbRBeC16jaEiZd9" target="_blank">Register</a>
                </span>
            </div>
        </div>
    </nav>
    <header id="header" class="header">
        <div class="container">
            <div class="row">
                <div class="col-lg-12 col-xl-12">
                    <div class="text-container">
                        <h1 class="h1-large">Just Before Forever</h1>
                        <p class="p-large">A 5-weeks hybrid counselling course for couples getting married within the
                            first half of 2023</p>
                        <a class="btn-solid-lg" href="https://forms.gle/czYbRBeC16jaEiZd9" target="_blank">Register
                            Now</a>
                        <h4 class="mt-4">Start: January 29, 2023 </h4>
                        <h4 class="mt-4">Fee- Affordable </h4>
                    </div>
                </div>
                <!-- <div class="col-lg-6 col-xl-7">
               <div class="image-container">
                   <img class="img-fluid" src="assets/images/header-image.png" alt="alternative" />
               </div> 
           </div>  -->
            </div>
        </div>
    </header>
    <div id="details" class="basic-1">
        <div class="container">
            <div class="row">
                <div class="col-lg-6 col-xl-7">
                    <div class="image-container">
                        <img class="img-fluid" src="assets/images/details-1.png" alt="alternative" />
                    </div>
                </div>
                <div class="col-lg-6 col-xl-5">
                    <div class="text-container">
                        <div class="section-title">WHAT TO EXPECT</div>
                        <h2>Expectations make you set for encounter</h2>
                        <p>Gain insight and knowledge regarding building godly marital foundations</p>
                        <a class="btn-solid-reg" href="https://forms.gle/czYbRBeC16jaEiZd9" target="_blank">Register</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="basic-2">
        <div class="container">
            <div class="row">
                <div class="col-lg-6 col-xl-5">
                    <div class="text-container">
                        <div class="section-title">PURPOSE OF THE COUNSELLING</div>
                        <h2>Are you prepared enough?</h2>
                        <p>A 5 week hybrid Christian counselling course for couples getting married within the first
                            half of 2023. </p>
                        <p>The Pre-marital counseling course aims to impact and create godly foundation for a beautiful
                            and fruitful marriage according to God's will and plan. It is also a great opportunity for
                            partners to break away from social norms and spend time rejuvenating and enriching their
                            courtship, just before marriage.
                            Our hope, and the goal of this course, is for you and your partner to learn, unlearn and
                            relearn how to navigate Godly principles of marriage here on earth.</p>
                    </div>
                </div>
                <div class="col-lg-6 col-xl-7">
                    <div class="image-container purpose-margin">
                        <img class="img-fluid" src="assets/images/purposeimage.jpg" alt="alternative" />
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="footer bg-gray" id="contact">
        <img class="decoration-circles" src="assets/images/decoration-circles.png" alt="alternative" />
        <div class="container">
            <div class="row">
                <div class="col-lg-12">
                    <h4>Purity Is Possible</h4>
                    <div class="social-container">
                        <span class="fa-stack">
                            <a href="https://www.facebook.com/purespeccommunity">
                                <i class="fas fa-circle fa-stack-2x"></i>
                                <i class="fab fa-facebook-f fa-stack-1x"></i>
                            </a>
                        </span>
                        <span class="fa-stack">
                            <a href="https://twitter.com/ThePureSpec">
                                <i class="fas fa-circle fa-stack-2x"></i>
                                <i class="fab fa-twitter fa-stack-1x"></i>
                            </a>
                        </span>
                        <span class="fa-stack">
                            <a href="https://www.linkedin.com/in/pure-spec-community-121360209">
                                <i class="fas fa-circle fa-stack-2x"></i>
                                <i class="fab fa-linkedin fa-stack-1x"></i>
                            </a>
                        </span>
                        <span class="fa-stack">
                            <a href="https://instagram.com/purespeccommunity">
                                <i class="fas fa-circle fa-stack-2x"></i>
                                <i class="fab fa-instagram fa-stack-1x"></i>
                            </a>
                        </span>
                        <span class="fa-stack">
                            <a href="https://t.me/purespeccommunity">
                                <i class="fas fa-circle fa-stack-2x"></i>
                                <i class="fab fa-telegram fa-stack-1x"></i>
                            </a>
                        </span>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <button id="myBtn">
        <img src="assets/images/up-arrow.png" alt="alternative" />
    </button>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
    name: 'App',
    // components: {
    //   HelloWorld
    // }
}
</script>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>
