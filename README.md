# 👋 Hey!

### 🌊 <span style="color:#ADD8E6">_log.a.SURFLOCATION_ </span>🌊

is web mapping application to log your surfing sessions and destinations.
The project is at an early stage & collaboration is very welcome. 💫

---

<br>

This README contains following information & instructions:

- [Short project description](#project-description)
- [How the project can be installed and built](#project-setup)
- Process of desired collaboration
- Links to additional information

#### <a id="project-description"></a> Project description

As a user, I want to log my surfing sessions via a map application.

The application consists of two panels. The **left-side panel** contains the map. The map should be loaded based on the user's current position (via the Geolocation API).

The **right-side panel** will display a formula and a list of logged surf sessions. The formula will appear (on the right side panel) after the user clicks on a position on the map. Additional data can be input into the formula, e.g. title, date, time, duration of surf session, type of surf destination (reef, beach, rock, mixed), rating of surf session, and some text to describe it. The panel could be collapsible. The list of logged surf sessions will always be displayed (below the formula).

![application wireframe](/readme-data/wireframe.png)

Task list:

- [x] Create a GitHub Repository
- [x] Dockerize Static Website
  - [x] test branch: new-basic-frontend
  - [x] docker container can be build and run
- [ ] Create Documentation, How to setup, How to collaborate via Pull Request
- [ ] Define Web-Application Design, Wireframes, Icons, Colour schemes (with Figma)
- [ ] Define Use-Cases
- [ ] Create Vanilla Javascript Project
- [ ] Include leaflet.js for map component
- [ ] Translation Vanilla JS Project into React.js
- [ ] Use Typescript
- [ ] Backend (nodejs, fastAPI or Django...)
- [ ] Database (postgreSQL/postGIS or sqlite/SpatiaLite)
- [ ] Mobile App

#### <a id="project-setup"></a> Project setup

Take a look at the installation guide [here](docs/installation.md).

#### How-To... write clean code

Take a look at the development guidelines [here](docs/development_guidelines.md).
