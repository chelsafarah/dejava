<template>
    <div>
        <!-- Header -->
        <header>
            <div class="transbox d-flex flex-column px-5 flex-lg-row text-lg-start text-md-center">
                <div class="description me-lg-5 me-md-1">
                    <h1>
                        JASA TUGAS & PEMBUATAN SKRIPSI
                    </h1>
                    <p class="mt-3">
                        Buat yg lagi Butuh JASA SKRIPSI atau Bimbingan SKRIPSI dll Dengan Harga Terjangkau dengan Hasil yg Memuaskan. <br>
                        Silahkan order. Ga usah khawatir kami nenyediakan Jasa Bimbingan Skripsi dll.
                    </p>
                    <a href="#contact" class="btn btn-get-contact px-4 mt-4">
                        Hubungi Kami
                    </a>
                </div>
                <div>
                    <img class="img-ilustration" src="img/ilustration.png" alt="">
                </div>
                
            </div>
        </header>
    </div>
</template>
  
<script>
    export default {
        name: 'HeaderComponent',
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

    header{
        margin-top: -60px;
        padding-top: 100px;
        padding-bottom: 100px;
        background-color: antiquewhite;
    }

    .description {
        margin-top: 100px;
    }

    .img-ilustration {
        max-width: 400px;
    }
</style>