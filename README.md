Moulik Chaturvedi — Personal Portfolio
A simple personal profile website introducing me, listing my current skills, and linking to selected programming coursework/projects.
Live website: [PLACEHOLDER — add your deployed portfolio URL]
Repository: [PLACEHOLDER — add the portfolio repository URL]

Screenshots
These screenshots were supplied with this project on 22 October 2026.
1. Profile, About, and Skills

2. Projects and Footer

About
I am a 2nd-year B.Tech Computer Science Engineering student interested in programming, C++, and Data Structures and Algorithms. I am building my technical skills and working toward a software engineering career.
Features and user actions
Visitors can perform these actions:
1. Read the profile: View the About and Skills sections.
2. Open a project: Select a View Project link to visit the linked GitHub file.
3. Switch the theme: Use the theme button to toggle between light and dark mode. The JavaScript stores the selected theme in localStorage, so the preference can persist in the same browser.
Projects shown
- Factorial — links to factorial.py in the Python basics repository.
- Fibonacci and Structure — links to fibonacci_and_structure.py.
- Audit table — links to AUDIT.md, described on the page as a comparison of original and clearer AI-generated commit messages.
Project destinations are the links present in the supplied HTML. Their current availability and contents have not been independently verified.
Tech stack
- HTML5: Page structure and content.
- CSS: External stylesheet referenced as style.css (the stylesheet source was not provided with the supplied HTML).
- JavaScript: Theme toggle, theme-button accessibility attributes, and theme preference handling.
- Browser localStorage: Saves the selected theme as dark or light.
No framework, package manager, backend, database, build system, or automated test setup is evidenced by the supplied HTML.
Run locally
1. Download or clone the portfolio project.
2. Keep index.html and style.css in the same directory.
3. Open index.html in a modern web browser.
For a local development server, you may use Python if installed:
python -m http.server 8000
Then open http://localhost:8000.

Run that command from the folder containing index.html. The supplied page references style.css, so that file must be present for its intended styling. The theme toggle requires JavaScript and browser storage support; if storage is blocked or unavailable, persistence may not work.
Repository structure
portfolio/
├── index.html
├── style.css                 # referenced by HTML; include your actual stylesheet
├── README.md
└── screenshots/
    ├── portfolio-top.png
    └── portfolio-projects-footer.png
Adjust this tree if your actual repository differs.
Limitations and notes
- Live URL is not available in the supplied material. Replace the placeholder above after deploying the website.
- The CSS file was referenced but not supplied here; visual styling is represented by the screenshots, not verified from stylesheet source.
- The screenshots show a rendered page, but do not prove that every interaction or project destination was tested.
- The provided HTML contains no contact section or contact details.
- The theme toggle updates the button text and accessibility attributes and saves a theme preference. The exact appearance of each theme depends on CSS rules in style.css.
- This page links to project files in another GitHub repository; it does not embed or run those projects.
Claim audit
README claim	Evidence / status
The page title is “Moulik Chaturvedi | Personal Profile”	Verified in supplied HTML <title>.
The page has About, Skills, Projects, and footer sections	Verified in supplied HTML; screenshots show these page areas.
Listed skills are C++, Data Structures and Algorithms, C, Github, and Prompt Engineering	Verified as page content in supplied HTML (case/spelling retained as authored where relevant).
Three project entries and their GitHub destinations are present	Verified as link markup in supplied HTML; destination availability/content not verified.
A theme button toggles the dark-mode body class	Verified in supplied JavaScript.
Theme preference is read from and written to localStorage	Verified in supplied JavaScript. Successful persistence in every browser is not guaranteed.
The page uses HTML, CSS, and JavaScript	Verified: HTML document, linked style.css, and inline script. CSS implementation details are not supplied.
The site is live at a specific URL	Unknown — PLACEHOLDER. No deployed URL was supplied.
The website is responsive/accessibility-compliant or fully tested	Not claimed; the viewport meta tag and button attributes alone do not establish full compliance or testing.


Credits
Created by Moulik Chaturvedi. Screenshots were provided for this README package.
