<template>
    <div class="container">
        <nav class="navbar sticky-top">
            <div class="container-fluid">
                <a class="navbar-brand" href="#">Dejavajoki</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarList" aria-controls="navbarList" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse " id="navbarList">
                    <ul class="navbar-nav ms-auto me-3 mb-2 mb-lg-0">
                        <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">Beranda</a>
                        </li>
                        <li class="nav-item">
                        <a class="nav-link" href="#">Testimoni</a>
                        </li>
                        <li class="nav-item">
                        <a class="nav-link">Cara Order</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </div>
</template>

<script>

export default {
  name: 'NavbarComponent',
  components: {
    
  },
}
</script>

<style>
    nav {
        background-color: #e3f2fd;
    }
</style>