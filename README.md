<h1 align="center">Hi, I'm Jason Irie 👋</h1>

<h3 align="center">Software Developer · Full-Stack Applications, APIs & Automation</h3>

<p align="center">
  I build reliable backend systems, API integrations, automation tools, and scientific software.<br/>
  My work spans e-commerce operations, AI-assisted applications, robotics, and space-weather research.
</p>

<p align="center">
  <a href="https://portfoliowebsite-36391.web.app/">
    <img src="https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Jason Irie's portfolio" />
  </a>
  <a href="https://www.linkedin.com/in/jason-irie-2bb2b0243/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Jason Irie on LinkedIn" />
  </a>
</p>

## About Me

- 🎓 UCLA graduate with a **B.S. in Mathematics of Computation**
- 🔌 Experienced in **Python, FastAPI, React, REST APIs, automation, and OpenAI integrations**
- ⚙️ Built integrations across **7+ e-commerce and operations platforms**
- ⏱️ Automated **8+ manual workflows**, turning processes that took 1–2 hours into tasks completed in minutes
- 🛰️ Developed scientific-computing pipelines for NASA's **EZIE heliophysics mission** at JPL
- 🤖 Background in soft-robot simulation, autonomous navigation, LiDAR mapping, embedded systems, and reinforcement learning

## Current Experience

### Software Developer - Backend & API Integrations · Magnakom

`November 2025 - Present` · Los Angeles, CA

- Design and build internal full-stack applications with Python/FastAPI backends and React, TypeScript, Next.js, or Streamlit interfaces.
- Develop and maintain integrations across 7+ commerce and operations platforms, including Walmart, Mercado Libre, Temu, Falabella, ShipStation, ChannelMax, SellerCloud, and WholeCell.
- Automate order reconciliation, inventory synchronization, shipping labels, cancellations, repricing, returns, and multi-source reporting workflows.
- Built more than eight business automations that reduced repetitive processes from 1–2 hours to minutes.
- Apply OpenAI APIs, computer vision, and document-processing pipelines to extract unstructured data, classify business records, match products, and generate operational spreadsheets.
- Improve reliability with OAuth and signed-request authentication, concurrent API processing, validation, retries, rate limiting, structured logging, and failure alerts.

#### Selected Private Projects

> These are internal projects, so the source code and business data are not public. The descriptions focus on my engineering contributions and omit confidential implementation details.

**Multi-Marketplace Operations Platform**  
Built Python integrations connecting marketplace, ERP, shipping, and inventory systems. The tools import and reconcile orders, prevent duplicate creation, synchronize stock concurrently by SKU, process cancellations and payment updates, download shipping labels, update tracking, and generate audit-ready Excel reports across multiple sales channels.

`Python` `FastAPI` `REST APIs` `OAuth` `Streamlit` `Pandas` `Excel` `Concurrency` `Slack Alerts`

**AI-Assisted RMA Management Application**  
Developed a full-stack application with a React/TypeScript frontend and FastAPI backend for importing vendor workbooks and maintaining a returns tracker. Integrated Gmail, Google Sheets, and OpenAI to analyze email threads, classify RMA stages, match records by normalized identifiers, flag uncertain cases for human review, and keep operational statuses synchronized.

`React` `TypeScript` `FastAPI` `Python` `OpenAI` `Gmail API` `Google Sheets API`

**AI Document & Spreadsheet Processing**  
Created Python applications that extract invoice and packing-slip data from PDFs, use structured OpenAI outputs to identify products and prices, match results to device records, preserve spreadsheet formatting, and return downloadable workbooks. Supported phone, tablet, and Mac parsing with configurable columns and manual-review paths.

`Python` `FastAPI` `OpenAI` `Pandas` `OpenPyXL` `PDFPlumber` `Streamlit`

