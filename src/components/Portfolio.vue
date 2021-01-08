<template>
    <section class="" id="portfolio">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading text-uppercase">Material sobre derechos animales</h2>
            <h3 class="section-subheading text-muted">Videos, talleres, textos, libros, folletos, banners y más!</h3>
          </div>
        </div>
        <div class="row">
          
            <div class="col-md-6 col-sm-6 portfolio-item" v-for="(obj, key) in portfolioJSON" :key="key">
                <a class="portfolio-link" target="_blank" :href="obj.url">
                    <div class="portfolio-hover">
                        <div class="portfolio-hover-content">
                            <i class="fas fa-plus fa-3x"></i>
                        </div>
                    </div>
                    <img class="img-fluid image-portfolio" style="width: 500px;
  height: 200px;" :src="obj.img" alt="">
                <div class="portfolio-caption">
                    <h4 style="color: black">{{ obj.caption }}</h4>
                </div>
                </a>
            </div>
        </div>
      </div>
    </section>
</template>

<script>
export default {
    data: () => ({
        portfolioJSON: [
            {
                img: 'https://images.indianexpress.com/2020/04/books_1200.jpg',
                caption: 'Libros, textos e informes',
                title: '',
                url: 'https://drive.google.com/drive/u/4/folders/1JN6na_t5fT-9T1Impk7JG5xIoMI64y_1'
            },
                        {
                img: 'https://i.ytimg.com/vi/dsaXyUKrpX0/maxresdefault.jpg',
                caption: 'Videos educativos sobre veganismo',
                title: 'Crytocurrency web',
                url: 'https://www.youtube.com/playlist?list=PLofVo5vsVeAC8wOLNQDb2kd1cdcyWRU8y'
            },
            {
                img: 'https://pbs.twimg.com/media/EBVIFl1XsAcRdTa.jpg',
                caption: 'Videos para formación de activistas',
                title: 'Weather app (Mobile for now)',
                url: 'https://www.youtube.com/playlist?list=PLofVo5vsVeABGoaz3FgU_iG5nmIAEow8W'
            },
            {
                img: 'https://i.ibb.co/bvsVS7G/folleto.png',
                caption: 'Material para activar (folletos, videos, banners)',
                title: 'Front End development for Frigo®',
                url: 'https://drive.google.com/drive/u/4/folders/1AMyS1KRoeixeJ3S0GkLPtAK8KDqWAB9O'
            }
        ]
    })
}
</script>

<style lang="css">

</style>


