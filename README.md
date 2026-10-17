<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,60:0A1F12,100:00FF41&height=200&section=header&text=imtius%40dev%3A~%24&fontSize=44&fontColor=00FF41&fontAlignY=42&desc=CSE%20student%20%C2%B7%20full%20stack%20engineer%20%C2%B7%20competitive%20programmer&descSize=15&descColor=9CA3AF&descAlignY=65" width="100%" alt="header" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=2800&pause=900&color=00FF41&center=true&vCenter=true&width=700&height=40&lines=%3E+whoami+%E2%86%92+Imtius+Ahmad;%3E+stack+%E2%86%92+Next.js+%7C+TypeScript+%7C+Node+%7C+Prisma;%3E+solving+%E2%86%92+problems+in+C%2B%2B;%3E+researching+%E2%86%92+medical+image+segmentation;%3E+status+%E2%86%92+shipping+code+and+learning+fast" alt="typing" />

<br/>

![Status](https://img.shields.io/badge/status-open_to_work-00FF41?style=flat-square&labelColor=0D1117)
![Location](https://img.shields.io/badge/location-Bangladesh-00FF41?style=flat-square&labelColor=0D1117)
![Focus](https://img.shields.io/badge/focus-backend_%2B_full_stack-00FF41?style=flat-square&labelColor=0D1117)
![Learning](https://img.shields.io/badge/learning-PyTorch_%7C_DSA-00FF41?style=flat-square&labelColor=0D1117)

</div>

---

## `$ whoami`

```bash
$ cat about.txt

name        : Imtius Ahmad
role        : Full Stack Developer (backend-focused)
education   : B.Sc. in CSE, Netrokona University (final semester)
languages   : TypeScript, C++, Python, JavaScript, Java
interests   : scalable web systems, computer vision, deep learning
research    : medical image segmentation (PyTorch, U-Net family)
hobby       : competitive programming on Codeforces
open_to     : full stack / backend roles, entry-level teaching roles
```

I build web applications with a focus on clean architecture, performance and maintainability: REST APIs, database design, authentication and role-based access control. Alongside that, I study computer vision and enjoy the problem-solving discipline of competitive programming.

---

## `$ ls ~/stack`

```text
frontend/   → HTML  CSS  JavaScript  TypeScript  React  Next.js  Tailwind  Redux
backend/    → Node.js  Express  Spring Boot  Firebase  REST  JWT  RBAC
database/   → PostgreSQL  MySQL  MongoDB  MariaDB  Prisma
ai-ml/      → Python  PyTorch  OpenCV  MATLAB
tools/      → Git  GitHub  Linux  Vercel  VS Code
```

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,cpp,py,java,react,nextjs,tailwind,redux,nodejs,express,spring&theme=dark" alt="languages and frameworks" /><br/>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,mariadb,prisma,firebase,pytorch,opencv,matlab,git,github,linux,vercel,vscode&theme=dark" alt="data and tools" />
</p>

```text
Next.js     ██████████████████░░  90%
TypeScript  █████████████████░░░  85%
React       █████████████████░░░  85%
Node.js     ████████████████░░░░  80%
C++ (CP)    ████████████████░░░░  80%
PostgreSQL  ███████████████░░░░░  75%
Prisma      ██████████████░░░░░░  70%
Python/ML   ████████████░░░░░░░░  60%
```

---

## `$ git log --projects`

### RentPlace &nbsp;![shipped](https://img.shields.io/badge/status-shipped-00FF41?style=flat-square&labelColor=0D1117)

A production-ready rental marketplace for Bangladesh with role-based dashboards for tenants, landlords and admins, plus Stripe Checkout payments. One monorepo holds both the Next.js frontend and the Express/Prisma REST API.

[![Live demo](https://img.shields.io/badge/live_demo-rentnest--eta.vercel.app-00FF41?style=for-the-badge&labelColor=0D1117)](https://rentnest-eta.vercel.app)

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-433E38?style=flat-square)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white)
![Express](https://img.shields.io/badge/Express-404040?style=flat-square&logo=express&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)

```text
rentplace/
├── src/        Next.js App Router frontend
├── backend/    Express + Prisma + Stripe REST API
│   ├── src/    user · properties · rentalRequest · payment · landlord · admin · review
│   └── prisma/ schema · migrations · seed
└── scripts/    API and route smoke tests
```

**Highlights**
- **Auth:** JWT access and refresh tokens in cookies with automatic single-flight refresh, and route guards that redirect users by role
- **Dashboards:** tenants track requests, pay and review; landlords manage listings and approve requests with optimistic UI; admins moderate users, properties and rentals
- **Payments:** Stripe Checkout flow with session verification on return
- **Browse:** debounced search, filters and pagination with shareable URL state
- **State:** TanStack Query for server state, Zustand for session, URL for filters
- **Deploy:** frontend and API deployed separately on Vercel from the same repo, with a same-origin `/api/*` proxy so no CORS setup is needed

### Blood Care &nbsp;![in dev](https://img.shields.io/badge/status-in_development-F59E0B?style=flat-square&labelColor=0D1117)

A platform that connects blood donors with people searching for blood, making emergency coordination faster and easier.

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

### Thesis: medical image segmentation &nbsp;![research](https://img.shields.io/badge/type-research-8B5CF6?style=flat-square&labelColor=0D1117)

Deep learning research on segmenting medical images using U-Net style architectures, built with PyTorch and trained on GPU.

---

## `$ git status`

```text
On branch main
Your branch is up to date with 'origin/imtius'.

shipped:
  ✔ RentPlace         full stack rental marketplace (live)

in progress:
  ▸ Blood Care        donor and recipient coordination platform
  ▸ Thesis            medical image segmentation with PyTorch

learning:
  ▸ PyTorch and machine learning
  ▸ Scalable backend architecture
  ▸ Data structures and algorithms

practicing:
  ▸ Competitive programming (Codeforces, C++)
```

---

## `$ ./stats --github`

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=imtius10&show_icons=true&hide_border=true&bg_color=0D1117&title_color=00FF41&text_color=9CA3AF&icon_color=00FF41&include_all_commits=true" alt="stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=imtius10&layout=compact&hide_border=true&bg_color=0D1117&title_color=00FF41&text_color=9CA3AF&langs_count=8" alt="languages" />
</p>

<p align="center">
  <img width="70%" src="https://streak-stats.demolab.com/?user=imtius10&hide_border=true&background=0D1117&ring=00FF41&fire=00FF41&currStreakLabel=00FF41&sideLabels=9CA3AF&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=6B7280" alt="streak" />
</p>

---

## `$ ping imtius`

<p align="center">
  <a href="https://github.com/imtius10"><img src="https://img.shields.io/badge/GitHub-imtius10-0D1117?style=for-the-badge&logo=github&logoColor=00FF41" alt="GitHub" /></a>
  <a href="https://www.linkedin.com/in/imtius10/"><img src="https://img.shields.io/badge/LinkedIn-imtius10-0D1117?style=for-the-badge&logo=linkedin&logoColor=00FF41" alt="LinkedIn" /></a>
  <a href="mailto:h.imtius10@gmail.com"><img src="https://img.shields.io/badge/Email-h.imtius10%40gmail.com-0D1117?style=for-the-badge&logo=gmail&logoColor=00FF41" alt="Email" /></a>
</p>

```text
64 bytes from imtius: open to collaborations, internships and teaching roles.
```

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00FF41,60:0A1F12,100:000000&height=100&section=footer" width="100%" alt="footer" />
