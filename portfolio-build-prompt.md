# Portfolio Build Prompt — Generoso Roberto

Paste this into Claude Design or Lovable.

---

Build a single-page portfolio website for a public health physician and data analyst named Generoso Roberto.

## Design direction

Clean, editorial minimalism. The audience is NHS trusts, UK Health Security Agency, health tech companies, and global health NGOs. The design should feel trustworthy, clinically credible, and modern — not corporate, not flashy, not a startup pitch deck. Think: The Lancet meets a modern portfolio site.

**Colour palette:**
- Primary: deep navy #003B5C (NHS-adjacent, signals clinical authority)
- Secondary: mid navy #005A8C
- Accent: teal #0F6E56 (health/wellbeing warmth)
- Light fills: #E8F1F8 (navy light), #E1F5EE (teal light), #FAEEDA (amber light), #EEEDFE (purple light)
- Background: warm white #FAFAF8
- Surface: #F4F2EF
- Borders: #E8E5E0
- Text: #1A1A1A primary, #5C5C5C secondary, #8C8C8C tertiary

**Typography:**
- Display/headings: Source Serif 4 (editorial authority)
- Body: Libre Franklin, weight 300-500 (clean, modern readability)

**Design details:**
- Rounded corners (12-14px on cards)
- Subtle entrance animations (fade up, staggered)
- Hover lift on cards (translateY -2px)
- Coloured 4px accent bar at the top of each case study card
- Generous whitespace
- Sticky navigation
- Mobile responsive

## Structure and content

### Header
- Monogram: navy square with rounded corners, white "GR" in serif font
- Name: Generoso Roberto
- Subtitle: Public health physician · Data analyst · UK-based
- Intro paragraph: "A decade leading public health programmes — disease surveillance, outbreak response, health systems research, and USAID-funded data capacity building. Now applying formal data science training to the problems I've spent my career working on."
- Sticky nav: Public health work | Technical projects | Skills | About

### Impact stats row (4 columns)
- 10+ / Years in public health
- 41 / Hospitals in patient safety study
- 7 / Local councils in USAID data programme
- 800+ / Hours data science training

### Professional case studies section
Label: "Professional case studies"

