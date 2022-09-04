<script>
export let title
export let date
</script>

<article>
  <h1>{title}</h1>

  <p><strong>Publié le:</strong> {date}</p>

  <slot />
</article>