# Rob Dahl

Full-stack software engineer with 8+ years of experience building React, TypeScript, Node.js, and
GraphQL applications across enterprise products, search, compliance, identity/authentication, and
internal platforms. Most of my work has been turning ambiguous business needs, legacy systems, and
cross-team constraints into product experiences that are easier to use, ship, and support.

Outside of that, I build things that give me an excuse to work closer to the data: telemetry
analysis, image pipelines, and the infrastructure they run on.

## Selected projects

- **[Job Search Dashboard](https://jobs.robdahl.dev)** — A self-hostable job tracker with
deterministic offline posting extraction, configurable fit scoring, and application tracking. LLM
analysis is layered on as an optional enhancement rather than a dependency, so parsing still works
with no model in the loop. [Source](https://github.com/RobDahl/job-dashboard)

- **[Paper Trace](https://f1.robdahl.dev)** — Formula 1 lap telemetry rendered as a pen-plotter
printout. A Python/FastAPI/NumPy analysis service over the official FastF1 timing archive feeds
hand-authored SVG charts on a Next.js front end that ships almost no JavaScript, with 185 pre-built
session snapshots so the site works with the backend switched off.
[Source](https://github.com/RobDahl/f1-telemetry-dashboard)

- **[Customer Order Management System](https://github.com/RobDahl/customer-order-management-system)**
— An order, invoicing and payments system in C#/.NET where an ASP.NET Core MVC web app and a .NET
Framework 4.8 WinForms client share one domain model and Dapper data layer over a SQL Server schema
owned by T-SQL migrations and stored procedures. Includes CSV import, five reports, and 297 tests
run in CI against a SQL Server container.

- **[Slicedeck](https://slicedeck.robdahl.dev)** — Splits one live camera frame across the keys of an
Elgato Stream Deck so the whole device becomes a single low-resolution display. Press a key and the
deck zooms into it. The browser demo runs the same pipeline with no camera or hardware attached.
[Source](https://github.com/RobDahl/slicedeck)

- **[Portfolio](https://robdahl.dev)** — Personal Portfolio site using Next.js, Tailwind CSS, and a resume compiled from
Typst source in the repo. [Source](https://github.com/RobDahl/next-portfolio)

## Elsewhere

- Portfolio: [robdahl.dev](https://robdahl.dev)
- LinkedIn: [linkedin.com/in/rob-dahl](https://www.linkedin.com/in/rob-dahl)
