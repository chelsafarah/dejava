<template>
    <div>
        <!-- Header -->
        <header>
            <div class="transbox d-flex flex-column px-5 flex-lg-row text-lg-start text-md-center">
                <div class="description me-lg-5 me-md-1">
                    <h1 class="title anim-typewriter">
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

    .title{
        position: relative; 
        width: 18em;
        border-right: 2px solid rgba(255,255,255,.75);
        font-size: 180%;
        white-space: nowrap;
        overflow: hidden; 
    }
    
    /* Animation */
    .anim-typewriter{
    animation: typewriter 4s steps(30) 1s 1 normal both,
                blinkTextCursor 500ms steps(30) infinite normal;
    }
    @keyframes typewriter{
        from{width: 0;}
        to{width: 18em;}
    }
    @keyframes blinkTextCursor{
        from{border-right-color: rgba(255,255,255,.75);}
        to{border-right-color: transparent;}
    }
</style>