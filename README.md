<p align="left">
  <img src="public/assets/logo-modern-transparent.png" width="112" alt="Modern Construction for Contracting">
</p>

# Modern · Construction for Contracting

**From exploring the work to starting a project conversation.**

**Portfolio showcase.** Application source code remains private.
This public presentation includes selected website captures and project imagery.

A bilingual website for Modern Construction for Contracting, bringing the
company's services, project portfolio, and inquiry experience into one place.
Visitors can explore construction disciplines, look through project imagery,
and share the context the team needs to discuss their requirements.

[Explore Modern](https://www.moderngroupco.com/) ·
[Services](https://www.moderngroupco.com/our-services) ·
[Project portfolio](https://www.moderngroupco.com/projects) ·
[Start an inquiry](https://www.moderngroupco.com/contact-us)

![Modern home page with its green identity, construction crane, and city skyline](docs/readme/screenshots/home-city.png)

## <img src="docs/readme/icons/service-icon-construction.svg" width="24" height="24" alt=""> A clear introduction to the company

The home page introduces Modern through construction imagery, service previews,
selected work, and direct routes into an inquiry. A consistent green identity
connects the opening presentation with the rest of the site.

**English and Arabic. Light and dark themes. Responsive layouts.**
Language selection includes right-to-left presentation for Arabic visitors.

<details>
<summary>View the alternate construction hero</summary>

![Modern's alternate home hero with monochrome construction-site photography](docs/readme/screenshots/home-construction.png)

</details>

## <img src="docs/readme/icons/service-icon-design.svg" width="24" height="24" alt=""> Find the right service

![Service tabs showing the construction discipline, supporting imagery, and request-service action](docs/readme/screenshots/services.png)

Seven service areas make the company's work easier to explore:

| Discipline | Focus |
| --- | --- |
| Construction | Building works and coordinated site delivery |
| Design | Concepts, drawings, and technical coordination |
| Cable work | Electrical and communication-system installation |
| Building materials | Material selection and sourcing inquiries |
| Stonework | Stone, marble, and architectural finishes |
| Woodwork | Joinery and interior wood applications |
| Structural glazing | Glass facades and glazing systems |

Visitors can move from a service into the contact form with the relevant
discipline already selected, keeping the inquiry connected to what they viewed.

## <img src="docs/readme/icons/service-icon-glazing.svg" width="24" height="24" alt=""> Explore the project portfolio

![Tolip Hotel imagery from Modern's existing project portfolio](public/assets/projects/tolip-hotel/tolip-hotel-02.webp)

Category filters group the portfolio by discipline. Opening a project brings
its gallery, scope, and supporting details into focus, helping visitors move
from a broad service category to a specific example of the work.

The selections below come from the project's existing portfolio assets.
They include site photography, architectural drawings, and design imagery.

<details>
<summary>View construction and design selections</summary>

### Chinese Tower

![Reinforcement and formwork shown in the Chinese Tower project gallery](public/assets/projects/chinese-tower/chinese-tower-01.webp)

### King Abdulaziz Airport Training Center

![Architectural site plan from the training-center design portfolio](public/assets/projects/king-abdulaziz-airport-training-center/king-abdulaziz-airport-training-center-02.webp)

</details>

<details>
<summary>View glazing, stonework, and woodwork selections</summary>

### Glazing systems

<img src="public/assets/projects/stick-glazing/stick-glazing-01.webp" width="440" alt="Glass facade detail from the stick-glazing portfolio">

### Marble finishes

<img src="public/assets/projects/marble-projects/marble-projects-01.webp" width="440" alt="Polished marble flooring from the stonework portfolio">

### Interior woodwork

<img src="public/assets/projects/wooden-wall-and-ceiling-covering/wooden-wall-and-ceiling-covering-01.webp" width="560" alt="Bedroom design imagery showing wooden wall and ceiling coverings">

</details>

## <img src="docs/readme/icons/service-icon-materials.svg" width="24" height="24" alt=""> A materials desk in preparation

![Materials preparation page with catalog and request-flow status](docs/readme/screenshots/materials-preparation.png)

The supplied materials-page capture presents the catalog and request flow as
being prepared. Visitors are directed toward planning a materials request and
discussing their needs with the team. This is an inquiry journey rather than
an online checkout.

## <img src="docs/readme/icons/service-icon-cable.svg" width="24" height="24" alt=""> Give the conversation useful context

<img src="docs/readme/screenshots/contact-intake.png" width="760" alt="Modern contact form with request type, service discipline, contact details, location, timeline, subject, and request details">

The contact experience collects the request type, relevant discipline, contact
details, project location, target timeline, and a written brief. Links from
services and projects carry context into the form so visitors can continue
their inquiry without starting over.

Submissions are validated on the server. Email delivery depends on the configured
email service; the form provides feedback when a request cannot be sent.

Modern AI provides an additional way to ask about services, projects, and how
to prepare an inquiry. Provider-backed responses depend on runtime configuration;
the app also includes a local fallback.

## Behind the experience

| Layer | Implementation |
| --- | --- |
| Application | React, TypeScript, and TanStack Start |
| Navigation | TanStack Router |
| Styling and motion | Tailwind CSS, Motion, and React Aria Components |
| Languages | i18next with English and Arabic resources |
| Runtime | Vite development and Cloudflare Workers configuration |
| Inquiry delivery | Server-side validation and Resend integration |


---

Website designed and developed by **[Abdulrahman M. Yaqyn](https://yaqyn.dev/)**.
Modern branding and portfolio imagery represent the client and its project material.

This showcase grants no software distribution license. Branding and portfolio
materials remain subject to their respective rights holders' permissions.
