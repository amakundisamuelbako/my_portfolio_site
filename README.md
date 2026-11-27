![Site checks](https://github.com/amakundisamuelbako/my_portfolio-site/actions/workflows/site.yml/badge.svg)
**Portfolio Site Documentation**

_About Me_
I'm a full-stack engineer building and shipping production-ready systems with Python, and DevOps

_Status_
In development

_Project Commencement_
The portfolio site project started on 24th November, 2026.
At about 11:41AM (WAT) at my Friends residence.

_Overview_
This project 'My Portfolio Site' is built as a knowledge and expertise proof of my
role as a full-stack engineer. Recruiters, clients and collaborators can access this
site to check up my information, projects, tech stacks etc

The scope of this project first version is to design a simple single page site with limited features/section such as Home, About, Skills, Projects, and contact. The main goal of the site is to design and build a a site which is fast to load, mobile-first, accessible and easy to update.

The initial design scope of the project does not include features such as blog, CMS, authentication to the site.

_Tech Stack_
The following technologically tools will be used to develop the site.
**Markup** | HTML5
**Styling** | CSS
**Behavior** | JavaScript
**Contact form** |
**Hosting** | GitHub Pages
**CI/CD** | GitHub Actions
**Domain/DNS** |

_Project Structure_
Project Scaffolding
portfolio

- .github/
  -workflows/
  -deploy.yml
  src/
  - index.hmtl
  - css/
    - styles.css
  - js/
    - main.js
  - assets/ - images/ - icons/ - resume.pdf
    docs/
  - user-story.md
  - sitemap.md
  - wireframes/

tests/
.gitignore
.editorconfig
package.json
LICENSE
README.md

_Getting Started_
**Prerequistes**
Git, A code editor

_Development Workflow_
Each phase of the project is recorded as follows with dates and decisions.
**Phase 1**: Planning (user story, sitemap, content list)

**Phase 2**: Design (Wireframes, colour palettee, typography, mobile-first layout)

**Phase 3**: Project Setup (repo, folder structure, tooling, first commit)

**Phase 4**: Build (header/nav, hero, about, skills, projects, contact, footer)

**Phase 5**: Responsiveness and accessibility

**Phase 6**: Performance and SEO

**Phase 7**: Testing

**Phase 8**: Deployment

**Phase 9**: CI/CD automation

**Phase 10**: Domain, HTTPS, monitoring

_Design Notes_

- Wireframes:
- Colour palette:
- Typography:
- Breakpoints:
- Section order: Home, About, Skills, Projects, Contacts
-

_Testing and Quality_

- HTML validation (W3C vaidator)
- Lint and formatting (ESLint, Prettier)
- Axe Accessibility scores
- cross-browser check (Chrome, Firefox, Safari)
- Real-device mobile check
- Broken-link check
- Contact form end-to-end test

_Build and Deployment_

- Hosting platform: name and why
- Build command / output directory
- Environment variables: list names only, never values
- Manual deploy steps: for the first release
- Rollback procedure:

_CI/CD Pipeline_
Describe the workflow in .github/workflows/deploy.yml:

1.  Trigger: push to main
2.  Install dependencies
3.  Lint and test
4.  Build
5.  Deploy to host
6.  Notify on failure
    Add a status badge

_Domain, HTTPS and DNS_

- Registrar
- DNS records: A / CNAME entries used
- HTTPS: how the certificate is issued and renewed
- Redirects: www to apex (or reverse)

_Monitoring and Maintenance_

- Uptime monitoring tool
- Analytics (privacy-friendly option)
- Dependency updates (Dependabot)
- Content update routine (add new projects, referesh resume)

_Roadmap_

- Dark mode
- Docker container for self-hosting

_Changelog_
**Version** **Date** **Changes**
0.1.0 24/11/2026 Initial development

_Licencse and Contact_

- License:
- Author: Samuel Amakundi Bako
- Email: amakondisamuel@gmail.com
