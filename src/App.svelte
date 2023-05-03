<main>
  <div class="wrapper">
    <div class="header">
      <h1 class="name">Luka Salevic<span class="link">lu-ka.me</span></h1>
      <h2 class="description">Fullstack Web & Software Engineer</h2>
    </div>

    <div class="details">
      <code>salevic@lu-ka.me</code>
      <span class="spacer"></span>
      <code>github.com/Sensanaty</code>
      <span class="spacer"></span>
      <code>+31 612 632 764</code>
    </div>

    <div class="skills">
      <h2>Skills</h2>

      <div class="wrapper">
        <ul class="left">
          <li>JavaScript (ES6) & TypeScript, CSS, Tailwind</li>
          <li>Vue 2 & 3, Nuxt, Ember.js, React, Svelte</li>
          <li>Docker & Docker Compose, Kubernetes</li>
          <li>Google Cloud, Heroku, AWS, Vercel, Azure</li>
          <li>PostgreSQL, Redis, MySQL, GraphQL, Mongo</li>
          <li>AGILE & SCRUM methodologies</li>
        </ul>

        <ul class="right">
          <li>Ruby & Ruby on Rails, Python & Django</li>
          <li>Git, Mercurial, SVN</li>
          <li>TTD & Continuous Delivery and Integration</li>
          <li>Linux (Ubuntu, Debian, Fedora, Alpine) & MacOS</li>
          <li>Illustrator, Figma, Sketch, Photoshop</li>
          <li>SEO, Web Design & UX, Accessibility & i18n</li>
        </ul>
      </div>
    </div>

    <div class="experience">
      <h2>Experience</h2>

      <div class="company">
        <div class="position">
          <h2>Trengo</h2>
          <h3>Frontend Engineer <span>Dec 2022 - Present</span></h3>
        </div>
        <div class="company-details">
          <ul>
            <li>
              I was part of the team with arguably the most critical customer-facing role of the entire application, where myself and 3 other devs collaborated closely in order to ship huge refactors of the legacy codebase, in order to modernize it and ensure that it's much easier going forward to modify and add new features to it.
            </li>

            <li>
              Additionally, my team and I collaborated on a large, cross-team effort to create a large new project based around 3rd party application integrations, starting from scratch and working our way up with wholly new components and refactors of older sections where necessary.
            </li>

            <li>
              Participated in a large cross-team effort to elevate the quality of our homebrewed UIKit, both in terms of the usefulness and reusability of the components within it, as well as the testability and longevity of the components.
            </li>

            <li>
              I was a very vocal advocate for improving upon the DX of the whole codebase, collaborating very closely with the senior devs to clean up and organize the older, more legacy sections of the project.
            </li>
          </ul>
        </div>
      </div>

      <div class="company">
        <div class="position">
          <h2>FeedbackFruits</h2>
          <h3>Fullstack Engineer <span>Dec 2021 - Dec 2022</span></h3>
        </div>

        <div class="company-details">
          <ul>
            <li>
              My team and I were responsible for the construction of a brand new, large featureset from scratch for one of our client universities, that would eventually be ported over for all universities on the platform. It involved the creation of many new complex components and in some situations refactors of existing components on the frontend, while the backend also required new functionality with a lot of room for error due to a slew of complex SQL queries.
            </li>

            <li>
              Responsible for the integration and testing of all new features into various LMS platforms like Canvas, BlackBoard, Microsoft Teams and others. This involves writing extensive Unit, acceptance and integration tests on both the frontend and backend as well as manual testing of the various APIs involved in the LMS'.
            </li>

            <li>
              I was deeply involved in the code review process for many pull requests made for both the backend and the frontend of the platform. I ensured that all code being delivered was adhering to a high standard, especially making sure that accessibility concerns were accounted for due to the nature of the userbase (universities and their students).
            </li>

            <li>
              Outside of major projects, I was also involved in delivering small, but crucial quality of life improvements for the platform, such as searchbars, table sorting and various other similar things. I also created a number of smaller components and features that ended up being used by pretty much anyone using the platform - both internally as well as externally.
            </li>
          </ul>
        </div>
      </div>

      <div class="company">
        <div class="position">
          <h2>Tablevibe</h2>
          <h3>Fullstack Engineer <span>Aug 2020 - Dec 2021</span></h3>
        </div>
      </div>

      <div class="company-details">
        <ul>
          <li>
            I was part of a large effort where we modernized and cleaned up some of the messier parts of the Vue codebase that relied on brittle 3rd parties, ensuring the young project would remain scalable and easy to work on for any potential newcomers.
          </li>

          <li>
            Facilitated a large refactor of the Rails backend that smoothly aided delivery services rather than only in-restaurant dining experiences, a crucial feature during the peak of the COVID pandemic where many people couldn't go out to eat, which was a large factor in ensuring the continued and successful growth of the product.
          </li>
        </ul>
      </div>
    </div>
</main>

<style>
  :global(html, body, #app) {
    background: #1E1E1E;
    width: 100%;
    height: 100%;
  }
  :global(#app) {
    display: flex;
    justify-content: center;
    align-items: center;
  }
  main {
    height: 297mm;
    width: 210mm;
    background: white;
    padding: 9px 10px;
    font-family: Aeonik;
  }
  h1, h2, h3, h4, h5, ul, li, p, code, pre { margin: 0; padding: 0}

  .name {
    font-size: 2.0rem;
  }
  .link {
    color: dimgray;
    font-family: "Hack Nerd Font Mono";
    font-size: 1.5rem;
    margin-left: 15px
  }
  .link::before {
    content: "// ";
    font-family: "Helvetica Now Display"
  }

  .details {
    font-size: 1.05rem;
    display: flex;
    justify-content: space-around;
    align-items: center;
    width: calc(100% + 20px);
    background: black;
    color: white;
    padding: 10px;
    margin: 6px -10px 2px -10px ;
  }
  code {
    font-family: "Hack Nerd Font Mono";
    font-weight: bold;
  }
  .spacer {
    height: 25px;
    width: 6px;
    background: white;
    margin: -20px;
  }

  .skills {
    width: 100%;
    padding: 4px;
  }
  .skills > .wrapper {
    display: flex;
    flex-flow: row wrap;
    justify-content: center;
    align-items: center;
  }
  h2 {
    margin-bottom: 5px;
  }
  .skills > .wrapper > ul {
    margin-left: 10px;
    width: calc(50% - 10px);
    justify-self: flex-start;
  }
  .skills > .wrapper > ul > li {
    font-size: 1.08rem;
    margin: 1px 0;
  }

  .experience > h2 { margin: 4px 0 7px 0; font-size: 1.5rem }
  h3 { font-size: 1.4rem; font-weight: normal }
  .position {
    display: inline-flex;
    align-items: center;
    flex-flow: row wrap;
  }

  .position > h2 { font-size: 1.5rem }
  .position > h2::after { content: " -"; margin-right: 8px }
  .position > h3 { font-size: 1.5rem }
  h3 > span { color: dimgray; font-weight: bold; font-family: "Hack Nerd Font Mono"; font-size: 1rem; margin-left: 4px; }
  h3 > span::before { content: "//"; font-family: "Helvetica Now Display"; margin-right: 6px; }
  .company-details > p { margin: 8px 0 }
  .company-details > ul { margin-left: 10px }
  .company-details > ul > li { margin: 6px 0 }
  .company-details > ul > li:nth-child(1) { margin: 2px 0 6px 0 }
</style>
