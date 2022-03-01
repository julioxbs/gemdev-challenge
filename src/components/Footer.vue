<template>
  <footer>
      <div class="container">
          <ul class="m-0 p-0 d-flex justify-content-center gap-3">
              <li><i class="bi bi-facebook"></i></li>
              <li><i class="bi bi-twitter"></i></li>
              <li><i class="bi bi-instagram"></i></li>
              <li><i class="bi bi-pinterest"></i></li>
              <li><i class="bi bi-youtube"></i></li>
          </ul>

          <p class="text-muted text-center mt-5">Copyright © <a href="#">Julioxbs</a></p>
      </div>
  </footer>
</template>

<script>
export default {

}
</script>

<style scoped>
footer {
    background: #f2f3fd;
    padding: 80px 0;
    margin-top: 6rem;
}

li {
    background: #fff;
    width: 40px;
    height: 40px;
    border-radius: 50%;
    position: relative;
    list-style: none;
    cursor: pointer;
    transition: all .3s ease;
}

i {
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
    font-size: 25px;
    color: #1b1e7b;
}

li:hover {
    background: #1b1e7b;
}

i:hover {
    color: #fff;
}
</style>