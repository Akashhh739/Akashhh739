## Hey, I'm Akash 👋

I build AI products end to end, from training the model to running the servers it lives on.

### 🏠 Strukt AI: [struktai.work](https://www.struktai.work)

**Upload a 2D floor plan and get a furnished, walkable 3D home.**

- Floor plan → 3D model, editable on a 2D canvas
- Export to **Blender, SketchUp (.skp), Revit** and more
- Furniture photo → 3D model with **SAM 3D**, plus import of your own 3D models
- Rendered images, **Bake** for full 3D houses, and a **3D walkthrough**

I started it as a side project and grew it into a product with **9,000+ users** and paying customers. I worked on every layer myself.

**How it grew**
- **v0:** a rough prototype on off-the-shelf models. It worked, but the quality wasn't good enough.
- **Pilot:** I watched how real users edited the outputs. No good public dataset exists for 2D → 3D, so I built one from that real usage.
- **Pro model:** I trained a much heavier model on that data. Returning users noticed the jump, more customers came in, and we raised prices.
- **Bake:** generates entire new 3D houses, furniture included.
- **Canvas + exports:** 2D editing on a canvas, CAD/3D exports and SAM 3D furniture. Every edit doubles as training data for the next model.

**What I own**

| Layer | What I did |
|---|---|
| **ML** | Room detection, OCR room-typing, constraint-solver furniture placement, and SAM 3D image-to-3D. Built the dataset, trained the models, and shipped them to prod |
| **Infra** | Hybrid GPU inference across AWS, RunPod and an on-prem k3s server behind Cloudflare. Secured startup cloud credits to fund it |
| **Backend** | Job queue with credit hold/commit/refund, Postgres, and auth |
| **Reliability** | CI/CD, load and autoscaling tests, and debugging prod incidents from the logs |
| **Security** | Auth hardening, SQL-injection protection, and WAF rules |
| **Growth** | Google Search Console, crawling and SEO; we now get organic traffic from ChatGPT referrals |

I use AI coding agents as a force multiplier, but I make the architecture calls and debug the production problems myself.

### 🧪 Smaller builds

- **[FHIR clinical lakehouse](https://github.com/Akashhh739/FHIR)**: a FHIR pipeline on Databricks/PySpark, an ML model and a text-to-SQL agent
- **[AI-in-Drug-discovery](https://github.com/Akashhh739/AI-in-Drug-discovery)**: AUC 0.970. I also caught a 207/256 train/test leak that had been inflating the results.
- **[PPE-watch](https://github.com/Akashhh739/PPE-watch-)**: real-time PPE detection with YOLO
- **[DevLM](https://github.com/Akashhh739/DevLM)**: an on-demand DevSecOps analyst. It pulls logs from AWS, Sentry, Cloudflare and Postgres into Parquet, then runs an agent over the logs and the codebase to diagnose prod issues.

### 🛠 Stack

`Python` `PyTorch` `YOLO` `SAM 3D` `LangGraph` `PySpark` `Databricks` `PostgreSQL` `Docker` `Kubernetes/k3s` `AWS` `RunPod` `Cloudflare` `GitHub Actions`

### 🔭 What's next

I'm looking for a team that ships **applied AI or ML infra** to real users, where one person can own a problem from the model all the way to production. I'm open to India, remote or relocation.

If that sounds like your team, [let's talk](https://www.linkedin.com/in/akash-kandukuri-654939253).
