<div class="featured-projects">
  <a href="#">
    <img
      src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSFA84Gk3MJPYRozNi6zdjfOsb1esx-JMf5XwXbzIyVFUd_BDeNDztxOKBn1EIC-B7HkUU&usqp=CAU"
      alt="earth"
    />
  </a>
  <a href="#">
    <h1 class="project-title">Research about Earth</h1>
  </a>
  <p>It is a research about earth</p>
</div>

<style>
  .featured-projects {
    display: flex;
    flex-direction: column;
    gap: 0.3em;
    padding: 1em;
  }
  .featured-projects > a > img {
    margin-bottom: 0.5em;
    border-radius: 5px;
    -webkit-transition: -webkit-transform 0.4s;
    transition: transform 0.4s;
  }
  .featured-projects > a > img:hover {
    transform: scale(1.02);
  }
  .featured-projects > p {
    font-size: 0.9rem;
    color: var(--gray);
  }
  .project-title {
    font-size: 1.2rem;
  }
</style>
