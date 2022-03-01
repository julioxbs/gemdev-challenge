<template>
  <section>
      <div class="container">
          <div class="counter d-md-flex text-center justify-content-center gap-5">
              <div class="cell" v-for="info in infos" :key="info.id">
                  <p class="p-0 m-0 fw-bold">{{info.numbers}}</p>
                  <span class="text-muted">{{info.text}}</span>
              </div>
          </div>
      </div>
  </section>
</template>

<script>
export default {
    data() {
        return {
            infos: [
                {numbers: 231, text: 'Nislo Velos'},
                {numbers: 385, text: 'Preum Lecso'},
                {numbers: 159, text: 'Sagit Orcis'},
                {numbers: 127, text: 'Purus Semper'},
                {numbers: 211, text: 'Aliqua Sempre'},
            ]
        }
    }
}
</script>

<style scoped>
p {
    font-size: 50px;
    color: #1b1e7b;
}

section {
    margin: 6rem 0;
}
</style>