# Younghoon

Backend engineer working mostly in TypeScript (Node.js) and Go. I design services around DDD, CQRS and event-driven patterns, and I like turning architecture rules into checks that run in CI instead of leaving them in a wiki.

📫 [kyhsa93@naver.com](mailto:kyhsa93@naver.com) · ✍️ [kyhsa93.github.io](https://kyhsa93.github.io/) ([한국어](https://kyhsa93.github.io/ko/))

## Selected work

| Project | What it shows |
|---|---|
| [**backend-service-playbook**](https://github.com/kyhsa93/backend-service-playbook) | One DDD backend design (Account / Card / Payment) implemented independently in 5 stacks: NestJS, Go, Spring Boot (Java, Kotlin), FastAPI. Each ships a compliance harness that scores layering, dependency direction and naming, plus a scaffolding generator. CI covers each stack, CodeQL, gitleaks, Trivy and docs-drift checks. |
| [**nestjs-rest-cqrs-example**](https://github.com/kyhsa93/nestjs-rest-cqrs-example) ⭐ 870+ | Layered DDD + CQRS reference in NestJS: aggregates, domain events, repository interfaces, MySQL, and an outbox publishing to SQS (LocalStack). |
| [**k8s-playbook**](https://github.com/kyhsa93/k8s-playbook) | A catalog of Kubernetes deployment anti-patterns with an automated detection harness, checked against Argo CD / Flux / Kargo setups. |
| [**jipgye**](https://github.com/kyhsa93/jipgye) ([site](https://kyhsa93.github.io/jipgye/)) | A daily data pipeline on GitHub Actions: collects Seoul apartment transactions and rates, computes rent-vs-jeonse and renewal costs, and refuses to publish a number when the sample is too small. Test suite in CI, published corrections as GitHub Releases. |

## Writing

I write about backend architecture and the things that only break in production: aggregate design, testing pitfalls, benchmarking AI agents against architecture rules. → [All posts](https://kyhsa93.github.io/posts/)

## Stack

**Languages** TypeScript · Go · Java/Kotlin · Python
**Backend** NestJS · Spring Boot · FastAPI · MySQL · TypeORM · AWS SQS
**Infra** Docker · Kubernetes · GitHub Actions · Terraform

## Interests

Microservice design with DDD · event-driven architecture · containers and orchestration · cloud native (AWS, GCP)

## Also

Side projects (a browser raid game, an ASCII FPS, a toddler-milestone PWA) are in [side-projects](https://kyhsa93.github.io/side-projects/).