**Intelligent PDF Logo Placement Tool**  
Developed a computer-vision pipeline that renders each PDF page, detects occupied content, finds the largest safe empty region, and inserts a proportionally scaled logo without covering text. Built an interactive interface for logo size, alignment, offsets, white-space sensitivity, and safety margins, with downloadable processed PDFs.

`Python` `OpenCV` `NumPy` `PyMuPDF` `Pillow` `Streamlit`

**Barcode Inventory Lookup Application**  
Created and packaged a Windows desktop application that accepts barcode-scanner input, validates an SFIR identifier against a Google Sheets-backed dataset, and returns its matching ESN. Added live database reloads, input validation, clear operator states, and deployment documentation for nontechnical users.

`Python` `Google Sheets API` `Google Auth` `PyInstaller` `Windows Desktop`

**Internal Operations Portal**  
Built a responsive Next.js dashboard that organizes internal printing, inventory, cancellation, reporting, repricing, product-processing, and RMA tools into a single categorized interface for operations teams.

`Next.js` `React` `TypeScript` `Tailwind CSS`

### Software Engineer I · Hire Henry

`March 2025 - Present`

- Enhanced and debugged a Flutter application across desktop and mobile layouts.
- Built site-saving workflows with custom names and real-time dashboard updates backed by Firebase Firestore.
- Integrated Google Maps and WebSockets to render location and telemetry data from a Python backend.
- Implemented Firebase Authentication and backend logic for latitude, longitude, orientation, and other site attributes.
- Deployed the Flutter web application to AWS EC2 and documented the codebase for developer onboarding.

### Undergraduate Student Researcher · The Quantum Light-Matter Cooperative

`October 2024 - Present`

- Customize WordPress experiences with HTML, CSS, themes, and interactive media.
- Developed a Python scraper that keeps the research-publications page current automatically.
- Contribute to an interactive live-tour experience designed to make the research more accessible to visitors.

## Research Experience

### Engineer Intern · NASA Jet Propulsion Laboratory

`June 2025 - August 2025` · Pasadena, CA

- Advanced the EZIE Observing System Simulation Experiment with an end-to-end Python pipeline spanning raw-data screening, atmospheric modeling, radiative-transfer simulation, and geophysical retrieval.
- Combined IGRF, NRLMSIS, and MERRA-2 datasets into physically consistent atmospheric and magnetic-field products using interpolation, multiprocessing, and lazy-loaded xarray workflows.
- Reduced a four-radiometer radiative-transfer simulation from approximately **207 seconds to 41 seconds** through parallelization and multiprocessing.
- Reduced polarization-alignment processing from approximately **5 minutes to 31 seconds** using vectorization and targeted filtering.
- Developed a custom Gauss-Newton retrieval framework for simultaneous magnetic-field and temperature-profile estimation.
- Applied the retrieval to **15 EZIE orbits** and validated detected magnetic perturbations against independent SuperMAG ground-magnetometer observations.

### Undergraduate Student Researcher · Structures-Computer Interaction Lab, UCLA

`September 2024 - April 2026`

- Converted a C++ soft-robotics simulator into a modular Python framework for more accessible research workflows.
- Applied discrete differential geometry to simulate elastic rods, deformable structures, material manipulation, and soft-robot control.
- Led electronics development for an agricultural robot, including motor drivers, sensor integration, PCB layouts, wiring, power management, ESP32 firmware, and NVIDIA Jetson control.
- Built LiDAR costmap pipelines that transform point clouds into 128 × 128 occupancy grids for navigation and policy learning.
- Trained PPO-based navigation policies and developed terrain-aware traversability maps from 3D SLAM point clouds.
- Optimized mapping through caching, memory reuse, reduced allocation, and adaptive updates for real-time operation.

