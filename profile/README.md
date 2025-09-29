
<a name="readme-top"></a>

## Table of Contents

- [Getting Started](#getting-started)  
- [Roadmap](#roadmap)  
- [External Sources](#external-sources)  
- [Design Decisions](#design-decisions)  
- [License](#license)  

---

## Getting Started

| Stack         | Architecture                                                                     |
| ------------- | ---------------------------------------------------------------------------------|
| Backend       | Factory Pattern, DDD, CQRS, MVC                                                  |
| Frontend      | Advanced File-Based Routing / Pattern Matching, FSD, and State Management        | 
| Microservices | Domain isolation, communication standards (planned)                              |

---

## Roadmap

### Frontend  
- [x] [Playwright E2E Template](https://github.com/BuildFrom/Playwright)  
- [x] SvelteKit Template  
- [x] [Next.js Template](https://github.com/BuildFrom/NextJS)  
- [ ] Flutter Template  
- [x] [React Native Expo](https://github.com/BuildFrom/ReactNative-Expo)  
- [x] [Telegram Mini App](https://github.com/BuildFrom/MiniApp)  

### Backend  
- [x] [FastAPI Template](https://github.com/BuildFrom/FastAPI)  
- [x] [Bun/Node.js Template](https://github.com/BuildFrom/Bun)  
- [ ] [Golang Template](https://github.com/BuildFrom/Golang-Stdlib)  
- [ ] Spring Boot Template  
- [x] Laravel Template  
- [ ] C# Template  
- [x] Rust Template  

### Other  
- [x] [LaTeX Template](https://github.com/BuildFrom/LaTeX)
- [x] [Plotly Dash](https://github.com/BuildFrom/PlotlyDash)  
- [x] [OpenAI Agents SDK](https://github.com/BuildFrom/OpenAI-Agents)  
- [ ] [Gemini Agents SDK](https://github.com/BuildFrom/Gemini-Agents)  

<p align="right">(<a href="#readme-top">Back to top</a>)</p>

---

## External Sources

To ensure code quality and maintainability, the following style guides and resources are recommended:

- [Airbnb Style Guides](https://github.com/airbnb/javascript) — JavaScript standards and conventions.  
- [Uber Go Style Guide](https://github.com/uber-go/guide/blob/master/style.md) — Comprehensive practices for Go development.  
- [Google Style Guides](https://google.github.io/styleguide/) — Guidelines across multiple languages.  
- [shadcn/ui Theme Generator](https://zippystarter.com/tools/shadcn-ui-theme-generator) — Custom theme generator.  

---

## Design Decisions

| Company Type         | Description                                                        | Key Needs                                      | Recommended Approach         |
|----------------------|--------------------------------------------------------------------|------------------------------------------------|------------------------------|
| Sole Developer       | Independent contributor, focusing on enjoyment and avoiding burnout | Simplicity, maintainability                    | Modular Monolith             |
| Small Startup        | Early stage, limited customers and resources                      | Cost efficiency, simplicity, telemetry         | Modular Monolith             |
| Rapidly Expanding    | Scaling user base and development team                            | Telemetry, developer onboarding, modular code  | Modular Monolith (scalable)  |
| Enterprise (Webscale)| Large-scale global operations                                      | Telemetry, manageability, team scalability     | Service-oriented architecture |

<p align="right">(<a href="#readme-top">Back to top</a>)</p>

---

## License

Distributed under the **Apache 2.0 License**. See `LICENSE.txt` for details.

<p align="right">(<a href="#readme-top">Back to top</a>)</p>
