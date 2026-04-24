<div align="center">
  <img src="assets/gojo-banner.png" alt="Satoru Gojo Banner" width="100%" />
  <br />
  <br />
  <h1>Hi, I'm Afzal Ansari 👋</h1>
  <h3>Software Engineer & Lead Developer</h3>
  <p><i>Building high-performance backend architectures and system-level applications.</i></p>
</div>

<br />

I'm a Software Engineer who loves building fast, scalable backend systems. Right now, I'm leading the development of a few complex platforms from the ground up—handling everything from initial system design to final production. When I'm not architecting APIs, you'll find me sharpening my problem-solving skills by mastering Data Structures & Algorithms in C++. 

<hr/>

<p><img src="https://media.giphy.com/media/QVz8bVdhi6dmkIkg61/giphy.gif" width="40" align="absmiddle" /> <b>Tech Stack & Skills</b></p>

<div align="center">

| **Category** | **Technologies** |
| :--- | :--- |
| **Languages** | ![C++](https://img.shields.io/badge/C++-%2300599C.svg?style=flat&logo=c%2B%2B&logoColor=white) ![Strict TypeScript](https://img.shields.io/badge/Strict_TypeScript-%23007ACC.svg?style=flat&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E) ![SQL](https://img.shields.io/badge/sql-%23003B57.svg?style=flat&logo=postgresql&logoColor=white) |
| **Runtimes & ORMs**| ![Bun](https://img.shields.io/badge/Bun-%23000000.svg?style=flat&logo=bun&logoColor=white) ![Drizzle ORM](https://img.shields.io/badge/drizzle-C5F74F?style=flat&logo=drizzle&logoColor=black) |
| **Backend** | ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=flat&logo=node.js&logoColor=white) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=flat&logo=express&logoColor=%2361DAFB) ![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=flat&logo=redis&logoColor=white) |
| **Database** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=flat&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=flat&logo=mongodb&logoColor=white) |
| **Frontend** | ![React](https://img.shields.io/badge/react-%2320232a.svg?style=flat&logo=react&logoColor=%2361DAFB) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=flat&logo=tailwind-css&logoColor=white) ![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=flat&logo=bootstrap&logoColor=white) |
| **Tools & Env** | ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat&logo=docker&logoColor=white) ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat&logo=ubuntu&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat&logo=git&logoColor=white) ![WebStorm](https://img.shields.io/badge/WebStorm-000000?style=flat&logo=WebStorm&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white) |

</div>

<hr/>

<p><img src="assets/GojoFingerGuns.png" alt="Cat GIF" width="35"><b> Engineering Focus & Recent Architecture</b></p>

### **[Writespace (Content Engine & Social Platform)](https://github.com/afzal14786/writespace)**
> *Lead Developer • Highly Scalable Microservice Architecture*

A production-ready backend engine designed for a high-concurrency social blogging platform. Built with a focus on strict type safety, asynchronous processing, and robust security middleware (including custom bot interception).

* **Tech Stack:** Strict TypeScript, Node.js, Express, PostgreSQL, Drizzle ORM, Redis, BullMQ.
* **Architecture Highlights:**
    * **Advanced Authentication:** JWT access/refresh token rotation & secure OTP email verification.
    * **Decoupled Async Processing:** Dedicated BullMQ/Redis worker threads handling email distribution, media processing, and interaction queues without blocking the main event loop.
    * **Security & Performance:** Custom bot-interceptor middleware, Redis-backed rate limiting, and HTTP request logging.
    * **Relational Data Modeling:** Highly normalized PostgreSQL schema handling complex relationships (posts, hierarchical comments, likes, shares, and follows) strictly typed via Drizzle ORM.

### **[Reshma (Core E-Commerce Backend)](#)**
> *Lead Developer • B2C E-Commerce Platform*

The core architectural backbone for a high-traffic B2C e-commerce platform. Engineered to handle a highly dynamic product catalog, secure payment lifecycles, and advanced user role management.

* **Tech Stack:** Strict TypeScript, Node.js, Express, MongoDB (Mongoose), Redis, Cloudinary.
* **Architecture Highlights:**
    * **Polymorphic Product Catalog:** Complex data modeling to support diverse inventory types (Apparel, Bangles, Fabrics, Innerwear, Accessories) under a unified system.
    * **Multi-Layer Security:** Role-Based Access Control (RBAC) separating Admin and Public traffic, alongside Google OAuth and OTP-based authentication.
    * **Media & CDN Integration:** Automated media uploads, optimization, and delivery via Cloudinary.
    * **Performance Optimization:** Redis caching layers for catalog retrieval and session state management.

### **[DSA Preparation Repository](https://github.com/afzal14786/dsa-prep)**
> *Daily Mastery & Problem Solving*

A comprehensive, actively maintained collection of Data Structures and Algorithms solutions implemented in **C++**. This repository documents my mastery of core CS concepts and advanced competitive programming patterns.

* **Topics Covered:** Graph Algorithms (Dijkstra, Prim's), Dynamic Programming, Trees (AVL, BST), Tries, and Linked Lists.
* **Core Patterns:** Sliding Window, Two Pointers, Backtracking, and Bit Manipulation.

<hr/>

## Additional Engineering Projects

<details>
  <summary><b>Full-Stack Portfolio & Headless CMS (Backend API)</b></summary>
  <br>
  <p>A custom headless content management system and API engineered to serve personal portfolio data and blog content. Development prioritized secure content delivery and modular architecture, decoupling the data layer from the presentation layer.</p>
  
  **Technical Highlights:** Implemented robust JWT authentication, integrated Redis caching layers for optimized API response times, and utilized Cloudinary for scalable media management.
  <br>
  **Tech Stack:** Node.js, Express, MongoDB, Redis, Cloudinary.
  <br><br>
  <a href="https://github.com/afzal14786/portfolio-backend" target="_blank">View Source</a>
</details>

<details>
  <summary><b>Portfolio Client & Admin Dashboard</b></summary>
  <br>
  <p>A decoupled frontend ecosystem consisting of a highly optimized public-facing portfolio interface and a secure administrative dashboard. Built with strict typing to ensure runtime safety and maintainability across complex state management flows.</p>
  
  **Technical Highlights:** The admin dashboard features comprehensive content management tools, including a custom rich text editor for blogging, profile analytics visualization, and protected routing.
  <br>
  **Tech Stack:** React, TypeScript, Vite, Tailwind CSS.
  <br><br>
  <a href="https://github.com/afzal14786/portfolio-frontend" target="_blank">View Client Source</a> | <a href="https://github.com/afzal14786/portfolio-dashboard" target="_blank">View Admin Source</a>
</details>

<details>
  <summary><b>FinVista (Financial Technology Platform)</b></summary>
  <br>
  <em>Aug 2025 - Sept 2025</em>
  <p>A comprehensive financial technology web application designed with a focus on high-performance rendering and secure user sessions. Engineered to demonstrate complex full-stack integration, advanced state management, and multi-layered authentication architectures.</p>
  
  **Tech Stack:** ReactJS, Tailwind CSS, Node.js, Express, MongoDB, Redis, Firebase Auth.
  <br><br>
  <a href="https://finvista-trading-frontend.onrender.com/" target="_blank">View Live</a> | <a href="https://github.com/Afzal14786/Trading-Platform" target="_blank">View Source</a>
</details>

<details>
  <summary><b>FinVista Analytics Dashboard</b></summary>
  <br>
  <em>Aug 2025 - Sept 2025</em>
  <p>A highly interactive analytics dashboard built to process and visualize financial market data. Development focused on optimized DOM rendering for real-time data updates and building modular, reusable data visualization components.</p>
  
  **Tech Stack:** ReactJS, Chart.js, Node.js, Express, MongoDB, Redis.
  <br><br>
  <a href="https://finvista-trading-dashboard.onrender.com/" target="_blank">View Live</a> | <a href="https://github.com/Afzal14786/trading-dashboard" target="_blank">View Source</a>
</details>

<details>
  <summary><b>Vacation Rental Marketplace (Airbnb Clone)</b></summary>
  <br>
  <em>Apr 2025</em>
  <p>A full-stack marketplace application implementing robust RESTful architecture. Development focused on scalable database schema design, secure token-based authentication, and handling complex data queries within a NoSQL environment.</p>
  
  **Tech Stack:** MongoDB, Express, React, Node.js.
  <br><br>
  <a href="https://github.com/Afzal14786/Airbnb" target="_blank">View Source</a>
</details>

<hr/>

## Problem Solving & Algorithms Progress

| LeetCode Mastery | GeeksForGeeks Mastery |
| :---: | :---: |
| <a href="https://leetcode.com/0x4f5a4c"><img src="https://leetcard.jacoblin.cool/0x4f5a4c?ext=heatmap" alt="LeetCode Stats" /></a> | <a href="https://geeksforgeeks.org/user/iamafzal/"><img src="https://gfgstatscard.vercel.app/iamafzal?theme=dark" alt="GFG Stats" /></a> |

<hr/>

## Certifications & Professional Training

| Credential & Focus Area | Issuing Organization | Verification |
| :--- | :--- | :--- |
| **Data Structures & Algorithms with C++** <br> *Focus: Advanced Problem Solving & Core CS Concepts* | **Apna College** | [View Credential](https://iamafzal-dev.vercel.app/me) |
| **Full Stack Development (MERN)** <br> *Focus: End-to-End Web Application Architecture* | **Apna College** | [View Credential](https://iamafzal-dev.vercel.app/me) |
| **Mastering Data Structures & Algorithms (C/C++)** <br> *Instructor: Abdul Bari* | **Udemy** | [View Credential](https://iamafzal-dev.vercel.app/me) |

<br/>

## Academic Background

| Degree / Level | Institution | Timeline | Academic Score |
| :--- | :--- | :--- | :--- |
| **Bachelor of Computer Applications (BCA)** | Indira Gandhi National Open University | *Jan 2023 - Final Year* | - |
| **Higher Secondary (12th)** | T.N.B College Bhagalpur, Bihar | *2020 - 2022* | **81.40%** |
| **Secondary School (10th)** | S.S. High School Mal Mandro | *2018 - 2020* | **91.40%** |

<hr/>

<h3>
  <img src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNGtjNHp5a3BtYW1saXFyODUycjdjNHJ2OTRvdGJlY2tpbGk3amhrNSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/wkW0maGDN1eSc/giphy.gif"
       width="24" align="absmiddle" alt="pulse" />
  &nbsp;Engineering Metrics & GitHub Activity :
</h3>

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Afzal14786&theme=dark" alt="GitHub Profile Summary" />
  <br />

  <a href="https://github.com/Afzal14786">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=Afzal14786&theme=tokyonight&hide_border=true&background=0D1117" alt="GitHub Streak Graph" height="165" />
  </a>
  <a href="https://github.com/Afzal14786">
    <img src="https://github-readme-stats-tau-nine-81.vercel.app/api/top-langs/?username=Afzal14786&layout=compact&title_color=cba6f7&theme=tokyonight&border_color=45475a&hide_border=true" alt="Top Languages Used" height="165" />
  </a>
</div>

<hr/>

 <h2><img src="https://media.giphy.com/media/Al9XitEIwGgLU9yMfS/giphy.gif?cid=ecf05e47246z68gic13exguovr5xae6jhotnfa5nmu0evi54&ep=v1_stickers_search&rid=giphy.gif&ct=s" width="60" align="absmiddle"> Professional Links & Contact</h2>
 
<div align="center">
  <p><i>Always open to discussing system architecture, backend engineering, and new opportunities.</i></p>

  <a href="https://iamafzal-dev.vercel.app"><img src="https://img.shields.io/badge/Portfolio-%23000000.svg?style=flat&logo=vercel&logoColor=white" alt="Portfolio"></a>
  <a href="mailto:mdafzal14777@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white" alt="Gmail"></a>
  <a href="https://linkedin.com/in/0x4f5a4c"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://twitter.com/0x4f5a4c"><img src="https://img.shields.io/badge/X-(Twitter)-%23000000.svg?style=flat&logo=X&logoColor=white" alt="X/Twitter"></a>
  <br><br>
  <a href="https://leetcode.com/0x4f5a4c"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat&logo=leetcode&logoColor=white" alt="LeetCode"></a>
  <a href="https://geeksforgeeks.org/user/iamafzal/"><img src="https://img.shields.io/badge/GeeksforGeeks-298D46?style=flat&logo=geeksforgeeks&logoColor=white" alt="GFG"></a>
  <a href="https://discord.gg/mdafzal14786"><img src="https://img.shields.io/badge/Discord-%237289DA.svg?style=flat&logo=discord&logoColor=white" alt="Discord"></a>
  </div>

<hr/>

<div align="center">
  <h2><b>Visitor Count</b></h2>
  <img src="https://count.getloli.com/@Afzal14786?theme=booru-huggboo" alt="Md Afzal" />
</div>
