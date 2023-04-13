<section class="discussion">
  <div class="discussion-inner">
    <div class="col1">
      <h3>
        <b>OpenLab Discussions</b> create space to ask questions and have open-ended conversations.
      </h3>
      <a href="#"
        >Explore OpenLab Discussions&nbsp;&nbsp;<i
          class="fa-solid fa-chevron-right"
          style="font-size: .8rem;"
        /></a
      >
      <img
        src="https://github.githubassets.com/images/modules/site/home-campaign/illu-discussions.png?width=966&format=webpll"
        alt="placeholder2"
      />
    </div>
    <div class="col2">
      <h3>
        <b>OpenLab Request</b> allow real-time communication and collaboration about project changes.
      </h3>
      <a href="#"
        >Explore OpenLab Request&nbsp;&nbsp;<i
          class="fa-solid fa-chevron-right"
          style="font-size: .8rem;"
        /></a
      >
      <img
        src="https://github.githubassets.com/images/modules/site/home-campaign/illu-discussions.png?width=966&format=webpll"
        alt="placeholder2"
      />
    </div>
  </div>
</section>

<style>
  .discussion-inner {
    max-width: var(--max-width);
    padding: 4em 0;
    margin: 0 auto;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 2em;
  }
  .discussion-inner > * {
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 1em;
    padding: 2em 2em 0 2em;
    background: rgba(64, 64, 64, 0.25);
    backdrop-filter: blur(4px);
    -webkit-backdrop-filter: blur(4px);
    box-shadow: rgba(99, 99, 99, 0.2) 0px 2px 8px 0px;
    border-radius: 10px;
    border: 1px solid rgba(255, 255, 255, 0.18);
    transition: 0.2s;
  }
  .discussion-inner > *:hover {
    scale: 1.01;
  }
  .discussion-inner > * > h3 {
    font-weight: 400;
    font-size: 1rem;
  }
  .discussion-inner > * > img {
    border-radius: 10px;
    padding-top: 1em;
    width: 100%;
  }
  .discussion-inner > * > a {
    font-size: 1rem;
    font-weight: 600;
    background: -webkit-linear-gradient(45deg, #67cda8, #41b8d0);
    background-clip: text;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    width: fit-content;
    display: block;
    text-decoration: underline;
  }
  .discussion-inner > * > a:hover {
    text-decoration: underline;
    color: white;
    background: none;
    -webkit-text-fill-color: white;
  }
</style>
