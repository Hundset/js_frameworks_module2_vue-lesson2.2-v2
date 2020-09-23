<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>

(function() {
    localStorage.setItem('username', 'Robin');
    localStorage.setItem('password', '9999')
})();

export default {
  name: 'app'
}
</script>
