# New Leaf Luxury Lawn Website

## Student Information
- **Student Name:** Mbudi Nkode
- **Student Number:** ST10526469
- **Module Code:** DINM1 WEDE5020
- **Academic Year:** 2026

## Project Overview
A static website developed for **New Leaf Luxury Lawn**, a luxury lawn-care and landscaping service operating in Johannesburg's Northern Suburbs.

This project demonstrates the design and implementation of a multi-page business website using semantic HTML, CSS, and JavaScript. The repository also contains supporting project documentation, including a sitemap and homepage wireframe.

## Project Purpose & Goals
The purpose of this project is to provide a clear, responsive, and professional web presence for New Leaf Luxury Lawn while demonstrating fundamental front-end development practices.

The site is structured around the following goals:
- Present the company and its services clearly.
- Provide straightforward navigation between key pages.
- Give prospective customers a way to submit an enquiry.
- Provide contact information and relevant business details.
- Maintain a consistent visual identity across the website.
- Separate page structure, presentation, and behaviour into HTML, CSS, and JavaScript where appropriate.

## Pages
| Page | File | Purpose |
|---|---|---|
| Home | `index.html` | Main landing page and introduction to the business. |
| About | `about.html` | Provides information about New Leaf Luxury Lawn. |
| Services | `services.html` | Presents the lawn and landscaping services offered. |
| Enquiry | `enquiry.html` | Provides an enquiry form for prospective customers. |
| Contact | `contact.html` | Provides contact and communication information. |

## Technologies Used
- **HTML5** — page structure and semantic content.
- **CSS3** — layout, typography, colours, spacing, responsive presentation, and component styling.
- **JavaScript** — client-side interactive functionality.
- **Web assets** — images and other supporting resources stored within the project.
- **VS Code / browser developer tools** — development and debugging workflow.

## Project Structure
The main project structure is organised as follows:

```text
New Leaf Luxury Lawn
├── Home (index.html)
├── About (about.html)
├── Services (services.html)
│   └── Project Gallery
│       ├── Commercial (gallery-commercial.jpg)
│       ├── Poolside (gallery-poolside.jpg)
│       ├── Putting Green (gallery-puttinggreen.jpg)
│       └── Residential (gallery-residential.jpg)
├── Contact (contact.html)
└── Get a Quote (enquiry.html)
│
├── css/
│   ├── style.css
│
├── js/
│   └── main.js
│
├── images/
│   └── ...
│
└── docs/
    ├── sitemap
    ├── homepage wireframe
    └── ...
```
The exact contents of the `css/`, `images/`, and `docs/` directories may change as development continues.

## CSS Architecture
The project uses CSS files to control the visual presentation of the website.

`css/style.css` provides the primary styling shared across the website, while additional page-specific stylesheets are used where individual pages require their own presentation rules. 

This approach allows common styles to be reused while keeping page-specific styling separate. When troubleshooting styles in the browser, Chrome/Edge DevTools can be used to identify the stylesheet and line responsible for a particular CSS rule.

## JavaScript
Client-side JavaScript is located in:
```text
js/main.js
```
JavaScript is used for browser-side functionality and interaction rather than server-side processing.

## Documentation
The `docs/` directory contains supporting design documentation created during development.

This includes:
- The website sitemap, which represents the relationship between the main pages.
- The homepage wireframe, which provides a visual plan for the page layout before or during implementation.

These documents help connect the planning/design stage with the final implementation.

## Budget 
- **Domain name:** ± R200 per year.
- **Hosting:** ± 1000 per year.
- **Email hosting:** ± R50 per month.
- **Development:** R0 (done by student).
- **Images:** R0 (Creative Commons or provided by business).

## Timeline 
- **Week 1:** Research, documentation (sitemap/wireframes), and content collection.
- **Week 2:** Create semantic HTML structure for all pages.
- **Week 3:** Apply global and page-specific CSS styling.
- **Week 4:** Add JavaScript functionality and test across browsers/viewports.
- **Week 5:** Final bug fixes, project documentation, and submission.

## Running the Website Locally
The project is a static website and does not currently require a backend server or database for basic viewing.

### Option 1 — Open directly
Open `index.html` in a modern web browser.

### Option 2 — Use VS Code Live Server
For development, using a local web server such as the **Live Server** extension in Visual Studio Code is recommended.
1. Open the project folder in Visual Studio Code.
2. Open `index.html`.
3. Start Live Server.
4. Open the generated local URL in your browser.

Using a local server can provide a more realistic development environment and makes it easier to test navigation and browser behaviour.


## Current Development Status
The website is an active development project. The core multi-page structure and styling are in place, with further refinement possible as requirements evolve.

Potential future work may include:
- Further responsive design improvements.
- Additional form validation.
- Improved accessibility.
- Performance optimisation.
- Additional interactive functionality.
- Deployment to a production web server.
- Integration with a backend for enquiry submissions if required.

## Conclusion
This project establishes a functional and professional web presence for New Leaf Luxury Lawn. By combining HTML for structure, CSS for responsive design.

## References
- Rosebank College (2026). Website Development POE Guidelines. The Independent Institute of Education (Pty) Ltd.
- W3Schools (2026). HTML, CSS, and JavaScript Tutorials. Available at: https://www.w3schools.com/ (Accessed: 2026).
- Mozilla Developer Network (MDN) (2026). Web Docs. Available at: https://developer.mozilla.org/ (Accessed: 2026).
- New Leaf Luxury Lawn (2026). Internal Business Information and Service Descriptions. Johannesburg, South Africa.