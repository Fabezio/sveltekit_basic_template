<script>
const author = "Fabezio"
const project = "sveltekit_basic_template"
</script>

<footer>
    <div>visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to learn SvelteKit</div>
    <div><a href="https://github.com/{author}/{project}" target="_blank" >code source </a></div>
    <div>Développé avec <a href="https://svelte.dev" target="_blank" >svelte </a></div>
</footer>

<style lang="scss" >


footer {
  perspective: 100;
  position: fixed;
  bottom: 0;
  width: 100%;

  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  align-items: center;
  height: 3em;
  border-top: 1px solid deepbluesky;
  a {
    font-weight: bold;
    color: orangered;
  }
}


@media (min-width: 480px) {
  footer {
    height: 3em;

  }
}
</style>
