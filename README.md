## Hi, I'm Film 👋

CS student at Thammasat University who started in full-stack and drifted toward the infrastructure side: servers, Kubernetes, and making deployments boring.

- ☸️ DevOps researcher at **TonKit Lab**, working on the Virtual Lab platform
- 🛠️ Freelance full-stack & DevOps for small businesses
- 🌱 Looking for a Software Engineering / DevOps internship
- 🥈 2nd place, Sony Smart Factory Hackathon 2025

> 🔒 Most of what I build is freelance client work in private repos, so this page is quieter than my commit history.

### What I've been working on

| Project | What I did | Stack |
|---|---|---|
| [**Virtual Lab**](https://github.com/NawapatThumthaisong97/VirtualLabtest)<br>*TonKit Lab* | • Zero Trust remote access: Ansible-provisioned Cloudflare Tunnel pods on K3s behind NGINX Ingress, with no cluster ports exposed<br>• 4-stage image-scan workflow (Fetch, Validate, Scan, Publish) using Init Containers and a custom reconciler, running Trivy and Skopeo in a read-only, non-root image<br>• Registry sync to AWS ECR with immutable tags and restricted IAM, driven by Ansible and systemd timers | K3s · Ansible · NGINX · Trivy · Skopeo · FastAPI · AWS ECR |
| **The Zins Beauty & Spa** 🔒<br>*Freelance* | • Internal management system for real-time stock and course tracking across 3 branches<br>• Session auth with HTTP-only, Secure, SameSite cookies and role-based access between Admin and branch staff<br>• GORM-backed database handling concurrent stock deductions; hardened DigitalOcean VPS behind a reverse proxy | React (Vite) · Go Fiber · GORM · DigitalOcean |
| **Ploy Fresh Fruit** 🔒<br>*Freelance* · [live site](https://ployfreshfruit.com) | • E-commerce and order management with a custom admin dashboard and customizable fruit baskets<br>• LINE Rich Menu for payment-slip approval and real-time delivery tracking<br>• GitHub Actions CI/CD, Docker, and a VPS secured with Nginx and Certbot | Next.js · Express · PostgreSQL · Docker · GitHub Actions |
| **Realmed Store** 🔒<br>*Freelance* | • Warehouse system for a medical equipment and pharmacy supplier, with full ownership of the backend database design<br>• JWT and Bcrypt auth with HTTP-only, Secure, SameSite cookies<br>• CRUD APIs and an email-based password recovery flow for staff | React · Express · MongoDB |
| [**cloudflare-r2-event-driven-pipeline**](https://github.com/PanupongFilm/cloudflare-r2-event-driven-pipeline) | • Event-driven upload pipeline on Cloudflare R2, Queues and Workers<br>• Decouples the upload trigger from the main backend so instructor requests are handled asynchronously, before workloads are routed to Kubernetes | Go · Cloudflare R2 · Queues · Workers |
| [**Inventory Management LIFF**](https://github.com/PanupongFilm/inventory-management-liff)<br>*Family business* | • LINE Official Account for my family's water shop, with a Rich Menu for adding orders, sales summary, and product and order management<br>• Profit report for any date range; each order snapshots cost, price and promotion at sale time, so past profit stays correct when prices change | Next.js · TypeScript · Prisma · PostgreSQL · LINE LIFF · Rich Menu |

🔒 = private client repo

### Tech I use

<img src="https://skillicons.dev/icons?i=kubernetes,docker,ansible,terraform,aws,cloudflare,githubactions,nginx,linux,go,python,fastapi,ts,express,react,nextjs,postgres,mongodb&perline=9" width="100%" />

### Award

<img src="assets/sony-smart-factory-hackathon-2025-banner.jpg" width="360" align="left" alt="Sony Smart Factory Hackathon 2025, 2nd place banner and trophy" />

**2nd place, Sony Smart Factory Hackathon 2025** 🥈

Built a real-time manufacturing anomaly dashboard that tracks live machine operations and material waste, using WebSockets with an Express.js and FastAPI backend.

<br clear="left" />

### Certifications

<img src="assets/aws-cloud-foundations.png" width="32%" alt="AWS Academy Cloud Foundations" /> <img src="assets/aws-cloud-architecting.png" width="32%" alt="AWS Academy Cloud Architecting" /> <img src="assets/aws-cloud-web-application-builder.png" width="32%" alt="AWS Academy Cloud Web Application Builder" />

### Elsewhere

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/panupong-suthikasem-327695383)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:panupong.suttikasem@gmail.com)
