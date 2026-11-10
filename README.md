# Akash Kandukuri

**I build AI products end to end, from training the model to running the servers it lives on.**

[struktai.work](https://www.struktai.work) · [LinkedIn](https://www.linkedin.com/in/akash-kandukuri-654939253)

---

## Strukt AI

Strukt AI turns a 2D floor plan into a furnished 3D home you can walk through. It has **9,000+ users**.

You can edit the plan on a 2D canvas, then export to Blender, SketchUp or Revit. A photo of a piece of furniture becomes a 3D model, and you can render images, bake full houses and walk through the result.

It started as a side project on off-the-shelf models that weren't good enough. No public dataset existed for 2D → 3D, so I built one from how real users edited their outputs. I then trained a heavier Pro model on that data. Returning users noticed the jump, more customers came in, and we raised prices.

I built every layer:

```
models      room detection · OCR room-typing · constraint-solver furniture placement · SAM 3D
infra       hybrid GPU inference: AWS + RunPod + on-prem k3s, behind Cloudflare
backend     job queue · credits · Postgres · auth
ops         CI/CD · load & autoscaling tests · prod debugging from the logs
security    auth hardening · SQL-injection protection · WAF rules
growth      Search Console · SEO · organic traffic from ChatGPT
```

---

## Other things I've built

**[DevLM](https://github.com/Akashhh739/DevLM)**: pulls logs from AWS, Sentry, Cloudflare and Postgres, then runs an agent over the logs and the codebase to find what broke.

**[FHIR](https://github.com/Akashhh739/FHIR)**: a clinical data lakehouse on Databricks with a readmission model and a text-to-SQL agent.

**[AI-in-Drug-discovery](https://github.com/Akashhh739/AI-in-Drug-discovery)**: scores 0.970 AUC on EGFR. It also caught a train/test leak that was quietly inflating the scores.

**[PPE-watch](https://github.com/Akashhh739/PPE-watch-)**: real-time YOLOv8 safety-gear detection, deployed in a working facility.

---

## Stack

Python · PyTorch · YOLO · LangGraph · PySpark · Databricks · Postgres · Docker · Kubernetes · AWS · Cloudflare · GitHub Actions

---

## What's next

I want to join a team shipping applied AI to real users, where one person can own a problem from the model all the way to production. I'm open to India, remote or relocation.

[Say hi.](https://www.linkedin.com/in/akash-kandukuri-654939253)
