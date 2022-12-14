<template>
    <div class="container">
        <section class="section-stats row justify-content-center" id="stats">
            <div class="col-4 col-md-2 stats-detail">
                <h2>200</h2>
                <p>Customers</p>
            </div>
            <div class="col-4 col-md-2 stats-detail">
                <h2>1000</h2>
                <p>Task Done</p>
            </div>
            <div class="col-4 col-md-2 stats-detail">
                <h2>75</h2>
                <p>Teams</p>
            </div>
        </section>
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
    .section-stats {
        margin-top: -50px;
    }
    .section-stats .stats-detail {
        padding-top: 15px;
        background-color: #fff;
        padding-left: 50px;
    }
    .section-stats h2 {
        font-size: 30px;
        margin-bottom: 0;
    }
    .section-stats p {
        font-size: 20px;
        font-weight: lighter;
    }
</style>