<template>
  <div>
    <a-layout-footer style="text-align: center" v-html="msg">
    </a-layout-footer>
  </div>
</template>

<script>
export default {
  name: 'Footer',
  data () {
    return {
      msg: 'Powered by VTDOCS. CopyRight &copy; 1999-2020 <a href="https://github.com/vt-dev-team">vt-dev-team</a>'
    }
  }
}
</script>
