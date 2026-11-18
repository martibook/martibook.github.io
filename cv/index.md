---
layout: cv
title: LU jiyan – CV
full_name: LU jiyan
email: martinahill@outlook.com
website: martibook.github.io
pdf: cv_LUjiyan.pdf
---

<!--
HOW TO EDIT
- "## Title" starts a section (Experience, Projects, ...).
- "### Title | Date" starts an entry. The text after the last " | " is shown on the right.
- A plain line right under "###" is a sub-line (e.g. the company name).
- "- text" is a bullet point. **bold**, *italic*.
When you merge your change to main, the PDF is rebuilt automatically.
-->

## Experience

### Microsoft AI, *Member of Technical Staff* | Jun 2026 – Present
- Reorg to the Microsoft AI team in Redmond, US

### Microsoft, *Member of Technical Staff* | Dec 2025 – Jun 2026
- Transferred to the Microsoft Copilot Platform Core team in Redmond, US

### Microsoft, *Software Engineer 2* | Mar 2021 – Dec 2025
- Developing AI-Powered applications and embedded cross-device experiences
- Spot Award for excellent work performance in 2022
- Shared Patent *Cross-Device Data Transfer Based On A Request-Responding Model* (MS#412283-CN-NP) in 2022

### Naturali – a startup, *Developer* | Aug 2018 – Feb 2021
- Developed a customized version control system for a conversational ChatBots building platform, details in Projects
- Data scraping

### Shenzhen Institutes of Advanced Technology, Chinese Academy of Sciences, *Intern* | Aug 2017 – Dec 2017
- Visualized the distribution of mobile traffic within commercial areas and uncovered business insights via data mining

### Physical Lab of Northwestern Polytechnical University, *Research Assistant* | Feb 2017 – Jun 2017
- Created Matlab GUI to support friendly user interaction for the program *Digital Holographic Interferometer for Acquiring 3D Dynamic Information*

### New Oriental Education & Training, *Teaching Assistant* | Jan 2017 – Mar 2017
- Served as a teaching assistant of English training class in high school section
- Best Creativity Award for my work

## Education

### B.S. in Software Engineering, *Northwestern Polytechnical University (NPU), Xi'an, China* | 2014 – 2018
- Score: 84/100

### Computer Science and Information Engineering, *National Taiwan Normal University, Taipei, Taiwan* | Feb – Jul 2016
- GPA: 4.14/4.3

### Computer Science, *University of Oulu, Oulu, Finland* | Feb – Aug 2018
- Grade: 4/5

**Competitions** (Mathematical Contest in Modeling): The Outstanding Winner of the university in 2016 · The Honorable Mention of Shaanxi Province in 2016

**Publications:** Lu Jiyan, Panos Kostakos, Mourad Oussalah and Susanna Pirttikangas. *SemanPhone: Combining Semantic and Phonetic Word Association in Verbal Learning Context*. 2018 IEEE/ACM International Conference on Advances in Social Networks Analysis and Mining (ASONAM). doi:10.1109/ASONAM.2018.8508827

## Skills

- **Programming:** C#, Golang, Python, C/C++, Kotlin, TypeScript/JavaScript, Java, Racket, HTML+CSS, Bash, Matlab, LaTeX, SQL
- **Algorithms:** Sorting (Merge, Quick, Heap), Binary Search, DFS, BFS, Dynamic Programming, Graphs (Dijkstra's, Bellman-Ford)
- **Tools:** Git, Vim, CLI tools, Visual Studio, Android Studio, IntelliJ IDEA, Docker, Postman, Swagger, Wireshark, JMeter
- **Technologies:** RESTful, WebSocket, SignalR, WebRTC, gRPC, ASP.NET, Gin, Flask, React, Vue, MySQL, PostgreSQL, MongoDB, Azure

## Projects

### Paloma – MAI Agentic Platform | 2026
Microsoft
- **Goal:** Let anyone in the org hand work to cloud agents from Slack, GitHub, Linear, etc.
- I made agents work natively in Slack across workspaces by building a full Slack toolset, from reading and searching conversations to tagging and direct-messaging people, sharing files and editing canvases. I designed access bundles, a global permission control for what each agent can reach. Then I built code channels: dedicated Slack channels where an agent takes a request all the way to a merged pull request.
- I improved reliability by stopping endless retry loops, recovering stuck agents and alerting on failures, and improved performance by replacing database scans with indexes and cutting agent build time.
- I made the platform clean up and improve itself: it deletes stale data so storage does not grow without limit, and nightly agents find problems in its own code, then fix them through reviewed pull requests.

### MAI Playground | 2026
Microsoft
- **Goal:** Build the internal playground where org members try MAI models, and turn their usage into training and evaluation data.
- **Features:** As an AI-native engineer, I became the main owner of an unfamiliar codebase in two months and closed 144 issues. I turned vague requirements into clear workflows by studying how users work and confirming early with prototype videos, such as letting safety testers flag a model's bad replies and send the conversation to training data in one step.
- **Performance:** I replaced per-action calls to the training data store with timed batch uploads, cutting traffic by a large factor. I led the cross-team alignment that had long blocked this fix.
- **Productivity:** I automated daily Slack feedback triage with a scheduled agent that files clear, deduplicated issues linked to their source threads.

### Scheduled Task in Microsoft Copilot | 2026
Microsoft
- **Goal:** Enable users to automate actions in Microsoft Copilot through one-time and recurring scheduled tasks.
- As the feature DRI, I led the architecture and end-to-end direction of the scheduled task system from inception. I defined the execution model, aligned cross-team partners, and drove the feature to launch under tight timelines.
- As an IC, I implemented the core backend—including schedule creation, execution orchestration, and integration with the underlying scheduler service. To ensure reliability at scale, I introduced jitter, rate limiting, and auto-pausing. I also solved complex challenges such as user-context propagation and feature-flag behavior for triggered tasks.

### Platform Core Engineering in Microsoft Copilot – Extensibility | 2025
Microsoft
- **Goal:** Strengthen the core platform foundation's extensibility, maintainability, and cross-service integration.
- A major effort involved migrating agent tools into standalone projects to improve modularity and long-term maintainability. This work enabled broader tool reuse across services and simplified ownership for tool teams. I handled multiple complex migrations, collaborating with teammates to deliver this large-scale refactor.
- I also fully implemented the service-side infrastructure for Service Command, a unified communication mechanism between server and clients that supports multi-turn interactions.

### Build Creator Gallery in Microsoft Copilot | 2025
Microsoft
- **Goal:** Enable a public gallery of creative works in Microsoft Copilot where users can view and remix content.
- I designed and implemented a secure admin portal for gallery item management, enabling browsing, creation, editing, and review of items with access control to ensure authorized usage. This portal streamlined content management and maintained quality standards. Additionally, I initiated the project by building the underlying service code from scratch, laying the foundation for the full gallery feature development.

### Build Sharing Feature in Microsoft Copilot | 2025
Microsoft
- **Goal:** Enable a reusable sharing framework in Microsoft Copilot.
- I co-designed and co-implemented a modular sharing framework that allows multiple features to integrate consistent sharing. Migrated existing implementations to the new framework, ensuring maintainability and scalability. Partnered with other teams to onboard their features onto the framework and provided ongoing support. Additionally, I improved the success rate of customized social preview generation for conversation sharing by 20%, enhancing user engagement and share quality.

### Build Quiz Card in Microsoft Copilot | 2025
Microsoft
- **Goal:** Enable an interactive quiz card in conversations within Microsoft Copilot.
- I led the design and evaluation of the core prompt driving quiz card generation, a key component of the feature, including LaTeX support that added significant complexity. Enhanced the quiz card parsing logic, reducing the error rate by 4%.

### Embed Generative AI Capabilities into Android OS | 2023 – 2024
Microsoft
- **Goal:** Integrate generative AI capabilities into the Android operating system.
- I explored AI capability options by evaluating frameworks and building quick prototypes to guide decision-making. I developed phone plugins for managing contact information, created a testing tool to streamline validation. Through collaboration with the Bing Chat Backend team, my work on citation utilities and dynamic prompt leakage filtration was integrated into their system, which powers Bing Chat and co-pilot applications used by millions daily.

### Messages in Microsoft Teams | 2022
Microsoft
- **Goal:** Enable Microsoft Teams users to send and receive SMS messages on their Android phones.
- I developed a push API that allowed phones to notify the Teams app about incoming SMS messages. This involved collaborating with various teams that owned different components. Additionally, to address delays caused by partner teams, I temporarily simulated unfinished components which helped expedite feature testing.

### Cross-Device Data Transfer | 2021 – 2022
Microsoft
- **Goal:** Provide a set of RESTful-style APIs that can be used to fetch device data from anywhere.
- I played a major role in developing a crucial transport service for a microservices architecture. As part of this, I revised a transportation protocol between the transport service and LinkToWindows on phones. I analyzed new requirements for the LinkToWindows side and communicated with the cross-geographical team to ensure success. I implemented some layers and features of the protocol, such as continuous chunk responses, shared connection management. To enhance the service's concurrency, I delved into advanced C# asynchronous programming techniques. Lastly, I ensured good debuggability by defining reasonable and helpful telemetry events.

### Conversational User Interface for Building Conversation ChatBot | 2019 – 2020
Naturali
- **Goal:** Create a platform and set of APIs that customer developers can use to build ChatBots, and create a ChatBot community similar to GitHub.
- As a developer for the ChatBot building platform, I created a version control system in the backend service to enhance collaboration among customer developers. To enable submission of pull requests to the main ChatBot version for reviewing changes, I implemented differentiating and merging versions. To facilitate the importation of ChatBot components from public libraries, I implemented referencing or forking a ChatBot component. To accommodate the creation of template ChatBots for various languages, I implemented partitioning and consolidating language-specific and non-language-specific aspects of ChatBot development. I made an informed decision on a fundamental storage strategy that ultimately proved superior in both development simplicity and overall performance.

### Data Scraping | 2018
Naturali
- **Goal:** Build automatic pipeline to collect large volume various types of data for model training purposes.
- Initially, I determined the data sources to gather based on the data requirements, e.g. QQ Music. Next, I analyzed the XHR requests made to the data source and customized a Python web crawling script to retrieve information. Also I maintained and improved performance of the overall scraping framework continuously.