Public research repositories: [DisMech](https://github.com/StructuresComp/dismech-rods) · [AgriCruiser](https://github.com/agri-cruiser/agri-cruiser)

## Featured Public Projects

| Project | What I Built | Technologies |
| --- | --- | --- |
| [AStar Flashcards](https://github.com/Shoheicode/Project-4-AI-Flashcards) | AI-assisted study application for generating and managing flashcards. | React, OpenAI API, Firebase |
| [AStar Rate My Professor](https://github.com/Shoheicode/Project-5--AI-Rate-My-Professor) | RAG application that scrapes professor data, stores embeddings in Pinecone, and answers natural-language questions. | Next.js, OpenAI, Pinecone, web scraping |
| [AStar Customer Support AI](https://github.com/Shoheicode/Project-3-AI-Customer-Support) | AI-assisted customer-support interface built during the Headstarter fellowship. | React, Next.js, OpenAI API |
| [Bank Management](https://github.com/Shoheicode/BankManagement) | Banking application demonstrating C++ object-oriented design and data management. | C++ |
| [Personal Website](https://github.com/Shoheicode/Personal-Website) | Responsive portfolio for presenting my experience and projects. | Flutter, Firebase |

## Technical Skills

**Backend & APIs**  
Python · FastAPI · REST APIs · WebSockets · Node.js · OAuth · OpenAI APIs

**Data, Automation & Scientific Computing**  
Pandas · NumPy · xarray · MATLAB · PDF processing · Web scraping · Multiprocessing · Data pipelines

**Frontend & Mobile**  
React · Next.js · Flutter · React Native · Streamlit · HTML · CSS · JavaScript

**Robotics & Simulation**  
C++ · NVIDIA Jetson · ESP32 · LiDAR · SLAM · Isaac Sim · Reinforcement Learning · Unity

**Cloud & Tools**  
AWS EC2 · Firebase · Git · GitHub · Google Cloud APIs · PyInstaller

## Leadership & Earlier Experience

- **Software Engineering Fellow, Headstarter AI** — Built and deployed five AI projects in five weeks; ranked in the 87th percentile among more than 3,000 participants.
- **Head Tech Lead, Google Developer Student Club at El Camino College** — Led technical exploration and helped teams build Flutter, Firebase, Google API, and TensorFlow projects.
- **Code Lead Sensei, Code Ninjas** — Taught programming, adapted lessons to individual learners, and contributed to code-review discussions.
- **Mathematics/CS Tutor, El Camino College** — Taught calculus, multivariable mathematics, and computer science with a reported 95% student-success rate.

## More Projects

<details>
<summary><strong>Web, Mobile & AI</strong></summary>

<br/>

- [AStar Fitness App](https://github.com/Shoheicode/fitness-app-project)
- [React Native Fitness App](https://github.com/Shoheicode/ReactNativefitnessapp)
- [Budget Management Website](https://github.com/Shoheicode/BudgetApp)
- [Google Developer Student Club Solution Challenge](https://github.com/El-Camino-Google-Developer-Student-Club/El-Camino-2023-Solution-Challenge)
- [CS 174 Final Project](https://cs-174-final-project.vercel.app/)

</details>

<details>
<summary><strong>C++, Data Structures & Algorithms</strong></summary>

<br/>

- [Ice Man](https://github.com/Shoheicode/CS30-ICEMAN)
- [Map Project](https://github.com/Shoheicode/CodeProjects/blob/main/C++%20Projects/MapProject/Readme.md)
- [CS 20A Projects](https://github.com/Shoheicode/CS20A-Class-Projects)
- [Coursera Data Structures & Algorithms](https://github.com/Shoheicode/CourseraProjects)

</details>

<details>
<summary><strong>Game Development</strong></summary>

<br/>

- [Simple Platforming Game](https://github.com/Shoheicode/PlatformingGame)

</details>

## Let's Connect

I'm interested in backend engineering, API development, automation, applied AI, and scientific-software opportunities.

- 🌐 [Portfolio](https://portfoliowebsite-36391.web.app/)
- 💼 [LinkedIn](https://www.linkedin.com/in/jason-irie-2bb2b0243/)
- 💻 [GitHub](https://github.com/Shoheicode)
