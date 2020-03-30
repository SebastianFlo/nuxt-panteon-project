<template>
  <div class="column">
    <div class="card">
      <header class="card-header">
        <p class="card-header-title has-text-grey">
          {{ title }}
        </p>
      </header>
      <div class="card-content">
        <div class="content has-text-centered">
          <!-- <b-icon
            :icon="icon"
            size="is-large"
            type="is-primary"
          /> -->
          <img :src="imageUrl" :alt="imageAlt">
        </div>
      </div>
      <!-- <footer class="card-footer">
        <div class="card-footer-item">
          <span>
            <slot />
          </span>
        </div>
      </footer> -->
    </div>
  </div>
</template>

<script>
const images = require.context('~/assets/', false, /\.jpg$/)

export default {
  props: {
    title: {
      type: String,
      required: true
    },
    icon: {
      type: String,
      required: false
    },
    image: {
      type: String,
      required: true
    },
    imageAlt: {
      type: String,
      required: true
    }
  },
  computed: {
    imageUrl() {
      return images(`./${this.image}`);
    }
  }
}
</script>
