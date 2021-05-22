<template>
    <div>
        <!-- Navigation-->
        <nav class="navbar navbar-expand-lg navbar-light fixed-top shadow-sm" id="mainNav">
            <div class="container px-5">
                <a class="navbar-brand nav-logo " style="color: #7CC3CD;" href="#page-top">SugoiFit Financials</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
                    Menu
                    <i class="bi-list"></i>
                </button>
                <div class="collapse navbar-collapse" id="navbarResponsive">
                    <ul class="navbar-nav ms-auto me-4 my-3 my-lg-0">
                        <li class="nav-item"><a class="nav-link me-lg-3" href="#features"> All Features</a></li>
                        <li class="nav-item"><a class="nav-link me-lg-3" href="#accounting"> Accounting</a></li>
                    
                        <li class="nav-item"><a class="nav-link me-lg-3" href="#website"> Marketing Website</a></li>

                        <li class="nav-item"><a class="nav-link me-lg-3" href="#team">About Developers</a></li>
                    </ul>
                    <button class="btn  rounded-pill px-3 mb-2 mb-lg-0" style= "background-colour: #428B95;" data-bs-toggle="modal" data-bs-target="#feedbackModal">
                        <span class="d-flex align-items-center">
                            <i class="bi-chat-text-fill me-2"></i>
                            <span class="small">Contact Us</span>
                        </span>
                    </button>
                </div>
            </div>
        </nav>
        <!-- Mashead header-->
        <header id="page-top" class="masthead">
            <div class="container px-5 ">
                <div class="row gx-5 mb-4 align-items-center">
                    <div class="col-lg-5">
                        <!-- Mashead text and app badges-->
                        <div class="mb-5 mb-lg-0 text-center text-lg-start" >
                            <h1 class="display-4 lh-1 mb-3" style="margin-top: 8rem;">SugoiFit, <br>a perfect fit for you.</h1>
                            <p class="lead fw-normal text-muted mb-5"> A central home for all your small business needs. We make running your business easier. </p>
                            <button class="btn btn-lg sign-btn">Sign up Now</button>
                          
                        </div>
                    </div>
                   <div class="col-lg-6 ">
                        <img class="mr-3" src="../assets/img/macbook.png" alt="" style="width: 740px; height: 480px;">
                        </div>
                    </div>
                </div>
            
        </header>
        <!-- Quote/testimonial aside-->
        <aside class="text-center bg-gradient-primary-to-secondary">
            <div class="container px-5">
                <div class="row gx-5 justify-content-center">
                    <div class="col-xl-8">
                        <div class="h2 fs-1 text-white mb-4">"An intuitive solution to a common problem that entrepreneurs face, wrapped up in a single web app!"</div>
                        <!-- <img src="assets/img/tnw-logo.svg" alt="..." style="height: 3rem" /> -->
                    </div>
                </div>
            </div>
        </aside>
        <!-- App features section-->
        <section id="features" class="d-flex flex-column align-items-center">
            <div class="container align-self-center justify-content-center " style="margin-left: 3rem;">
                <div class="row d-flex flex-row  align-items-center justify-content-center">
                    <div class="col-lg-10 d-flex flex-column align-self-center justify-content-center  mb-5 mb-lg-0  ">
                        <div class="container-fluid px-5">
                            
                            <div class="d-flex flex-row justify-content-center ">
                                <div class="col-md-4  mb-5 ">
                                    <!-- Feature item-->
                                    <div class="text-center  w-75 ">
                                        <i class="bi-at icon-feature text-gradient d-block mb-3"></i>
                                        <h3 class="font-alt">Personal Marketing Website</h3>
                                        <p class="text-muted mb-0"> Customize your website and start accepting orders today. </p>
                                    </div>
                                </div>
                                <div class="col-md-4 mb-5">
                                    <!-- Feature item-->
                                    <div class="text-center w-75">
                                        <i class="bi-cash-stack icon-feature text-gradient d-block mb-3"></i>
                                        <h3 class="font-alt">Accounting and Finance</h3>
                                        <p class="text-muted mb-0">Let us be your accountant! 
                                            One click away from your automated Financial Statements. </p>
                                    </div>
                                </div>
                                 <div class="col-md-4 mb-5 ">
                                    <!-- Feature item-->
                                    <div class="text-center w-75">
                                        <i class="bi-graph-up icon-feature text-gradient d-block mb-3"></i>
                                        <h3 class="font-alt">Reports</h3>
                                        <p class="text-muted mb-0">
                                            Get simple, easy to read reports on demand.
                                            Know which products are worth advancing!
                                            </p>
                                    </div>
                                </div>
                            </div>
                          
                            <div class="row">
                                <div class="col-md-4 mb-5 mb-md-0">
                                    <!-- Feature item-->
                                    <div class="text-center w-75">
                                        <i class="bi-receipt-cutoff icon-feature text-gradient d-block mb-3"></i>
                                        <h3 class="font-alt">Sales Management</h3>
                                        <p class="text-muted mb-0">Stay organize with our order tagging system. </p>
                                    </div>
                                </div>
                                <div class="col-md-4 mb-5 ">
                                    <!-- Feature item-->
                                    <div class="text-center w-75">
                                        <i class="bi-archive-fill icon-feature text-gradient d-block mb-3"></i>
                                        <h3 class="font-alt">Manage your inventory</h3>
                                        <p class="text-muted mb-0">Never run out of a product ever again. Easily keep track of your inventory
                                           with targeted alerts.</p>
                                    </div>
                                </div>
                                  <div class="col-md-4 mb-5">
                                    <!-- Feature item-->
                                    <div class="text-center w-75">
                                        <i class="bi-journal-text icon-feature text-gradient d-block mb-3"></i>
                                        <h3 class="font-alt">Invoices</h3>
                                        <p class="text-muted mb-0">SugoiFit manages your invoices for you ! We securely save your invoices for
                                            retreival at your convenience.</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-4 order-lg-0">
                        <!-- Features section device mockup-->
                        
                    </div>
                </div>
            </div>
        </section>
        <!-- Basic features section-->
        <section id="accounting" class="bg-light">
            <div class="container px-5">
                <div class="row gx-5 align-items-center justify-content-center justify-content-lg-between">
                    <div class="col-12 col-lg-5">
                        <h2 class="display-5 lh-1 mb-4">A new way of conducting business.</h2>
                        <p class="lead fw-normal text-muted mb-5 mb-lg-0">
                            No exerience with accounting? 
                            
                            We provide an easy way to manage your transactions and generate your financial statements.
                           </p>
                    </div>
                    <div class="col-sm-8 col-md-7">
                        <div class="px-5 px-sm-0"><img class="img-fluid" src="../assets/img/transaction.png" style="width: 800px; height: 420px;" alt="..." /></div>
                        
                    </div>
                </div>
            </div>
        </section>
        <!-- Call to action section-->
        <section id="website" class="cta " style="height: 45rem;">
            <img class="shadow-lg" src="../assets/img/website.png" style="z-index: 2; position: absolute; top: -30px; width: 40rem; height: 50rem;" alt="">
            <div class="cta-content d-flex flex-row align-items-center ">
                
                <div class="container d-flex flex-column  align-items-end justify-self-center px-5 cust-trans" style="margin-top: 10rem;">
                    <div>
                            <h2 class="text-black display-3 h-1  d-flex flex-row align-items-center" style="color: #0c353f">
                       Get your customizable <br> marketing website.
                                   
                      
                    </h2>
                    <p class="web-p" style="">  Easy way for customers to view your catalog <br>
                        and place an order which goes directly into the system.        </p>
                    </div>
                    
                    <!-- <a class="btn btn-outline-light py-3 px-4 rounded-pill d-flex flex-column align-items-start" href="https://startbootstrap.com/theme/new-age" target="_blank">Download for free</a> -->
                </div>
            </div>
        </section>
        <!-- Team Members -->
        <section id="team" class="bg-light">
            <div class="container px-5">
                <div class=" d-flex flex-row align-items-center justify-content-center ">
                    <div class="col-lg-10">
                        <teams></teams>
                    </div>
                     
                    
                </div>
            </div>
        </section>
        <!-- App badge section-->
        <section class="bg-gradient-primary-to-secondary" id="about">
            <div class="container px-5">
               
                    <h2 class="text-center text-white font-alt mb-4">Sign up now and Follow our social media pages for updates!</h2>
                    <div class="d-flex flex-column flex-lg-row align-items-center justify-content-center">
                        <!-- <a class="me-lg-3 mb-4 mb-lg-0" href="#!"><img class="app-badge" src="assets/img/google-play-badge.svg" alt="..." /></a>
                        <a class="me-lg-3 mb-4 mb-lg-0" href="#!"><img class="app-badge" src="assets/img/app-store-badge.svg" alt="..." /></a> -->
                        <a class="me-lg-3 mb-4 mb-lg-0" href="https://www.instagram.com/sugoifit/"><img class="app-badge" src="../assets/img/instagram-logo1.png" alt="Instagram" /></a>
                        <a href="https://twitter.com/sugoifit"><img class="app-badge" src="../assets/img/twitter_PNG1.png" alt="Twitter" /></a>
                    </div>
            </div>
        </section>
        <!-- Footer-->
        <footer class="bg-black text-center py-5">
            <div class="container px-5">
                <div class="text-white-50 small">
                    <div class="mb-2">&copy; SugoiFit Financials 2021. All Rights Reserved.</div>
                    <a href="#!">Privacy</a>
                    <span class="mx-1">&middot;</span>
        
                    <a href="#!">FAQ</a>
                </div>
            </div>
        </footer>

        <!-- Feedback modal-->
        <div class="modal fade" id="feedbackModal" tabindex="-1" aria-labelledby="feedbackModalLabel" aria-hidden="true">
            <div class="modal-dialog modal-dialog-centered">
                <div class="modal-content">
                    <div class="modal-header bg-gradient-primary-to-secondary p-4">
                        <h5 class="modal-title font-alt text-white" id="feedbackModalLabel">Send feedback</h5>
                        <button class="btn-close btn-close-white" type="button" data-bs-dismiss="modal" aria-label="Close"></button>
                    </div>
                    <div class="modal-body border-0 p-4">
                        <form>
                            <div class="form-floating mb-4">
                                <input class="form-control" id="inputName" type="text" placeholder="Enter your name..." />
                                <label for="inputName">Name</label>
                            </div>
                            <div class="form-floating mb-4">
                                <input class="form-control" id="inputEmail" type="email" placeholder="name@example.com" />
                                <label for="inputEmail">Email address</label>
                            </div>
                            <div class="form-floating mb-4">
                                <input class="form-control" id="inputPhone" type="tel" placeholder="(123) 456-7890" />
                                <label for="inputPhone">Phone number</label>
                            </div>
                            <div class="form-floating mb-4">
                                <textarea class="form-control" id="inputMessage" placeholder="Enter your message here..." style="height: 10rem"></textarea>
                                <label for="inputMessage">Message</label>
                            </div>
                            <div class="d-grid"><button class="btn btn-primary rounded-pill py-3" type="submit">Submit</button></div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>
    
</template>

<script>
import teams from './teams.vue'
export default {
  components: { teams },
    name: 'Home'
}
</script>