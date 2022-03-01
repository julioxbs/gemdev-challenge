<template>
  <nav class="p-3">
      <div class="container d-flex justify-content-between align-items-center">
          <a href="#" class="logo"><img src="/images/logo.svg" alt=""></a>

          <ul class="d-none d-md-flex gap-3 align-items-center m-0">
              <li v-for="{name, id} in links" :key="id">
                  <a href="#">{{name}}</a>
              </li>
              
              <li>
                  <a href="#"><i class="bi bi-twitter"></i></a>
              </li>

              <li>
                  <a href="#"><i class="bi bi-facebook"></i></a>
              </li>
          </ul>

          <a href="#" class="d-block d-md-none">
              <i class="fs-4 bi bi-list"></i>
          </a>
      </div>
  </nav>
</template>

<script>
export default {
    data() {
        return {
            links: [
                {name: 'Details', id: 1},
                {name: 'Features', id: 2},
                {name: 'About', id: 3},
                {name: 'Contact', id: 4},
            ]
        }
    }
}
</script>

<style scoped>
nav {
    background-color: #1b1e7b;
}

.logo img {
    width: 45%;
}

li {
    list-style: none;
}

a {
    text-decoration: none;
    color: #c5c3f0;
    font-size: 15px;
    font-weight: 400;
    transition: color .3s;
}

a:hover {
    color: #fff;
}
</style>