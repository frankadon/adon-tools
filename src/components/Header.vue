<template>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
        <a class="navbar-brand" href="#">
            AdOn Group
            <!-- <img src="../assets/AOG-logo_black.png" alt="" width="50"> -->
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
            <li class="nav-item">
            <a class="nav-link active" aria-current="page">
                <router-link to="/">Home</router-link>
            </a>
            </li>
            <li class="nav-item">
            <a class="nav-link">
                <router-link to="/about">About</router-link>
            </a>
            </li>
            <li class="nav-item">
            <a class="nav-link" href="#">Pricing</a>
            </li>
            <li class="nav-item">
            <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
            </li>
        </ul>
        </div>
    </div>
    </nav>
</template>

<script>
export default {

}
</script>

<style scoped>
a {
    text-decoration: none;
    color: #222;
}
a.router-link-exact-active {
  color: #42b983;
  font-weight: bold;
}
</style>