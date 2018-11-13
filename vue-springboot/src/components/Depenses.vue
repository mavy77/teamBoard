<template>

    <div id="app" class="container-fluid">
      <div class="site-info">
          <h1>DPENSES</h1>
      </div>

        <nav>
            <router-link class="btn btn-primary" to="/">Liste des dépenses</router-link>
            <router-link class="btn btn-primary" to="/add">Ajouter</router-link>
            <router-link class="btn btn-primary" to="/search">rechercher</router-link>
        </nav>
        <br/>
        <router-view/>
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
