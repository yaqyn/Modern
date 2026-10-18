![Modern Construction for Contracting, with its green logo and architectural cover artwork](docs/readme/cover.webp)

# Modern — Construction for Contracting

**Explore the work, find the right service, and start a project conversation.**

A bilingual website for Modern Construction for Contracting. Service pages,
project galleries, and context-aware inquiry links help visitors describe what
they need and give the team a useful starting point for the conversation.

**Public portfolio showcase.** Application source code remains private. This
presentation includes selected interface captures and existing project imagery.

[Explore Modern](https://www.moderngroupco.com/)

![Modern's home page with service navigation and a city-skyline hero](docs/readme/screenshots/home-city.webp)

## <img src="docs/readme/icons/features.svg" width="24" height="24" alt=""> Features

- Explore seven service disciplines and continue into a relevant inquiry.
- Filter the project portfolio and open galleries, scope, and supporting details.
- Carry service or project context into a structured contact form.
- Browse in English or Arabic, with right-to-left layouts and light/dark themes.

## <img src="docs/readme/icons/launch.svg" width="24" height="24" alt=""> Try the showcase

| Start here | What to look for |
| --- | --- |
| [Services](https://www.moderngroupco.com/our-services) | Select a discipline and follow its inquiry action. |
| [Projects](https://www.moderngroupco.com/projects) | Filter by discipline and open a project's gallery. |
| [Contact](https://www.moderngroupco.com/contact-us) | Review the request type, service, location, and timeline fields. |

A service inquiry should open the contact experience with the relevant context
selected. The contact form is a business inquiry channel; submit only genuine
requests. The materials-page capture below shows a preparation state, rather
than a completed online marketplace.

## <img src="docs/readme/icons/usage.svg" width="24" height="24" alt=""> Usage

### <img src="docs/readme/icons/overview.svg" width="20" height="20" alt=""> Company presentation

The home page introduces Modern through construction imagery, service previews,
selected work, and direct routes into an inquiry. The green identity connects
that opening presentation with the rest of the experience.

<details>
<summary>View the alternate construction hero</summary>

![Alternate home hero with monochrome construction-site photography](docs/readme/screenshots/home-construction.webp)

</details>

### <img src="docs/readme/icons/usage.svg" width="20" height="20" alt=""> Find a service

![Service tabs, construction details, and the request-service action](docs/readme/screenshots/services.webp)

| Discipline | Focus |
| --- | --- |
| Construction | Building works and coordinated site delivery |
| Design | Concepts, drawings, and technical coordination |
| Cable work | Electrical and communication-system installation |
| Building materials | Material selection and sourcing inquiries |
| Stonework | Stone, marble, and architectural finishes |
| Woodwork | Joinery and interior wood applications |
| Structural glazing | Glass facades and glazing systems |

Service links carry the selected discipline into the inquiry form, keeping the
request connected to what the visitor was exploring.

### <img src="docs/readme/icons/projects.svg" width="20" height="20" alt=""> Explore project galleries

![Tolip Hotel imagery from the existing Modern portfolio](docs/readme/photos/tolip-hotel.webp)

Category filters group the portfolio by discipline. Opening a project brings
its gallery, scope, and supporting details into focus. The selections below
come from existing portfolio assets and include photographs, an architectural
site plan, and interior-design imagery.

<details>
<summary>View construction and design selections</summary>

**Chinese Tower**

![Reinforcement and formwork from the Chinese Tower gallery](docs/readme/photos/chinese-tower.webp)

**King Abdulaziz Airport Training Center**

![Architectural site plan from the training-center design portfolio](docs/readme/photos/training-center.webp)

</details>

<details>
<summary>View glazing, stonework, and woodwork selections</summary>

**Glazing systems**

<img src="docs/readme/photos/stick-glazing.webp" width="440" alt="Glass facade detail from the stick-glazing portfolio">

**Marble finishes**

<img src="docs/readme/photos/marble-projects.webp" width="440" alt="Polished marble flooring from the stonework portfolio">

**Interior woodwork**

<img src="docs/readme/photos/interior-woodwork.webp" width="560" alt="Bedroom design imagery showing wooden wall and ceiling coverings">

</details>

### <img src="docs/readme/icons/catalog.svg" width="20" height="20" alt=""> Plan a materials request

![Materials desk showing catalog and request-flow preparation](docs/readme/screenshots/materials-preparation.webp)

The supplied capture presents the catalog and request flow as being prepared.
Visitors are directed toward planning a materials request and discussing their
needs with the team. This journey does not provide an online checkout.

### <img src="docs/readme/icons/contact.svg" width="20" height="20" alt=""> Start an inquiry

<img src="docs/readme/screenshots/contact-intake.webp" width="760" alt="Contact form with request type, service discipline, contact details, location, timeline, subject, and request details">

The form collects the request type, relevant discipline, contact details,
project location, target timeline, and a written brief. Service and project
links carry context into the form so visitors can continue without starting over.

Server-side validation checks submissions. Email delivery depends on the
configured email service; the form provides feedback when a request cannot be
sent. Modern AI offers another route to service and project information, with
provider-backed responses dependent on runtime configuration and a local
fallback available in the application.

## <img src="docs/readme/icons/architecture.svg" width="24" height="24" alt=""> Architecture

TanStack Start connects the React interface to server functions for inquiries
and assistant requests. Language resources support English and Arabic, while
shared navigation helpers preserve the context of an inquiry across pages.

| Layer | Implementation |
| --- | --- |
| Application | React, TypeScript, and TanStack Start |
| Navigation | TanStack Router |
| Styling and interaction | Tailwind CSS, Motion, and React Aria Components |
| Languages | i18next with English and Arabic resources |
| Runtime | Vite development and Cloudflare Workers configuration |
| Inquiry delivery | Server-side validation and Resend integration |

## <img src="docs/readme/icons/verification.svg" width="24" height="24" alt=""> Verification

Documentation checks validate local image references, private/public export
boundaries, brand-green icon geometry, and the publishing command's behavior
from another working directory. Raster conversions preserve dimensions and
decoded pixels; a staged secret scan precedes public publication.


## <img src="docs/readme/icons/security.svg" width="24" height="24" alt=""> Security and limitations

- Application source, private history, deployment workflows, and credentials
  stay in the private repository. The public repository holds presentation files.
- Screenshots show the supplied interface state; they do not verify current
  email delivery, AI-provider access, or completion of the materials marketplace.
- The cover is illustrative brand artwork. Portfolio captions distinguish site
  photography, drawings, and design imagery.

## <img src="docs/readme/icons/owner.svg" width="24" height="24" alt=""> Maintainer

Website designed and developed by **[Abdulrahman M. Yaqyn](https://yaqyn.dev/)**.
Business inquiries belong in [Modern's contact form](https://www.moderngroupco.com/contact-us).

## <img src="docs/readme/icons/license.svg" width="24" height="24" alt=""> License and acknowledgments

This showcase grants no software distribution license. Modern's branding and
portfolio imagery represent the client and its project material and remain
subject to their respective rights holders' permissions.
