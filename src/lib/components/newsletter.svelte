<!-- Container for demo purpose -->
<div class="container mx-auto mt-24" id="newsletter">

  <!-- Section: Design Block -->
  <section class="mt-32 text-gray-800 image-cover bg-origin-border bg-clip-border" style="background-image: url('https://images.unsplash.com/photo-1491425432462-010715fd7ed7?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1566&q=80')">
    <style>
      .background-radial-gradient {
        background-color: hsl(218, 41%, 15%);
        background-image: radial-gradient(
            650px circle at 0% 0%,
            hsl(218, 41%, 35%) 15%,
            hsl(218, 41%, 30%) 35%,
            hsl(218, 41%, 20%) 75%,
            hsl(218, 41%, 19%) 80%,
            transparent 100%
          ),
          radial-gradient(
            1250px circle at 100% 100%,
            hsl(218, 41%, 45%) 15%,
            hsl(218, 41%, 30%) 35%,
            hsl(218, 41%, 20%) 75%,
            hsl(218, 41%, 19%) 80%,
            transparent 100%
          );
      }
    </style>

    <div class="px-6 py-12 text-center md:px-12 lg:text-left">
      <div class="container mx-auto xl:px-32">
        <div class="flex grid items-center gap-12 lg:grid-cols-2">
          <div class="mt-12 lg:mt-0">
            <h1
              class="mb-12 text-5xl font-bold tracking-tight md:text-6xl xl:text-5xl"
              style="color: hsl(218, 81%, 95%)"
            >
              Restez-informé<br /><span class="text-yellow-00">dès qu'il y a du nouveau</span>
            </h1>
            <p class="mb-4 text-white opacity-70 lead">
              Nous vous ecrirons que lorsque cela en vaut vraiment la peine.
            </p>
          </div>
          <div class="mb-12 lg:mb-0">
            <div class="block px-6 py-12 bg-white rounded-lg shadow-lg md:px-12">
              <h2 class="mb-12 text-3xl font-bold text-center">Inscrivez-vous à notre lettre d'information</h2>
              <form>
                <div class="mb-6 form-group">
                  <input
                    type="text"
                    class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-yellow-600 focus:outline-none"
                    id="exampleInput90"
                    placeholder="Prenom"
                  />
                </div>
                <div class="mb-6 form-group">
                  <input
                    type="email"
                    class="form-control block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-yellow-600 focus:outline-none"
                    id="exampleInput91"
                    placeholder="Adresse email"
                  />
                </div>
                <div class="mb-6 text-center form-group form-check">
                  <input
                    type="checkbox"
                    class="w-4 h-4 mt-1 mr-2 align-top transition duration-200 bg-white bg-center bg-no-repeat bg-contain border border-gray-300 rounded-sm appearance-none cursor-pointer form-check-input checked:bg-yellow-600 checked:border-yellow-600 focus:outline-none"
                    id="exampleCheck96"
                    checked
                  />
                  <label
                    class="inline-block text-gray-800 form-check-label"
                    for="exampleCheck96"
                    >J'accepte les conditions d'utilisation</label
                  >
                </div>
                <button
                  type="submit"
                  class="inline-flex items-center justify-center w-full px-4 py-2 text-base font-medium text-white bg-yellow-600 border border-transparent rounded-md shadow-sm whitespace-nowrap hover:bg-yellow-700"
                  data-mdb-ripple="true"
                  data-mdb-ripple-color="light"
                >
                  S'inscrire
                </button>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- Section: Design Block -->

</div>
<!-- Container for demo purpose -->