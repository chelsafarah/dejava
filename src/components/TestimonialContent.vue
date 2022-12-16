<template>
    <div class="testimoni">
        <section class="section-testimonial-heading" id="testimonialHeading">
            <div class="container">
                <div class="row">
                    <div class="col text-center">
                        <h2>They Are Loving Us</h2>
                        <p>Moments were giving them <br>
                            the best experience </p>
                    </div>
                </div>
            </div>
        </section>

        <section class="section-testimonial-content" id="testimonialContent">
            <div class="container">
                <div class="section-popular-travel row justify-content-center">
                    <div class="col-sm-12 col-md-12 col-lg-4">
                        <div class="card card-testimonial text-center">
                            <div class="testimonial-content">
                                <h3 class="mb-1">Angga</h3>
                                <h6 class="mb-4">Manajemen</h6>
                                <p class="testimonial">
                                    “ It was glorious and I could not stop to say wohooo for every single momentDankeeeeee “
                                </p>
                            </div>
                        </div>
                    </div>
                    <div class="col-sm-12 col-md-12 col-lg-4">
                        <div class="card card-testimonial text-center">
                            <div class="testimonial-content">
                                <h3 class="mb-1">Shayna</h3>
                                <h6 class="mb-4">Teknik Informatika</h6>
                                <p class="testimonial">
                                    “ The trip was amazing and I saw something beautiful in that Island that makes me want to learn more “
                                </p>
                            </div>
                        </div>
                    </div>
                    <div class="col-sm-12 col-md-12 col-lg-4">
                        <div class="card card-testimonial text-center">
                            <div class="testimonial-content">
                                <h3 class="mb-1">Sabrina</h3>
                                <h6 class="mb-4">Matematika</h6>
                                <p class="testimonial">
                                    “I loved it when the waves was shaking harder — I was scared too”
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>
    
</template>

<script>

export default {
  name: 'TestimonialContent',
  components: {
    
  },
}
</script>

<style>
    .testimoni {
        padding-top: 50px;
        padding-bottom: 100px;
    }
    .quotation {
        font-size: 40px;
    }

    .card-testimonial {
        min-height: 200px;
        padding: 50px;
        border-radius: 200px;
        margin-bottom: 100px;
    }
    .card-testimonial:after {
        content:"";
        width:0px;
        height:0px;
        position:absolute;
        top:85%;
        right:36px;
        border-width:40px;
        border-style:solid;
        border-color:white transparent transparent white;
        display:block;
    }
</style>