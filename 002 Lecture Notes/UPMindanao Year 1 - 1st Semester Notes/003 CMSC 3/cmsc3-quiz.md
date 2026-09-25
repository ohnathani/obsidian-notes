# CMSC 3 Complete Quiz Cheatsheet

## Related notes

- [[2026-08-26 History of the Internet]]
- [[2026-08-28 Evolution of Websites]]

---

## 1. Core Web Design Principles & Planning

### 16 Core Web Design Principles
1. **User-Centric Design**: Understand user needs, preferences, and behaviors to create a site meeting their expectations [1].
2. **Responsive Design**: Ensure layout adapts seamlessly to different screen sizes and devices (mobile, tablet, desktop) [1, 2].
3. **Mobile-First Approach**: Design for small mobile screens first, then progressively enhance for larger displays [2].
4. **Usability & UX**: Provide a user-friendly interface with intuitive navigation and readable content to keep visitors engaged [2].
5. **Performance Optimization**: Minimize page load times by compressing images, minifying scripts, and reducing HTTP assets [2, 3].
6. **Content Quality**: Provide relevant, well-organized, up-to-date, and easy-to-understand content [3].
7. **Search Engine Optimization (SEO)**: Implement on-page and technical SEO practices (keyword research, meta tags, quality backlinks) to improve SERP visibility [3].
8. **Security**: Protect systems via SSL encryption, regular software updates, firewalls, and strong administrator authentication [3, 4].
9. **Scalability & Flexibility**: Design using flexible code and modular components to accommodate future growth and changing requirements [4].
10. **Cross-Browser Compatibility**: Ensure the site functions correctly and looks consistent across different web browsers [4].
11. **Accessibility**: Make the website accessible to all users, including individuals with disabilities [4].
12. **Testing & Quality Assurance**: Conduct thorough testing of functionality, performance, compatibility, and security prior to launch [4, 5].
13. **Feedback & Iteration**: Collect feedback from users and stakeholders to drive continuous site improvements [5].
14. **Legal & Privacy Compliance**: Comply with relevant laws and regulations, including privacy policies, terms of service, and copyright laws [5].
15. **Backup & Disaster Recovery**: Maintain procedures to recover data and restore site functionality after failures [5].
16. **Documentation & Maintenance**: Keep detailed technical documentation of site architecture, codebase, and configurations [5, 6].

---

### 13 Steps of Website Planning
> *"Failure to plan is planning to fail."* — Benjamin Franklin [8]

1. **Define Purpose & Goals**: Establish whether the site provides information, sells products, generates leads, or builds an online community [8].
2. **Identify Target Audience**: Profile user demographics, needs, preferences, and pain points to customize the design [9].
3. **Conduct Market Research / Environmental Scanning**: Identify industry trends, best practices, and competitor strengths to differentiate the site [9].
4. **Choose Domain Name & Hosting**: Select a memorable domain name (e.g., `upmin.edu.ph`) and a reliable hosting provider [9, 10].
5. **Create a Sitemap**: Outline main sections and hierarchical page structure to guide user navigation effectively [10].
6. **Wireframing & Prototyping**: Sketch basic layouts and visual wireframes to map functionality before development [10].
7. **Content Strategy**: Plan content types (text, images, videos), tone, voice, and messaging [10, 11].
8. **Design Style, Branding, Responsive Design, Accessibility & SEO**: Establish visual guidelines, responsive patterns, accessibility rules, and SEO visibility [11].
9. **Development & Testing**: Build system features and conduct comprehensive functional, performance, compatibility, and security testing [11].
10. **Launch & Promotion**: Publish the website to web servers and promote via social media, email marketing, and SEO [11].
11. **Monitoring & Maintenance**: Continuously track site performance analytics, traffic, page speed, uptime, and security updates [11, 12].
12. **Feedback & Iteration**: Collect user feedback to make iterative improvements over time [12].
13. **Legal & Privacy Compliance**: Ensure full compliance with copyright laws, terms of service, and privacy policies [12].

---

## 2. W3C Open Web Standards & Core Pillars

### The World Wide Web Consortium (W3C)
* **Founding & Structure**: Established by **Tim Berners-Lee in 1994** [16]. A public-interest non-profit organization featuring **400+ member organizations** and **12,000+ participating developers** globally [16].
* **Core Purpose**: Ensure the long-term growth of the Web by developing open standards [17].
* **4 Core Pillars**: **Security**, **Internationalization**, **Privacy**, and **Accessibility** [17].

---

### Deep Dive: The 4 Core W3C Pillars

#### A. Web Accessibility & WCAG (POUR Principles)
Web accessibility ensures web products are designed inclusively, removing communication barriers so the Web works for everyone regardless of hardware/device, software/browser, language, geographic location, or physical/cognitive abilities [17, 18, 19].

* **Disability Support**:
  * *Hearing*: Captions and transcripts for audio/video [19].
  * *Movement*: Full keyboard navigation and switch input support [19].
  * *Sight*: Image `alt` text, high contrast modes, and screen reader compatibility [19].
  * *Cognitive*: Simple, consistent navigation, plain language, and input assistance [19].

* **WCAG POUR Principles**:
  1. **Perceivable**: Provide text alternatives (`alt` text) for non-text content, multimedia time-based media (captions, transcripts, audio descriptions), and adaptable layouts that reflow without losing meaning [20, 21].
  2. **Operable**: Ensure **100% full functionality via keyboard alone** (no mouse required), clear navigation structure, and avoiding content that flashes (>3Hz) to prevent seizure risks [22, 43].
  3. **Understandable**: Maintain readable text with clear typography, predictable layout behavior, and input assistance with error messages [22, 23].
  4. **Robust**: Write valid, clean code using semantic HTML (`<header>`, `<nav>`, `<article>`, `<footer>`) to maximize compatibility with current and future assistive technologies [23, 24, 42].

