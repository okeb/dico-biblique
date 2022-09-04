<script>
export let data
</script>

<h1>The blog index</h1>

<p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Id, harum architecto minus tempore, ex consequuntur ipsam, mollitia repudiandae blanditiis ullam facilis a amet consequatur eius quis deserunt temporibus aut molestiae.</p>

<!-- <ul class="lg:px-12 <lg:px-8 list-none">
  {#each data.posts as post}
    {#if post.meta.published == true}
      <li>
        <h2>
          <a href={post.path} class="text-2xl">
            {post.meta.title}
          </a>
        </h2>
        Published {post.meta.date}
      </li>
    {/if}
  {/each}
</ul> -->

<!-- Container for demo purpose -->
<div class="container px-6 mx-auto my-24">

<!-- Section: Design Block -->
<section class="mb-32 text-center text-gray-800">
  {#each data.posts as post}
    {#if post.meta.published == true}
<div class="flex flex-wrap justify-center mb-12">
    <div class="w-full px-3 grow-0 shrink-0 basis-auto md:w-10/12">
      <div
        class="relative mb-6 overflow-hidden bg-no-repeat bg-cover rounded-lg shadow-lg ripple"
        data-mdb-ripple="true" data-mdb-ripple-color="light">
        <img src="https://mdbootstrap.com/img/new/slides/100.jpg" class="w-full" />
        <a href={post.path}>
          <div class="absolute top-0 bottom-0 left-0 right-0 w-full h-full overflow-hidden transition duration-300 ease-in-out bg-fixed opacity-0 hover:opacity-100"
            style="background-color: rgba(251, 251, 251, 0.15)"></div>
        </a>
      </div>
    </div>

    <div class="w-full px-3 grow-0 shrink-0 basis-auto md:w-8/12 xl:w-6/12">
      <h5 class="mb-3 text-lg font-bold">{post.meta.title}</h5>

      <p class="mb-4 text-gray-500">
        <small>Ecrit le <u>{post.meta.date}</u> par
          <a href="/contact" class="text-gray-900">Serviteur du Seigneur</a></small>
      </p>
      <p class="mb-6">
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Culpa
        atque hic, officiis blanditiis accusantium veritatis ullam?
        Maiores atque autem velit officiis molestiae voluptates suscipit
        eligendi, vero expedita sequi, doloremque modi?
      </p>
      <a data-mdb-ripple="true" data-mdb-ripple-color="light"
        class="inline-block px-6 py-2.5 bg-blue-600 text-white font-medium text-xs leading-tight uppercase rounded-full shadow-md hover:bg-blue-700 hover:shadow-lg focus:bg-blue-700 focus:shadow-lg focus:outline-none focus:ring-0 active:bg-blue-800 active:shadow-lg transition duration-150 ease-in-out"
        href={post.path} role="button">Lire la suite</a>
    </div>
  </div>
    {/if}
  {/each}
</section>
<!-- Section: Design Block -->

</div>
<!-- Container for demo purpose -->