<section class="about">
  <div class="about-inner">
    <div class="col1">
      <h1>What is <span>OpenLab?</span></h1>
      <h2>
        The OpenLab enables everyone to take part in real cutting edge research in many fields
        across the sciences, humanities, and more. The OpenLab creates opportunities for you to
        unlock answers and contribute to real discoveries.
      </h2>
      <a href="#"
        >Checkout our works&nbsp;&nbsp;<i
          style="font-size: 1rem;"
          class="fa-solid fa-chevron-right"
        /></a
      >
    </div>
    <div class="col2">
      <img
        src="https://github.githubassets.com/images/modules/site/codespaces/illo-ports.png"
        alt="project-thumbnail"
      />
    </div>
  </div>
</section>

<style>
  .about {
    background-color: #000000;
    opacity: 1;
    background-image: repeating-radial-gradient(circle at 0 0, transparent 0, #000000 10px),
      repeating-linear-gradient(#22212855, #222128);
  }
  .about-inner {
    max-width: calc(var(--max-width) - 100px);
    padding: 4em 0;
    margin: 0 auto;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 2em;
  }
  .about-inner > .col1 {
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 1em;
  }
  .about-inner > .col1 > h1 > span {
    background: -webkit-linear-gradient(45deg, #67cda8, #41b8d0);
    background-clip: text;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
  }
  .about-inner > .col1 > h2 {
    font-size: 1rem;
    color: var(--gray);
  }
  .about-inner > .col1 > a {
    font-size: 1.4rem;
    font-weight: 600;
    background: -webkit-linear-gradient(45deg, #67cda8, #41b8d0);
    background-clip: text;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    width: fit-content;
    display: block;
    text-decoration: underline;
  }
  .about-inner > .col1 > a:hover {
    text-decoration: underline;
    color: white;
    background: none;
    -webkit-text-fill-color: white;
  }
  .about-inner > .col2 > img {
    width: 100%;
    border-radius: 5px;
    -webkit-transition: -webkit-transform 0.4s;
    transition: transform 0.4s;
  }
  .about-inner > .col2 > img:hover {
    transform: scale(1.02);
  }
</style>
