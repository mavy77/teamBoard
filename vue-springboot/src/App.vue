<template>

    <div id="app" class="container-fluid">
      <div id = "navLeft" class="container-left" width ="25%">
        <h3>MENU</h3>
      </div>
      <div>
        <div class="site-info">
            <h1>MADINASTORES</h1>
            <h3>Tableau de bord</h3>
        </div>
        <nav>
            <router-link class="btn btn-primary" to="/">Customers</router-link>
            <router-link class="btn btn-primary" to="/add">Add</router-link>
            <router-link class="btn btn-primary" to="/search">Search</router-link>
        </nav>
        <br/>
        <router-view/>
      </div>
    </div>
</template>

<script>
export default {
  name: "app"
};
</script>

<style>
.site-info {
  color: green;
  margin-bottom: 20px;
}

.btn-primary {
  margin-right: 5px;
}

.container-left {
  text-align: left;
}

.container-fluid {
  text-align: center;
}
</style>
