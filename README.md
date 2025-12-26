# UDHAYAPRAKASH J
> DevOps & Cloud Engineer • M.Tech (Software Engineering) • Automation • Serverless • SRE

Would you like me to start by generating a neon animated SVG header and an animated project metric counter for the README?

<!--
  Neon animated SVG header + animated project metric counter included below.
  You can paste this whole file into your repo's README.md.
  If you want the images hosted instead of inline, I included raw SVG sources so you can:
   - save .svg files to your repo and reference them via relative paths, OR
   - URL-encode the SVG and use a data URI (<img src="data:image/svg+xml;utf8,ENCODED_SVG">)
-->

<!-- ===== NEON / NEO HEADER (Inline SVG) ===== -->
<p align="center">
  <!-- Inline SVG neon header (copy-paste as-is). Colors: neon green / cyan on dark background -->
  <svg width="100%" height="140" viewBox="0 0 1200 140" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Udhayaprakash J neon header">
    <defs>
      <linearGradient id="g1" x1="0" x2="1">
        <stop offset="0" stop-color="#00ff99"/>
        <stop offset="1" stop-color="#00d4ff"/>
      </linearGradient>
      <filter id="f1" x="-10%" y="-30%" width="120%" height="200%">
        <feGaussianBlur stdDeviation="6" result="blur"/>
        <feMerge>
          <feMergeNode in="blur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
      <style>
        <![CDATA[
          .neonText { font-family: 'Fira Code', 'Inter', monospace; font-weight: 800; font-size:56px; fill: url(#g1); }
          .subText { font-family: 'Inter', Arial, sans-serif; font-size:18px; fill:#9debf7; opacity:0.9 }
          .glow { filter: url(#f1); }
          .blink { animation: blink 2.5s linear infinite; }
          @keyframes slideIn {
            0% { transform: translateY(40px); opacity:0 }
            80% { transform: translateY(0); opacity:1 }
            100% { transform: translateY(0); opacity:1 }
          }
          @keyframes blink {
            0% { opacity: 1; }
            50% { opacity: 0.65; }
            100% { opacity: 1; }
          }
        ]]>
      </style>
    </defs>

    <!-- dark background rounded rectangle -->
    <rect x="0" y="0" width="1200" height="140" rx="8" fill="#071019" />

    <!-- Neon main text -->
    <g transform="translate(36,48)" class="glow" style="transform-origin: left; animation: slideIn 0.9s ease-out;">
      <text class="neonText">Udhayaprakash J</text>
    </g>

    <!-- Typing-like subtext with soft glow -->
    <g transform="translate(36,102)" class="glow">
      <text class="subText">DevOps & Cloud Engineer • AWS • CI/CD • Docker • Kubernetes • Terraform</text>
    </g>

    <!-- Animated neon underline -->
    <g transform="translate(36,96)">
      <rect x="0" y="-8" width="460" height="6" rx="3" fill="url(#g1)" opacity="0.9">
        <animate attributeName="width" from="0" to="460" dur="1.1s" begin="0.2s" fill="freeze" />
      </rect>
      <!-- pulsing dot -->
      <circle cx="470" cy="-5" r="5" fill="#00ff99" class="blink" />
    </g>
  </svg>
</p>

---

## About — short & powerful
Motivated DevOps & Cloud Engineer with hands-on experience building CI/CD pipelines, containerized applications, serverless web apps, and infrastructure-as-code. Passionate about reliability, automation, and reducing manual toil.

- M.Tech (Software Engineering), VIT Chennai — 7.69 CGPA
- Internship — TMIS IT Solutions (prompt engineering for AI tools)
- Focus: AWS, Kubernetes, Terraform, Jenkins, Docker, IaC, SRE

---

## Neon / Neo Metrics Panel (Animated SVG counters)
<p align="center">
  <!-- Inline Animated Counters SVG
       Values are taken from your resume: Projects: 6, CI/CD Pipelines: 3, Serverless deployed: 2
       The numbers animate from 0 → target using SVG <animate>.
  -->
  <svg width="880" height="120" viewBox="0 0 880 120" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Project metrics">
    <defs>
      <linearGradient id="mg" x1="0" x2="1">
        <stop offset="0" stop-color="#00ff99"/>
        <stop offset="1" stop-color="#00d4ff"/>
      </linearGradient>
      <style>
        <![CDATA[
          .card { fill: #071019; stroke: rgba(0,212,255,0.06); rx:14; }
          .title { font-family: Inter, Arial, sans-serif; font-size:14px; fill:#9debf7; }
          .num { font-family: 'Fira Code', monospace; font-weight:700; font-size:36px; fill:url(#mg); }
          .label { font-family: Inter, Arial, sans-serif; font-size:12px; fill:#7fd6e6; opacity:0.9 }
        ]]>
      </style>
    </defs>

    <!-- Card 1 -->
    <g transform="translate(12,10)">
      <rect width="260" height="100" rx="12" class="card" />
      <text x="22" y="36" class="title">Projects Completed</text>
      <text x="22" y="74" class="num">
        <tspan id="p1">0</tspan>
        <animate xlink:href="#p1" attributeName="textContent" from="0" to="6" dur="1.6s" fill="freeze" begin="0.2s" />
      </text>
      <text x="150" y="74" class="label">Active • Growth-driven</text>
    </g>

    <!-- Card 2 -->
    <g transform="translate(310,10)">
      <rect width="260" height="100" rx="12" class="card" />
      <text x="22" y="36" class="title">CI/CD Pipelines Built</text>
      <text x="22" y="74" class="num">
        <tspan id="p2">0</tspan>
        <animate xlink:href="#p2" attributeName="textContent" from="0" to="3" dur="1.6s" fill="freeze" begin="0.6s" />
      </text>
      <text x="150" y="74" class="label">Automated Testing & Deploy</text>
    </g>

    <!-- Card 3 -->
    <g transform="translate(608,10)">
      <rect width="260" height="100" rx="12" class="card" />
      <text x="22" y="36" class="title">Serverless Systems</text>
      <text x="22" y="74" class="num">
        <tspan id="p3">0</tspan>
        <animate xlink:href="#p3" attributeName="textContent" from="0" to="2" dur="1.6s" fill="freeze" begin="1.0s" />
      </text>
      <text x="150" y="74" class="label">Lambda • API Gateway • DynamoDB</text>
    </g>
  </svg>
</p>

> Note: GitHub may sanitize SVG behavior in some contexts. If the animation doesn't run on GitHub directly, download the SVG files to your repo and reference them as images (they will animate when viewed in browsers that support inline SVG animation).

---

## Live GitHub Stats & Languages
<p align="center">
  <!-- Replace the username param if you want another target -->
  <img src="https://github-readme-stats.vercel.app/api?username=judhayaprakash27052001-Git&show_icons=true&count_private=true&theme=dark&bg_color=071019" alt="github-stats" width="420"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=judhayaprakash27052001-Git&layout=compact&theme=dark&bg_color=071019" alt="top-langs" width="360"/>
</p>

---

## Top Skills
- Cloud: AWS (EC2, S3, Lambda, API Gateway, DynamoDB, CloudFront, EKS, RDS, IAM, VPC)
- DevOps: Jenkins, Git/GitHub, Docker, Kubernetes, Ansible, Terraform, GitHub Actions
- Observability: Prometheus, Grafana, CloudWatch, ELK
- Infra as Code: Terraform, CloudFormation; Containerization & Orchestration: Docker, Kubernetes
- Other: Linux, Shell scripting, React basics, Postman

---

## Selected Projects (with metric lines / GIF placeholders)
### Serverless Contact Book — AWS (link)
- Repo: https://github.com/judhayaprakash27052001-Git/AWS-Contact-Book-Serverless-Project.git
- Stack: S3 + CloudFront, Lambda, API Gateway, DynamoDB
- Metrics: API endpoints: 6 | Avg latency: 120ms | Uptime: 99.9%
- Preview (replace with real GIF):  
  <img src="https://media.giphy.com/media/26BRzozg4TCBXv6QU/giphy.gif" width="480" alt="serverless-preview"/>

### CI/CD Pipeline with Jenkins & Docker
- Highlights: Jenkins Declarative pipeline, multi-stage builds, Docker images stored in ECR, deployed to AWS EC2
- Metrics: Builds: 120 | Passing: 98% | Avg deploy time: ~3m
- Preview (GIF placeholder)

### Secure Web App for Financial Transactions (React)
- Highlights: Responsive UI, validation, deployed to S3/CloudFront or EC2 (as required)
- Metrics: UI validations: 38 | Test coverage: 72%
- Preview (GIF placeholder)

(If you want, I can generate small animated SVG architecture cards for each project showing pipelines, infra, and a "health" metric.)

---

## Badges (neon style)
[![AWS Badge](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://aws.amazon.com/) [![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/) [![K8s](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)](https://kubernetes.io/)

---

## Certifications
- Microsoft Azure Fundamentals (AZ-900)
- Google — Site Reliability Engineering: Measuring and Managing Reliability

---

## Contact & Links
- Website: https://judhayaprakash.com/
- Email: judhayaprakash27052001@gmail.com
- LinkedIn: https://www.linkedin.com/in/udhayaprakash-jayavel-80a20b191/
- GitHub: https://github.com/judhayaprakash27052001-Git
- Resume (local): Udhayaprakash_J_Resume.pdf

---

## How to use / customize
1. To change the neon header colors: edit the gradient stops (#00ff99, #00d4ff) in the SVG or supply your hex codes.
2. To change the metric counters, edit the <animate ... to="X"> values inside the metrics SVG or switch them to your desired numbers.
3. Prefer hosted images: save the SVG sources below as files (neon-header.svg, metrics.svg) in your repo and use:
   <img src="./neon-header.svg" alt="neon header" />
   <img src="./metrics.svg" alt="metrics" />
4. To update the GitHub stats, change the username in the github-readme-stats URLs.

---

## Raw SVG sources (copy to files for better compatibility)
### neon-header.svg
```xml
<!-- neon-header.svg -->
<svg width="1200" height="140" viewBox="0 0 1200 140" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Udhayaprakash J neon header">
  <defs>
    <linearGradient id="g1" x1="0" x2="1">
      <stop offset="0" stop-color="#00ff99"/>
      <stop offset="1" stop-color="#00d4ff"/>
    </linearGradient>
    <filter id="f1" x="-10%" y="-30%" width="120%" height="200%">
      <feGaussianBlur stdDeviation="6" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <style><![CDATA[
      .neonText { font-family: 'Fira Code', 'Inter', monospace; font-weight: 800; font-size:56px; fill: url(#g1); }
      .subText { font-family: 'Inter', Arial, sans-serif; font-size:18px; fill:#9debf7; opacity:0.9 }
      .glow { filter: url(#f1); }
      .blink { animation: blink 2.5s linear infinite; }
      @keyframes blink { 0% { opacity: 1; } 50% { opacity: 0.65; } 100% { opacity: 1; } }
    ]]></style>
  </defs>

  <rect x="0" y="0" width="1200" height="140" rx="8" fill="#071019" />
  <g transform="translate(36,48)" class="glow" style="transform-origin: left;">
    <text class="neonText">Udhayaprakash J</text>
  </g>
  <g transform="translate(36,102)" class="glow">
    <text class="subText">DevOps & Cloud Engineer • AWS • CI/CD • Docker • Kubernetes • Terraform</text>
  </g>
  <g transform="translate(36,96)">
    <rect x="0" y="-8" width="460" height="6" rx="3" fill="url(#g1)" opacity="0.9">
      <animate attributeName="width" from="0" to="460" dur="1.1s" begin="0.2s" fill="freeze" />
    </rect>
    <circle cx="470" cy="-5" r="5" fill="#00ff99" class="blink" />
  </g>
</svg>
```

### metrics.svg
```xml
<!-- metrics.svg -->
<svg width="880" height="120" viewBox="0 0 880 120" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Project metrics">
  <defs>
    <linearGradient id="mg" x1="0" x2="1">
      <stop offset="0" stop-color="#00ff99"/>
      <stop offset="1" stop-color="#00d4ff"/>
    </linearGradient>
    <style><![CDATA[
      .card { fill: #071019; stroke: rgba(0,212,255,0.06); rx:14; }
      .title { font-family: Inter, Arial, sans-serif; font-size:14px; fill:#9debf7; }
      .num { font-family: 'Fira Code', monospace; font-weight:700; font-size:36px; fill:url(#mg); }
      .label { font-family: Inter, Arial, sans-serif; font-size:12px; fill:#7fd6e6; opacity:0.9 }
    ]]></style>
  </defs>

  <g transform="translate(12,10)">
    <rect width="260" height="100" rx="12" class="card" />
    <text x="22" y="36" class="title">Projects Completed</text>
    <text x="22" y="74" class="num"><tspan id="p1">0</tspan><animate xlink:href="#p1" attributeName="textContent" from="0" to="6" dur="1.6s" fill="freeze" begin="0.2s" /></text>
    <text x="150" y="74" class="label">Active • Growth-driven</text>
  </g>

  <g transform="translate(310,10)">
    <rect width="260" height="100" rx="12" class="card" />
    <text x="22" y="36" class="title">CI/CD Pipelines Built</text>
    <text x="22" y="74" class="num"><tspan id="p2">0</tspan><animate xlink:href="#p2" attributeName="textContent" from="0" to="3" dur="1.6s" fill="freeze" begin="0.6s" /></text>
    <text x="150" y="74" class="label">Automated Testing & Deploy</text>
  </g>

  <g transform="translate(608,10)">
    <rect width="260" height="100" rx="12" class="card" />
    <text x="22" y="36" class="title">Serverless Systems</text>
    <text x="22" y="74" class="num"><tspan id="p3">0</tspan><animate xlink:href="#p3" attributeName="textContent" from="0" to="2" dur="1.6s" fill="freeze" begin="1.0s" /></text>
    <text x="150" y="74" class="label">Lambda • API Gateway • DynamoDB</text>
  </g>
</svg>
```

---

If you want me to:
- export these SVGs as files for you (neon-header.svg, metrics.svg) and produce a final README with relative image links, I can create them now and show the exact file contents ready to paste, OR
- change colors (e.g., neon-pink, neon-blue), adjust counter values, or add more animated cards for other metrics (commits, followers, repo health), tell me which values to use.

Next steps I can take now (pick any or say "do all"):
1. Save neon-header.svg & metrics.svg into README and show the final README again with <img src="./neon-header.svg"> and <img src="./metrics.svg"> references (best for GitHub rendering).  
2. Generate small animated architecture SVGs for each selected project with metrics and embed them.  
3. Replace placeholder GIFs with generated GIF previews (I can generate architecture SVGs you can convert to GIFs externally).  
4. Tweak colors, fonts, or counters to your exact taste.

Which of these should I do next? If you're happy, I will:
- produce the two SVG files as downloadable content (I will paste their raw source) and
- produce a final README variant that references them as local images (ideal for display on GitHub).
