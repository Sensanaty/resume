<main>
  <div class="wrapper">
    <div class="header">
      <h1 class="name">Luka Salević<span class="link">lu-ka.me</span></h1>
      <h2 class="description">Fullstack Web & Software Engineer</h2>
    </div>

    <div class="details">
      <a href="mailto:salevic@lu-ka.me"><code>salevic@lu-ka.me</code></a>
      <span class="spacer"></span>
      <a href="https://github.com/Sensanaty"><code>github.com/Sensanaty</code></a>
      <span class="spacer"></span>
      <code>+31 612 632 764</code>
    </div>

    <div class="skills">
      <h2>Skills</h2>

      <div class="wrapper">
        <ul class="left">
          <li>TypeScript, HTML, CSS, Tailwind</li>
          <li>Vue and Nuxt 2 & 3, Svelte, React, Lit, Ember</li>
          <li>Docker & Docker Compose, Kubernetes</li>
          <li>Cloudflare, Google Cloud, AWS, Vercel, Azure</li>
          <li>PostgreSQL, Redis, MySQL, GraphQL, Mongo</li>
          <li>LangSmith, self-hosted LLMs (Llama 3)</li>
        </ul>

        <ul class="right">
          <li>Ruby & Rails, Golang, Python, Learning Rust</li>
          <li>Linux (UNIX), Git, Mercurial, SVN</li>
          <li>Vitest, testing-library, Jest, Cypress, Playwright</li>
          <li>Pinia, VueX, Jotai, Zustand, TanStack Query</li>
          <li>Figma, Miro, Framer, Lottie</li>
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
              As part of the automation team, led the frontend development of a greenfield AI automation feature. The AI directly interacted with deeper, critical systems of the project, being allowed to act autonomously, which meant a lot of care was taken to ensure high quality workflows.
            </li>

            <li>
              I also often helped the backend engineers on the automation team with the Node (Nest.js) codebase of the greenfield AI project, as the bulk of the work there involved backend work. In collaboration with our Infra team, we put out a fully-functional MVP of the project in less than a month.
            </li>

            <li>
              As part of the Inbox team, we were responsible for the most critical part of the entire application, the Inbox. My team and I modernized huge swathes of the legacy, untested  Inbox codebase, ensuring greater testability, extensibility and getting rid of many long-standing bugs in the platform which were slowly increasing our churn rate.
            </li>

            <li>
              During my time in Inbox, we also built a massive new feature that involved over 20 different 3rd party CRM and Ecommerce platform integrations via their APIs to great success, seeing adoption with almost every Trengo customer.
            </li>

            <li>
              Stepped into a PM role during a health emergency with our own PM. Conducted dozens of customer interviews, communicated with key stakeholders and kept them up-to-date while shielding the team from growing pressure, organized several sprints, sprint reviews & refinements and handled other various PM tasks.
            </li>

            <li>
              Championed a cross-team effort to upgrade our legacy Vue application from version 2.6 to the latest 3 version, while getting rid of as many dependencies as possible in the meantime. I was also a very vocal advocate for improving upon the general DX of the whole codebase, from simple things like automated linting on-commit to ensuring that our test coverage was sufficient and scalable for future work.
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
              Led the creation of a complex featureset for long-term data gathering and visualization, ultimately used by all universities on the platform. This involved building new components, refactoring existing ones on the frontend, and adding new backend functionality involving large, expansive SQL queries, making sure they were optimized for the large datasets involved.
            </li>

            <li>
              Integrated and testing of features for LMS platforms like Canvas, BlackBoard, Microsoft Teams. Wrote extensive unit, acceptance, snapshot and integration tests, primarily with Playwright, Cypress & RSpec.
            </li>

            <li>
              Played a central role in code reviews for both backend and frontend pull requests. Ensured high standards and addressed accessibility concerns, given the userbase consisted of universities and their students.
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

  a {
    color: inherit;
    text-decoration: none;
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
