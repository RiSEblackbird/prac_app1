<script>
  import Header from 'packs/components/header.vue'
  import Footer from 'packs/components/footer.vue'

  export default {
    name: 'MyApp',
    props: {
      msg: String
    },
    components: {
      Header, Footer
    }
  }
</script>

<style lang="scss">
</style>
