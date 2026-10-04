<p align="center">
  <img src="https://raw.githubusercontent.com/mypageaudit/.github/main/profile/avatar.png" width="112" height="112" alt="MyPageAudit logo">
</p>

<h1 align="center">Welcome to MyPageAudit</h1>

<p align="center"><strong>Find it. Understand it. Improve it.</strong></p>

<p align="center">
  Website audits that help you understand what needs attention—and what to do next.
</p>

<p align="center">
  <a href="#what-you-can-do-today">Explore the product</a> ·
  <a href="#find-your-way-around">Explore the repositories</a> ·
  <a href="#where-were-headed">Our direction</a>
</p>

## Why we're building MyPageAudit

A website audit should give you more than a score. It should show you the problem, the evidence behind it, and a practical next step.

MyPageAudit helps developers, freelancers, website owners, and small agencies review their sites and prioritize SEO improvements. Our goal is to make the journey from finding an issue to checking a fix easier to follow.

**Inspect → Understand → Prioritize → Fix → Verify**

## What you can do today

- **Explore a website:** crawl discoverable pages through internal HTML links and sitemaps, or inspect a single page.
- **Understand each page:** review 32 checks across page metadata, technical SEO, mobile declarations, headings, images, and structured data—with evidence and recommendations.
- **Inspect images without a wall of thumbnails:** see image counts and open a source location when you want to view an image.
- **Keep your work organized:** save projects and their latest successful audit summaries in your account.
- **Work in your preferred appearance:** switch between Light, Dark, and System immediately.

Crawls respect robots.txt and show their coverage and limits. They currently inspect fetched HTML, with a default limit of 500 pages or 10 minutes; pages available only through JavaScript or sign-in are outside that coverage. Audit scores describe the checks performed, rather than predicting search rankings.

## Find your way around

Each repository has a focused job and its own documentation. Some repositories are private; their links are available to members with access.

| Repository                                                              | What's inside                                                            | Start here if you want to…               |
| ----------------------------------------------------------------------- | ------------------------------------------------------------------------ | ---------------------------------------- |
| [audit-client](https://github.com/mypageaudit/audit-client)             | The web interface, page results, image locations, projects, and settings | Work on the frontend and user experience |
| [audit-server](https://github.com/mypageaudit/audit-server)             | The API, site-audit requests, accounts, and data storage                 | Work on backend behavior                 |
| [audit-core](https://github.com/mypageaudit/audit-core)                 | The crawler, SEO checks, evidence models, and scoring                    | Understand or improve the audit engine   |
| [safe-web-probe](https://github.com/mypageaudit/safe-web-probe)         | Bounded public-web fetching and redirect validation                      | Work on how websites are fetched         |
| [structured-logging](https://github.com/mypageaudit/structured-logging) | Reusable JSON logging helpers                                            | Work on application logging              |
| [infra](https://github.com/mypageaudit/infra)                           | Deployment configuration, monitoring, and backups                        | Run and maintain the application         |
| [acceptance-tests](https://github.com/mypageaudit/acceptance-tests)     | Browser checks across desktop and mobile                                 | Check that the product works together    |
| [organization](https://github.com/mypageaudit/organization)             | Product direction, branding, roadmap, and release coordination           | Follow or plan product work              |
| [.github](https://github.com/mypageaudit/.github)                       | This profile and shared contribution, issue, and pull-request guides     | Understand how we collaborate            |

To run the application locally, start with the READMEs in **audit-client** and **audit-server**.

## Where we're headed

We want MyPageAudit to become a dependable way to keep websites healthy over time, especially for teams looking after several sites.

Our next areas of exploration are recurring audits, saved history and comparisons, regression alerts, clearer fix priorities, and useful client reports. Team workflows and integrations are longer-term goals. These are planned capabilities, not features available today.

## Have an idea or found a problem?

We'd like to understand the task you were trying to complete and what would make it easier.

- For a bug, open an issue in the relevant repository with the page or workflow, steps to reproduce, and what you expected.
- For a product idea or work spanning several repositories, start in [organization](https://github.com/mypageaudit/organization/issues).
- For a code change, read our [contribution guide](https://github.com/mypageaudit/.github/blob/main/CONTRIBUTING.md).
- For a sensitive security concern, follow our [security reporting guide](https://github.com/mypageaudit/.github/blob/main/SECURITY.md).

Thanks for helping make website audits clearer and more useful.