**Card 1 — blue accent (#003B5C → #378ADD)**
- Visualisation: SVG network diagram on light blue (#E8F1F8) background showing a central "DATA HUB" node connected to 7 LGU (local government unit) nodes with lines. Team labels (IT, Data Science, Public Health, DRR) as small navy pill badges around the network. Shows the coordination structure visually.
- Title: COVID-19 data capacity building across seven local councils
- Org: USAID-RTI · Project manager
- Tag: Programme management (navy light bg)
- Description: Managed a USAID-funded initiative to strengthen COVID-19 data management capacity. Coordinated cross-functional teams spanning IT, data science, public health, and disaster risk reduction across seven local government councils.
- Outcomes: Coordinated multi-disciplinary teams across seven councils | Strengthened local COVID-19 data collection and reporting systems | Bridged data science and public health practice at local government level
- Tools: Data management · Capacity building · Cross-functional coordination

**Card 2 — teal accent (#0F6E56 → #5DCAA5)**
- Visualisation: SVG dashboard preview on light teal (#E1F5EE) background. Three metric boxes on the left (41 Hospitals, 600 Indicators, 1 Publication) in white with teal borders. A bar chart on the right showing varying heights of teal bars representing indicator distributions. Below, a row of placeholder data lines suggesting automated report output.
- Title: National patient safety study across 41 hospitals
- Org: University of Manila · Science research specialist
- Tag: Research (teal light bg)
- Description: Contributed to a national-scale patient safety study. Built Excel-based automation tools that generated summaries for 600 patient safety indicators, reducing manual reporting burden. Co-authored a peer-reviewed journal article on the findings.
- Outcomes: Automated reporting for 600 patient safety indicators | Co-authored peer-reviewed publication | Presented at the 2nd National Antimicrobial Resistance Summit
- Tools: Excel automation · Patient safety · Peer-reviewed research

**Card 3 — amber accent (#854F0B → #EF9F27)**
- Visualisation: SVG regression scatter plot on light amber (#FAEEDA) background. Left panel shows a scatter plot with amber/brown dots and a diagonal regression line trending upward. Right side has three metric boxes: "684 Patient records analysed", "5 Tertiary hospitals", and "311 News articles — qualitative media content analysis".
- Title: AMR burden and costing study — five tertiary hospitals
- Org: Independent researcher
- Tag: Data analysis (amber light bg)
- Description: Designed and conducted a study on the economic burden of antimicrobial resistance across five tertiary hospitals, analysing 684 patient records using logistic and multivariate regression in Stata. A second study applied qualitative media content analysis to 311 news articles on the Dengue vaccine controversy.
- Outcomes: 684 patient records, logistic and multivariate regression | 311-article qualitative media content analysis | Statistical modelling in Stata
- Tools: Stata · Regression analysis · Health economics

**Card 4 — purple accent (#534AB7 → #AFA9EC)**
- Visualisation: SVG flow diagram on light purple (#EEEDFE) background. Five connected boxes showing a disease surveillance pipeline: COMMUNITY (Health workers) → DETECTION (Surveillance data) → ANALYSIS (Municipal health officer, filled purple as the highlighted role) → RESPONSE (Outbreak control) → REPORT (DOH regional). Below, pill-shaped labels for team members: Nurses, Midwives, Ward coordinators, Preventive programmes.
- Title: Municipal health leadership — disease surveillance and outbreak response
- Org: Department of Health · Municipal health officer
- Tag: Leadership (purple light bg)
- Description: Led all preventive health programmes, disease surveillance, and outbreak response for an underserved rural municipality. Coordinated community health workers, nurses, and midwives across ward-level service delivery.
- Outcomes: Led municipality-wide disease surveillance system | Managed multi-disciplinary community health team | Delivered outbreak response for underserved population

**Card 5 — navy accent (#003B5C → #005A8C)**
- Title: National postgraduate programme — learning management
- Org: Development Academy · Learning manager
- Tag: Operations (navy light bg)
- Description: Managed full-cycle implementation of a two-year national postgraduate programme for approximately 100 rural physicians. Coordinated government officials, faculty, and administrative processes. Identified and resolved a six-month contract payment backlog that had stalled programme operations.
- Outcomes: Managed programme for ~100 physicians across two years | Resolved six-month payment backlog blocking operations | Coordinated government, academic, and administrative stakeholders

### Technical projects section
Label: "Technical projects"
2-column grid of cards. Each card has a visual preview area (100px height) at the top with a stylised SVG, then the title and description below:

1. COVID-19 vaccine prioritisation — Visual: cluster bubbles on light blue background in varying sizes and 4 colours (navy=Priority 1, blue=Priority 2, teal=Low priority, amber=Low resource) with a small legend. Inspired by the original k-means cluster map. Description: K-means clustering to optimise vaccine rollout sequencing. Python, scikit-learn.
2. NHS A&E admission analysis — Visual: histogram bars on light teal background showing a right-skewed distribution (tall bars in centre fading right), with x-axis label "Time spent in A&E (min)". Inspired by the original histogram. Description: Emergency department admission patterns and seasonal trends. Python, Pandas.
3. Global life expectancy trends — Visual: grouped bar chart on light blue background showing 4 income categories (Low income, Lower mid, Upper mid, High) each with a light bar (2000) and darker bar (2015), with "+8yr", "+5yr", "+4yr", "+4yr" labels above. Inspired by the original Tableau dashboard. Description: Shifts across countries 2000–2015, highlighting health system disparities. Tableau.
4. Disease & risk factor mapping — Visual: two panels on light amber background. Left panel has vertical bars in alternating dark/light amber. Right panel has a simple pie/donut chart. Inspired by the original interactive dashboard. Description: Relationships between modifiable risk factors and disease burden. Python.
5. US poverty & health equity — Visual: simplified bubble map on light blue background, translucent navy circles of varying sizes scattered across a white rectangle suggesting a geographic distribution. Inspired by the original Mapbox choropleth. Description: Geographic patterns linking poverty rates to population health outcomes.
6. Coming soon (dashed border, muted text) — Visual: light surface background with a dashed circle and "In progress" text, "UK health data" below. Description: Women's health outcomes & PCOS prevalence — UK data analysis.

### Skills section
Label: "Skills & tools"
2x2 grid:

- Analysis & languages: Python, SQL, Stata, Pandas, scikit-learn, R
- Visualisation & reporting: Tableau, Matplotlib, Excel automation, Data storytelling
- Public health domain: Epidemiology, Disease surveillance, AMR, Health economics, Patient safety
- Methods: Regression analysis, K-means clustering, Content analysis, Programme evaluation

Use pill-shaped chips on the surface background colour.

### About section
Label: "About"
Layout: avatar circle (navy light bg with a document/clipboard icon) + text

Text: "Public health physician with a decade of experience in disease surveillance, health systems research, and programme management — including USAID-funded data initiatives. Now bringing formal data science training to public health analytics in the UK."

Credential badges: Registered physician | Turing College Data Science | Peer-reviewed author

Seeking box (surface bg, rounded): "Looking for: Data analyst or public health intelligence roles where clinical and public health experience is an advantage, not just context. UK-based, no sponsorship required."

Links:
- Get in touch (primary button, navy bg, links to mailto:generoso.gr.roberto@gmail.com)
- Full background (links to https://www.linkedin.com/in/generoso-roberto/)
- GitHub (links to https://github.com/biogear13)
- Download CV

### Footer
- Left: © 2026 Generoso Roberto
- Right: UK-based · No sponsorship required

## Important positioning notes
- Do NOT mention Philippines or any specific country in the main content — let institution names carry context
- Frame as career deepening, not career changing — he's been working with health data for a decade, now formalising the technical skills
- "No sponsorship required" appears in both the About section and the footer
- Professional case studies come FIRST, technical bootcamp projects are secondary
- Keep the About section short — LinkedIn has the full story
- The whole site should make a UK public health hiring manager think "this person understands our world"