#### B. Internationalization (i18n)
Designing and developing applications early in the development cycle so they adapt seamlessly to users from any culture, region, or language [25].

* **Universal Access & Language Support**: Supports over **3,866 languages**, scripts, character encodings (UTF-8), language tags, and locale sensitivity (date/time, currency, measurement units) [26, 27, 28, 29].
* **Writing Directions**:
  * **Left-to-Right (LTR)**: Most common global writing direction [27].
  * **Right-to-Left (RTL)**: Hebrew, Ancient Greek, Arabic, Persian (Farsi), Urdu, Kurdish, Pashto [27].
  * **Top-to-Bottom (TTB)**: Chinese, Mongolian, North Korea, South Korea, Japanese [27].
* **Best Practice**: Avoid hardcoding text directly into graphic images [7].

#### C. Web Security Principles
* **Authentication Factors**: Identity verification based on what you know (password), what you have (smart cards), what you are (biometrics), or Multi-Factor Authentication (OTP) [30].
* **Authorization**: Restrict user access permissions strictly to allowed resources and functionality [30].
* **Core Practices**: Client and server-side **Input Validation** (sanitizing input to prevent XSS and SQL injection), **Data Encryption** in transit (HTTPS/SSL) and at rest, Principle of **Least Privilege**, security patching, firewalls, and Intrusion Detection Systems (IDS) [31, 32, 33, 45].

#### D. Privacy & GDPR Compliance
* **Privacy Principles**: Data Protection, Transparency (clear privacy policies), **Explicit User Consent**, **Data Minimization** (collecting only necessary data; e.g., e-commerce sites must not request birthdates or SSNs), User Control (right to access, rectify, erase, or export data), Cross-Border Data Transfer rules, **Privacy by Design**, User Education, and Organizational Accountability [34, 35, 36, 37, 38].
* **GDPR (General Data Protection Regulation)**: EU regulation protecting personal data of EU residents [12, 13]. Mandates Data Breach Notifications within specified timeframes and Data Protection Impact Assessments (DPIAs) for high-risk data processing [13, 14].
* **GDPR Penalty Structure**:
  * *Less Severe Violations*: Fines up to **€10 Million** or **2%** of global annual turnover, whichever is higher [14].
  * *Severe Violations (Art. 83(5))*: Fines up to **€20 Million** or **4%** of total global turnover of the preceding fiscal year, whichever is higher [14, 15].

---

## 3. Website Architecture & Client-Server Tiers

### 3 Core Architecture Components
Website architecture defines the structural framework determining how a site functions across 3 components:
1. **Content**: Text, imagery, video, and media assets [54].
2. **Functionality**: Actions, user interactions, data processing, and business logic [54].
3. **Infrastructure**: Hardware, web servers, databases, operating systems, and networks [55].

---

### Client-Server Architectural Tiers

```
[ Presentation Layer / Client ] <---> [ Application Layer / Logic ] <---> [ Data Layer / DBMS ]
```

* **1-Tier (Monolithic)**: Presentation, business logic, and data layer reside in a single application program on one server/machine [59].
  * *Pros*: Simple to design, deploy, and test [59, 60].
  * *Cons*: Severe scalability issues, hard to modify, single point of failure [60].
* **2-Tier**: Client machine handles the Presentation Layer; Server executes Business Logic and stores the Data Layer [60].
* **3-Tier Architecture**:
  1. **Presentation Layer (Front End / UI / Client)**: Visible interface rendering HTML, CSS, JavaScript (Frameworks: React, Angular, Ember, Aurora) [61, 62].
  2. **Application Layer (Business Logic / Middle Tier)**: Application server processing rules, calculations, and logic (Languages: Java, C#, C++, Python, Ruby) [61, 63].
  3. **Data Layer (Back End / Data Tier / DBMS)**: Database Management System handling transaction processing, persistence, backups, and integrity (DBMS: MySQL, PostgreSQL, MSSQL) [61, 64].
  * *Advantages of 3-Tier*: High scalability (Transaction Processing monitors reduce DB connection overhead), technological flexibility (easy DBMS/server swap), long-term cost reduction, better match of systems to business needs, improved customer service, and competitive advantage [64, 65, 66].
* **5 Architecture Factors**: **Scalability**, **Performance**, **Security**, **Maintainability**, **Cost** [67].

---

## 4. Web Development Life Cycle (WDLC)

The WDLC provides a structured 6-phase approach to building web applications from planning to maintenance:

```
1. Planning & Analysis ➔ 2. Design ➔ 3. Development ➔ 4. Testing ➔ 5. Deployment ➔ 6. Maintenance
```

1. **Planning & Analysis**: Requirements gathering, technical and financial feasibility studies, sitemap construction, and wireframing (Goal: gain a deep understanding of the problem) [48, 49].
2. **Design**: Develop visual mockups, color palettes, typography, UI layout design, and UX prototypes [49].
3. **Development**: Select technology stack, then build Front-End code (HTML/CSS/JS), Back-End server logic, and Database schemas [49, 50].
4. **Testing & Review**:
   * *Functional Testing*: Quality Assurance (QA) testing to identify and fix coding bugs [50, 51].
   * *Non-Functional Testing*: Cross-browser compatibility, usability, performance load speed, and security vulnerability scans [51].
5. **Deployment**: Upload files to production web servers, register domain name (e.g., GoDaddy), and configure web hosting (e.g., Netlify, Vercel, Render, GitHub) [51, 52].
6. **Maintenance**: Software updates and upgrades, security patching, performance optimization (traffic, speed, uptime tracking), and technical user support [52, 53].
