<section class="hero">
  <div class="hero-inner">
    <h1>Welcome to the <span>OpenLab</span></h1>
    <h2>People-powered research</h2>
    <a href="/">See All projects</a>
  </div>
</section>

<style>
  .hero {
    padding: 5em 0;
    display: flex;
    justify-content: center;
    align-items: center;
    background-image: linear-gradient(rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0.9)),
      url("https://www.srgtalent.com/-/media/srg/1---new-website/final/blog/hero-images/black-research-scientist-looking-into-microscope.jpg");
    background-position: center;
    background-size: cover;
  }
  .hero-inner {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  .hero-inner > h1 {
    font-size: 2.5rem;
    margin-bottom: 5px;
  }
  .hero-inner > h2 {
    color: var(--gray);
    font-weight: 400;
    margin-bottom: 20px;
  }
  .hero-inner > h1 > span {
    font-weight: bold;
    background: -webkit-linear-gradient(45deg, #67cda8, #41b8d0);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
  }
  .hero-inner > a {
    border: 2px solid #41b8d0;
    padding: 10px 20px;
    border-radius: 10px;
    display: block;
    width: fit-content;
  }
</style>
