<template>
      <div class="navbar-bg"></div>
      <nav class="navbar navbar-expand-lg main-navbar">
        <a href="index.html" class="navbar-brand sidebar-gone-hide">Accountability Report</a>
        <div class="navbar-nav">
          <a href="#" class="nav-link sidebar-gone-show" data-toggle="sidebar"><i class="fas fa-bars"></i></a>
        </div>
        <div class="nav-collapse">
          <a class="sidebar-gone-show nav-collapse-toggle nav-link" href="#">
            <i class="fas fa-ellipsis-v"></i>
          </a>
        </div>
      </nav>

      <nav class="navbar navbar-secondary navbar-expand-lg">
        <div class="container">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a href="#" class="nav-link"><i class="fas fa-fire"></i><span>Dashboard</span></a>
            </li>
            <li class="nav-item">
              <a href="#" class="nav-link"><i class="fa fa-users"></i><span>Giver</span></a>
            </li>
            <li class="nav-item">
              <a href="#" class="nav-link"><i class="fa fa-heart"></i><span>Receiver</span></a>
            </li>
          </ul>
        </div>
      </nav>
</template>

<script>
export default {
    name: 'Header',
}
</script>

<style scoped>

</style>