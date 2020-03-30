<template>
  <section class="hero is-info is-fullheight">
    <div class="hero-head">
      <nav class="navbar">
        <div class="container">
          <div class="navbar-brand">
            <div class="navbar-item">
              <img src="~/assets/panteon-logo.png" alt="Logo">
            </div>
          </div>
          <div id="navbarMenu" class="navbar-menu">
            <div class="navbar-end">
              <span class="navbar-item">
                <a class="button is-white is-outlined" target="blank" :href="phone">
                  <span class="icon">
                    <b-icon icon="phone" />
                  </span>
                  <span>Apeleazã acum</span>
                </a>
              </span>
              <span class="navbar-item">
                <a class="button is-white is-outlined" target="blank" :href="directions">
                  <span class="icon">
                    <b-icon icon="map" />
                  </span>
                  <span>Cum ajungem</span>
                </a>
              </span>
            </div>
          </div>
        </div>
      </nav>
    </div>

    <div class="hero-body">
      <div class="container has-text-centered">
        <div class="column is-8 is-offset-2">
          <h1 class="title">
            Materiale de construcții · Pal melaminat · Accesorii mobilã
          </h1>

          <h2 class="subtitle">
            Livrare gratuitã in Baia Mare și împrejurimi*

            <br>

            Prețuri negociabile.
          </h2>


        </div>

        <div class="column is-8 is-offset-2 pan-map">
          <p>* pentru comenzi de peste 200 RON</p>
          <br>

          <div>
            <a class="button is-white is-outlined" target="blank" :href="directions">
              <span class="icon">
                <b-icon icon="map-marker" />
              </span>
              <span>B-dul Bucuresti 49, Baia Mare</span>
            </a>
          </div>

          <div class="pan-map-map">
            <img src="~/assets/map-extra.png" alt="hartã">
          </div>

        </div>

        <div class="columns pan-materials">
          <card :title="materials.accesorii_mobilier.title" class="is-one-quarter-desktop is-full-mobile" :imageAlt="materials.accesorii_mobilier.title" :image="materials.accesorii_mobilier.image">
          </card>

          <card :title="materials.accesorii_sarpante.title" class="is-one-quarter-desktop is-full-mobile" :imageAlt="materials.accesorii_sarpante.title" :image="materials.accesorii_sarpante.image">
          </card>
          <card :title="materials.blaturi_de_bucatarie.title" class="is-one-quarter-desktop is-full-mobile" :imageAlt="materials.blaturi_de_bucatarie.title" :image="materials.blaturi_de_bucatarie.image">
          </card>
          <card :title="materials.boltari.title" class="is-one-quarter-desktop is-full-mobile" :imageAlt="materials.boltari.title" :image="materials.boltari.image">
          </card>
        </div>

        <div class="columns pan-materials">
          <card :title="materials.ciment.title" class="is-one-quarter-desktop is-full-mobile" :imageAlt="materials.ciment.title" :image="materials.ciment.image">
          </card>
          <card :title="materials.hidroizolatii.title" class="is-one-quarter-desktop is-full-mobile" :imageAlt="materials.hidroizolatii.title" :image="materials.hidroizolatii.image">
          </card>
          <card :title="materials.mortar.title" class="is-one-quarter-desktop is-full-mobile" :imageAlt="materials.mortar.title" :image="materials.mortar.image">
          </card>
          <card :title="materials.pal.title" class="is-one-quarter-desktop is-full-mobile" :imageAlt="materials.pal.title" :image="materials.pal.image">
          </card>
        </div>

        <div class="columns pan-materials">
          <card :title="materials.panouri_bordurate.title" class="is-one-quarter-desktop is-full-mobile" :imageAlt="materials.panouri_bordurate.title" :image="materials.panouri_bordurate.image">
          </card>
          <card :title="materials.plasa_gard.title" class="is-one-quarter-desktop is-full-mobile" :imageAlt="materials.plasa_gard.title" :image="materials.plasa_gard.image">
          </card>
          <card :title="materials.plasa_sudata.title" class="is-one-quarter-desktop is-full-mobile" :imageAlt="materials.plasa_sudata.title" :image="materials.plasa_sudata.image">
          </card>
          <card :title="materials.rigips.title" class="is-one-quarter-desktop is-full-mobile" :imageAlt="materials.rigips.title" :image="materials.rigips.image">
          </card>
        </div>

        <div class="columns pan-materials">
          <card :title="materials.samota.title" class="is-one-quarter-desktop is-full-mobile" :imageAlt="materials.samota.title" :image="materials.samota.image">
          </card>
          <card :title="materials.spalieri.title" class="is-one-quarter-desktop is-full-mobile" :imageAlt="materials.spalieri.title" :image="materials.spalieri.image">
          </card>
          <card :title="materials.termoizolatii.title" class="is-one-quarter-desktop is-full-mobile" :imageAlt="materials.termoizolatii.title" :image="materials.termoizolatii.image">
          </card>
          <card :title="materials.var.title" class="is-one-quarter-desktop is-full-mobile" :imageAlt="materials.var.title" :image="materials.var.image">
          </card>
        </div>

      </div>
    </div>

    <footer class="footer has-text-white">
      <div class="mb-100 has-text-centered content columns">
        <div class="column is-3 is-offset-2 is-size-3 footer-link">
          <b-icon icon="phone"/> <a target="blank" :href="phone">0722 682 913</a>
        </div>
        <div class="column is-4 is-size-3 footer-link">
          <b-icon icon="email"/> <a target="blank" :href="email">panteonaspect@gmail.com</a>
        </div>
      </div>

      <div class="content column is-4 is-offset-4">
        <table itemprop="openingHours">
          <tbody>
            <tr>
              <th class="has-text-white">luni:</th>
              <td>
                <span>08:00–17:00</span>
              </td>
            </tr>
            <tr>
              <th class="has-text-white">marti:</th>
              <td>
                <span>08:00–17:00</span>
              </td>
            </tr>
            <tr>
              <th class="has-text-white">miercuri:</th>
              <td>
                <span>08:00–17:00</span>
              </td>
            </tr>
            <tr>
              <th class="has-text-white">joi:</th>
              <td>
                <span>08:00–17:00</span>
              </td>
            </tr>
            <tr>
              <th class="has-text-white">vineri:</th>
              <td>
                <span>08:00–17:00</span>
              </td>
            </tr>
            <tr>
              <th class="has-text-white">sâmbata:</th>
              <td>
                <span>08:00–00:00</span>
              </td>
            </tr>
            <tr>
              <th class="has-text-white">duminica:</th>
              <td>
                <span>Închis</span></td>
            </tr>
          </tbody>
        </table>
      </div>
    </footer>

  </section>
