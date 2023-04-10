<script>
  import "../app.css";
</script>

<nav>
  <div class="nav-container">
    <a class="title" href="/">OpenLab</a>
    <ul class="nav-menu">
      <li><a href="/projects">Projects</a></li>
      <li><a href="/news">News</a></li>
      <li><a href="/about">About</a></li>
    </ul>
  </div>
</nav>

<slot />


<style>
  nav {
    width: 100%;
    height: 60px;
    background-color: var(--nav-bg);
  }
  .nav-container {
    height: inherit;
    padding: 0 1em;
    margin: 0 auto;
    max-width: var(--max-width);
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  .nav-container .title {
    font-weight: bold;
    font-size: 1.3rem;
    background: -webkit-linear-gradient(45deg, #67cda8, #41b8d0);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
  }
  .nav-container .nav-menu {
    display: flex;
    gap: 3em;
  }
  .nav-container .nav-menu li a {
    text-transform: uppercase;
    font-size: 0.75rem;
    letter-spacing: 2px;
    font-weight: 600;   
  }
  .nav-container .nav-menu li a:hover {
    text-decoration: underline;
  }
</style>