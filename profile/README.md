<a name="readme-top"></a>

<!-- [![Contributors][contributors-shield]][contributors-url] -->
<!-- [![Forks][forks-shield]][forks-url] -->
<!-- [![Stargazers][stars-shield]][stars-url] -->

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#frontend">Frontend</a></li>
        <li><a href="#backend">Backend</a></li>
        <li><a href="#other">Other</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

### Built With

![Testing-Library](https://img.shields.io/badge/-TestingLibrary-%23E33332?style=for-the-badge&logo=testing-library&logoColor=white)
![Svelte](https://img.shields.io/badge/svelte-%23f1413d.svg?style=for-the-badge&logo=svelte&logoColor=white)
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Bun](https://img.shields.io/badge/Bun-%23000000.svg?style=for-the-badge&logo=bun&logoColor=white)
![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white)
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white)

<!-- GETTING STARTED -->

## Getting Started

The organization is designed to reuse common software design patterns used in frontend and backend projects as templates after a new repository is created.
At minimum, each template needs architecture for large scale projects and authentication because it's used entirely everywhere.
Enhancements are welcomed for designing the best possible architecture, for example:

```bash
DDD: Domain Driven Design
CQRS: Command Query Responsibility Segregation
MVC: Model, View, Controller
FSD: Feature-Sliced Design
```

| Stack         | Architecture                                                                     |
| ------------- | ---------------------------------------------------------------------------------|
| Backend       | Factory Pattern, DDD, CQRS, MVC                                                  |
| Frontend      | Advanced File Based Routing / Pattern Matching, FSD, and State Management        | 
| Microservices | ...                                                                              |


#### Frontend

1. **Playwright E2E Testing**
   - Page Object Model
   - HTML Reporter to GitHub Pages using GitHub Actions

2. **SvelteKit**
   - SvelteKit-FSD
     - Feature-Sliced Design
     - Shadcn

3. **NextJS**
   - Dark Mode
   - Shadcn UI Library
   - File-Based Routing
   - SPA
   - Support .mdx file type

4. **Flutter**
   - (To be implemented)

5. **Telegram Mini App**
   - File-Based Routing
   - API Integration

### Backend

1. **FastAPI Template**
   - Factory Pattern
   - Authentication

2. **Bun/NodeJS Template**
   - SOLID
   - OpenAPI Specification
   - Database Providers

3. **Golang Template**
   - (To be implemented)

4. **SpringBoot Template**
   - (To be implemented)

5. **Laravel Template**
   - MVC Pattern
   - Authentication

6. **C# Template**
   - (To be implemented)

#### Other 

1. **LaTeX**
   - CI/CD pipeline
   - DRY

2. **Plotly Dash**
   - FastAPI server
   - API setup
   - TailwindCSS

<!-- ROADMAP -->

## Roadmap

- [ ] Frontend Project
  - [x] Playwright E2E Template
  - [x] SvelteKit Template
  - [x] NextJS Template
  - [ ] Flutter Template
  - [x] Telegram Mini App Template

- [ ] Backend Project
  - [x] FastAPI Template
  - [x] Bun/NodeJS Template
  - [ ] Golang Template
  - [ ] SpringBoot Template
  - [x] Laravel Template
  - [ ] C# Template

- [x] Other
  - [x] LaTeX Template
  - [x] Plotly Dash

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## External Sources

When striving to write clean code, it's often helpful to refer to established style guides and best practices. Here are some valuable resources worth checking out:

- [Airbnb Style Guides](https://github.com/airbnb/javascript)
  Airbnb provides comprehensive style guides for various programming languages, including JavaScript. These guides cover a wide range of topics, from syntax and formatting to architectural decisions.

- [Uber Style Guides](https://github.com/uber-go/guide/blob/master/style.md)
  Uber offers style guides tailored specifically for Go programming. These guides provide recommendations on code organization, naming conventions, error handling, and more, based on Uber's extensive experience with Go development.

By consulting these resources, you can gain insights into industry-standard practices and adopt conventions that promote readability, maintainability, and consistency in your codebase.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Design decisions:

|Company|Description|Needs|Goal|
|--|--|--|--|
|Sole Developer|It's just you, you want to have fun and not get burned out by GitHub requests|Keep it Simple! Scale may not be the top priority, but avoiding spaghetti is.|Modular Monolith|
|Small Startup|You're just getting going and don't have many customers yet|Keep costs low. Keep it simple. Scale isn't a priority now, but you hope it will be. Telemetry.|Modular Monolith|
|Rapidly Expanding|You've got customers and need to scale to fit demand.|Telemetry, understand the pain points. Code that supports adding developers.|Modular Monolith that can be divided|
|Webscale!|You've made it! You're supporting Google-style load, and heating data-centers around the world.|Telemetry, Manageability, Supporting Diverse Teams|Readily divided services|

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## License

Distributed under the Apache 2.0 License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/shohinsan/readme.svg?style=for-the-badge
[contributors-url]: https://github.com/diego-ruben-cruz/TemplateAbyss/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/shohinsan/readme.svg?style=for-the-badge
[forks-url]: https://github.com/diego-ruben-cruz/TemplateAbyss/forks
[stars-shield]: https://img.shields.io/github/stars/shohinsan/readme.svg?style=for-the-badge
[stars-url]: https://github.com/diego-ruben-cruz/TemplateAbyss/stargazers
[issues-shield]: https://img.shields.io/github/issues/shohinsan/readme.svg?style=for-the-badge
[issues-url]: https://github.com/diego-ruben-cruz/TemplateAbyss/issues
[license-shield]: https://img.shields.io/github/license/shohinsan/readme.svg?style=for-the-badge
[license-url]: https://github.com/diego-ruben-cruz/TemplateAbyss/blob/master/LICENSE
