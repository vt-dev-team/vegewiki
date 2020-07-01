<template>
  <div>
      <a-menu
        theme="dark"
        mode="horizontal"
        :default-selected-keys="['2']"
        :style="{ lineHeight: '64px' }"
      >
        <a-menu-item key="1">
          vtdocs
        </a-menu-item>
        <a-menu-item key="2">
          nav 2
        </a-menu-item>
        <a-menu-item key="3">
          nav 3
        </a-menu-item>
      </a-menu>
  </div>
</template>

<script>
export default {
  name: 'Nav',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
      current: ['mail'],
      openKeys: ['sub1']
    }
  }
}
</script>
