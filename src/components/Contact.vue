<template>
  <section>
      <div class="container">
            <div class="text-center mb-5">
                <h3 class="fw-bold">Contact details</h3>

                <p class="text-muted">Velit egestas dui id ornare arcu odio ut sem ultrices dui nemo bibendum rompa de Twitter</p>
            </div>

            <form class="w-75 mx-auto">
                <div class="mb-3">
                    <label for="name"></label>
                    <input class="form-control-input w-100 p-2" type="text" id="name" placeholder="Name">
                </div>

                <div class="mb-3">
                    <label for="email"></label>
                    <input class="form-control-input w-100 p-2" type="text" id="email" placeholder="Email">
                </div>

                <div class="mb-3">
                    <label for="message"></label>
                    <textarea class="form-control-input w-100 p-2" id="message" placeholder="Your message"></textarea>
                </div>

                <a href="#" class="btn btn-primary w-100 p-2">Submit Message</a>
            </form>
        </div>
  </section>
</template>

<style scoped>
section {
    background-image: url('/images/contact-envelope.svg');
    background-repeat: no-repeat;
    background-position: right;

    padding: 60px;
    margin-top: 6rem;
}

textarea {
    height: 220px;
}

h3 {
    color: #1b1e7b;
    font-weight: bold;
}
</style>