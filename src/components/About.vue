<template>
  <div class="about">
    <h1>Hello {{ given_name }}, this is the {{ name }} page</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna ali...</p>
  </div>
</template>

<script>
export default {
  name: 'About',
  given_name: 'Duncan',
  data () {
    return {
          given_name: this.$route.params.name
    }
  }
}
</script>