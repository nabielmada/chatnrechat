<script>
export default {

}
</script>

<template>
  <section id = "intro" class = "container">
    <div class = "space-intro">
        <div class = "row">
            <div class = "col-6">
                <p class = "color-primary">CHAT N' RECHAT</p>
                <h1 class = "text-section-title">
                    Sebuah aplikasi chatting yang bisa bikin kamu lupa diri, tapi tidak lupa jasa pahlawan!
                </h1>
                <p class = "text-muted text-section-subtitle mt-4">
                    Sebenernya banyak banget aplikasi chatting yang lebih bagus dari ini, maka dari itu lebih baik pake yang lain aja deh ya daripada pake aplikasi yang ini.
                </p>

                <div class = "d-flex mt-4">
                    <div class = "me-3">
                        <button type = "button" class = "btn btn-lg btn-primary px-5 py-2 shadow-primary">
                            Register <i class = "bi bi-arrow-right-circle ms-2"></i>
                        </button>
                    </div>
                    <div>
                        <button type = "button" class = "btn btn-lg btn-light-primary px-5 py-2">
                            <span class = "color-primary">Learn More</span>
                        </button>
                    </div>
                </div>

                <div class = "row mt-5 pt-4">
                    <div class = "col-6">
                        <div class = "d-flex">
                            <div class = "me-3">
                                <i class = "bi bi-download h5"></i>
                            </div>
                            <div>
                                <div class = "text-muted">TOTAL PENDAPATAN</div>
                                <span class = "fs-3">1,501,234</span>
                            </div>
                        </div>
                    </div>
                    <div class = "col-6">
                        <div class = "d-flex">
                            <div class = "me-3">
                                <i class = "bi bi-person h4"></i>
                            </div>
                            <div>
                                <div class = "text-muted">TOTAL USERS</div>
                                <span class = "fs-3">1,318,829</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class = "col-6">
                <img src = "./../assets/images/bg/bg-intro.png" class = "img-fluid" loading="lazy" alt = "bg-intro" />
            </div>

            <section id = "partner" class = "mt-5 pt-5">
                <div class = "card bg-primary-light border-0">
                    <div class="card-body p-5">
                        <div class = "d-flex justify-content-evenly flex-row g-5">
                            <img src = "./../assets/images/partners/partner-cnn.png" alt = "partner-cnn" loading="lazy"/>
                            <img src = "./../assets/images/partners/partner-tirtoid.png" alt = "partner-tirtoid" loading="lazy"/>
                            <img src = "./../assets/images/partners/partner-forbes.png" alt = "partner-forbes" loading="lazy"/>
                            <img src = "./../assets/images/partners/partner-google.png" alt = "partner-google" loading="lazy"/>
                            <img src = "./../assets/images/partners/partner-nyt.png" alt = "partner-cnytnn" loading="lazy"/>
                        </div>
                    </div>
                </div>
            </section>
        </div>
    </div>
  </section>

  <section id = "features" class = "space container">
    <div class = "d-flex flex-column">
        <div class="row justify-content-center text-center align-items-center">
            <div class="col-12 col-md-7">
                <p>NGGAK HARUS SIH SEBENERNYA</p>
                <p class = "text-section-title">Kenapa Harus Pakai Chat N' Rechat?</p>
                <p class = "text-section-desc text-muted lh-lg">
                    Sebenernya yang bagus itu sih WhatsApp loh, mending pake WhatsApp aja deh. Yaudah berikut ini adalah fitur-fitur WhatsApp.
                </p>
            </div>
        </div>
    </div>

    <div class = "row mt-5 pt-4">
        <div class = "col-12 col-md-4">
            <div class = "d-flex flex-column justify-content-center align-items-center">
                <img src = "./../assets/images/bg/bg-features-1.png" class = "img-fluid" alt = "bg-features-1" loading = "lazy" />
                <p class = "subtitle pt-3">Groups to keep in touch</p>
                <p class = "text-section-desc text-muted text-center lh-lg">
                    Keep in touch with the groups of people that matter the most, like your family or coworkers. With group chats, you can share messages, photos, and videos.
                </p>
            </div>
        </div>
        <div class = "col-12 col-md-4">
            <div class = "d-flex flex-column justify-content-center align-items-center">
                <img src = "./../assets/images/bg/bg-features-2.png" class = "img-fluid" alt = "bg-features-2" loading = "lazy" />
                <p class = "subtitle pt-3">Simple, Reliable Messaging</p>
                <p class = "text-section-desc text-muted text-center lh-lg">
                    Message your friends and family for free*. WhatsApp uses your phone's Internet connection to send messages so you can avoid SMS fees.
                </p>
            </div>
        </div>
        <div class = "col-12 col-md-4">
            <div class = "d-flex flex-column justify-content-center align-items-center">
                <img src = "./../assets/images/bg/bg-features-3.png" class = "img-fluid" alt = "bg-features-3" loading = "lazy" />
                <p class = "subtitle pt-3">Speak Freely</p>
                <p class = "text-section-desc text-muted text-center lh-lg">
                    With voice calls, you can talk to your friends and family for free*, even if they're in another country. And with free* video calls, you can have face-to-face conversations.
                </p>
            </div>
        </div>
    </div>
  </section>

</template>

<style>

</style>