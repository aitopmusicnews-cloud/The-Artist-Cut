# The Artists Cut — AWS Activate / Investor Static Site

A single-file static website for **The Artists Cut**, presenting the company as a creator-technology platform with an AWS production roadmap.

## Active product tracks

- **AI Music Video Studio** — AI video generation, audio analysis, timeline editing, media handling, asynchronous GPU jobs, and final rendering.
- **OG BEATZ Vault** — catalog operations, audio intelligence, CRM, promotional sharing, and studio workflow tools.
- **Music Copyright Protection** — a separate OG Beatz™ rights-protection product currently present under `Copyrights/`.
- **Next Gen Sounds** — experiential education and workforce-development mission already represented in the company ecosystem.

## Platform narrative

The public story now follows one connected creator journey:

**Create → Protect → Analyze → Manage → Promote → Distribute → Educate**

This positions The Artists Cut as a broader creator-technology company rather than a collection of unrelated apps.

## AWS production roadmap

The homepage intentionally distinguishes between **current prototypes** and **planned AWS production architecture**.

The proposed AWS service map includes:

- Amazon S3 + Amazon CloudFront for media/object storage and delivery
- Amazon ECS with AWS Fargate for containerized API/application services
- Amazon RDS for managed application data
- Amazon SQS, AWS Step Functions, and Amazon EventBridge for asynchronous media workflows
- Amazon Bedrock for managed generative-AI experimentation
- Amazon EC2 GPU instances for open-weight/custom AI media inference where needed
- AWS IAM, AWS KMS, AWS Secrets Manager, Amazon CloudWatch, AWS CloudTrail, and Amazon Cognito for security, identity, secrets, monitoring, and auditability

The planned use of AWS credits is centered on technical costs: GPU inference, AI experimentation, media storage, rendering, production environments, managed databases, queues, security, and observability.

## Run locally

No build step is required.

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

You can also open `index.html` directly in a browser.

## Deploy

Because the homepage is plain HTML/CSS/JavaScript, it can be hosted as a static site. The current AWS-oriented deployment direction is Amazon S3 + Amazon CloudFront, while the product applications can migrate separately to managed AWS application and compute services.

## Before AWS Activate / public launch

Replace the contact placeholder near the bottom of `index.html` with the approved professional company email and, where available:

- pitch-deck link
- founder/company LinkedIn profile
- accurate funding stage
- working product/demo links
- AWS Account ID for the application workflow

The public page intentionally avoids inventing AWS deployment status, revenue, valuation, user-count, fundraising, or market-size figures.