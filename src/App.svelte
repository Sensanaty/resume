<main>
  <div class="wrapper">
    <div class="header">
      <h1 class="name">Luka Salević<span class="link">lu-ka.me</span></h1>
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
          <h3>Senior Frontend Engineer <span>Dec 2022 - Present</span></h3>
        </div>
        <div class="company-details">
          <ul>
            <li>
              Part of the team with the most critical user-facing role of the entire application, the Inbox, where my team and I shipped huge refactors of the legacy codebase, modernizing it and ensuring that it's much easier to modify and add new features to in the future.
            </li>

            <li>
              Refactored many data-fetching components to utilize a proper store system, which involved large scale reworks of many fragile interconnected parts of the codebase. This ultimately resulted in a much better dev experience due to the increased level of organization and the newly introduced unit tests, as well as major speed & efficiency gains in the application itself for our users.
            </li>

            <li>
              Additionally, I was heavily involved in a large cross-team effort to create an entirely new suite of tools related to 3rd party integrations such as Hubspot, Salesforce and other related 3rd parties. Starting from scratch, we worked our way up with wholly new components and refactors to older sections of the codebase.
            </li>

            <li>
              Participated in a large cross-team effort to elevate the quality of our homebrewed UIKit, both in terms of the usefulness and reusability of the components within it, as well as the testability and longevity of the components. Involved the creation of many new components as well as redesigns of older ones.
            </li>

            <li>
              Headed a long-term effort to upgrade our Vue version from 2 to 3, while getting rid of as many dependencies as possible in the meantime. I was also a very vocal advocate for improving upon the general DX of the whole codebase, from simple things like automated linting on-commit to ensuring that our test coverage was sufficient and scalable for future work.
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
              My team and I were responsible for the construction of a brand new, large featureset involving lots of data gathering and analytical capabilities, that would eventually be ported over for all universities on the platform. It involved the creation of many new complex components and in some situations refactors of existing components on the frontend, while the backend also required new functionality with a lot of room for error due to a slew of complex SQL queries.
            </li>

            <li>
              Responsible for the integration and testing of all new features into various LMS platforms like Canvas, BlackBoard, Microsoft Teams and others. This involved writing extensive Unit, acceptance and integration tests on both the frontend and backend as well as manual testing of the various APIs involved in the LMS'.
            </li>

            <li>
              I was deeply involved in the code review process for many pull requests made for both the backend and the frontend of the platform. I ensured that all code being delivered was adhering to a high standard, especially making sure that accessibility concerns were accounted for due to the nature of the userbase (universities and their students).
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
            Part of a large effort where we modernized and cleaned up some of the messier parts of the Vue codebase that relied on brittle 3rd parties, ensuring the young project would remain scalable and easy to work on.
          </li>

          <li>
            Facilitated a large refactor of the Rails backend to cater to delivery services, a crucial feature during the peak of the COVID pandemic where many people couldn't go out to eat, which was a large factor in ensuring the continued and successful growth of the product.
          </li>
        </ul>
      </div>
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
