<script>
  import FeaturedProjects from "./FeaturedProjects.svelte";
</script>

<section class="featured">
  <div class="featured-inner">
    <div class="row1">
      <h2>Featured Projects</h2>
    </div>
    <div class="row2">
      <FeaturedProjects />
      <FeaturedProjects />
      <FeaturedProjects />
    </div>
  </div>
</section>

<style>
  .featured-inner {
    max-width: var(--max-width);
    padding: 4em 0;
    margin: 0 auto;
  }
  .featured-inner > .row1 {
    display: flex;
    justify-content: center;
    margin-bottom: 1em;
  }
  .featured-inner > .row1 > h2 {
    font-size: 2.5rem;
  }
  .featured-inner > .row2 {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: center;
    text-align: center;
    gap: 1em;
  }
</style>