</template>

<script>
  import Card from '~/components/Card';

  export default {
    data() {
      return {
        phone: 'tel:+40-722-682-913',
        directions: 'https://www.google.com/maps/dir//PANTEON+ASPECT+S.R.L./data=!4m8!4m7!1m0!1m5!1m1!1s0x4737dc30f981a2f1:0x8800b010d2639a61!2m2!1d23.5431383!2d47.6484495',
        map: 'https://www.google.com/maps/place/PANTEON+ASPECT+S.R.L./data=!3m1!4b1!4m2!3m1!1s0x4737dc30f981a2f1:0x8800b010d2639a61',
        email: 'mailto:panteonaspect@gmail.com',
        materials: {
          accesorii_mobilier: {
            title: 'Accesorii mobilier',
            image: 'material.accesorii_mobilier.jpg'
          },
          accesorii_sarpante: {
            title: 'Accesorii șarpante',
            image: 'material.accesorii_sarpante.jpg'
          },
          blaturi_de_bucatarie: {
            title: 'Blaturi de bucatarie',
            image: 'material.blaturi_de_bucatarie.jpg'
          },
          boltari: {
            title: 'Bolțari beton pentru zidărie, fundație',
            image: 'material.boltari.jpg'
          },
          ciment: {
            title: 'Ciment',
            image: 'material.ciment.jpg'
          },
          hidroizolatii: {
            title: 'Hidroizolații',
            image: 'material.hidroizolatii.jpg'
          },
          mortar: {
            title: 'Mortar',
            image: 'material.mortar.jpg'
          },
          pal: {
            title: 'Pal melaminat',
            image: 'material.pal.jpg'
          },
          panouri_bordurate: {
            title: 'Panouri bordurate',
            image: 'material.panouri_bordurate.jpg'
          },
          plasa_gard: {
            title: 'Plasă gard',
            image: 'material.plasa_gard.jpg'
          },
          plasa_sudata: {
            title: 'Plasă sudată',
            image: 'material.plasa_sudata.jpg'
          },
          rigips: {
            title: 'Rigips',
            image: 'material.rigips.jpg'
          },
          samota: {
            title: 'Șamotă, semișamotă',
            image: 'material.samota.jpg'
          },
          spalieri: {
            title: 'Spalieri',
            image: 'material.spalieri.jpg'
          },
          termoizolatii: {
            title: 'Termoizolații',
            image: 'material.termoizolatii.jpg'
          },
          var: {
            title: 'Var',
            image: 'material.var.jpg'
          }
        }
      }
    },
    components: {
      Card
    }
  }
</script>

<style>

  a {
    color: #d3d3d3;
  }

  .navbar-item img {
    max-height: 4.75rem;
  }

  .pan-map {
    margin-top: 100px;
  }

  .pan-map-map {
    margin-top: 50px;
  }

  .pan-materials {
    margin-top: 100px;
  }

  .footer {
    background-color: #0f0b09;
  }

  .footer > .footer-link {
    color: white;
  }

  .mb-100 {
    margin-bottom: 100px;
  }

</style>
