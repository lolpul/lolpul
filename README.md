# Elisey Kochura

**Software Engineer — backend, systems, Linux infrastructure and product development**

I design and build software across backend services, concurrent systems, Linux infrastructure, Android application state and full-stack web products. I focus on clear component boundaries, explicit failure handling, testable implementations and practical verification.

Open to remote Python Backend, Go Backend, Systems, Embedded Linux, IoT and software engineering opportunities.

[Engineering portfolio and case studies](https://elisey.kochura.com) · [hello@kochura.com](mailto:hello@kochura.com)

## Selected engineering work

### Python backend — validation and failure boundaries

[Kochura Deploy showcase](https://github.com/lolpul/kochura-deploy-showcase): a focused FastAPI example with strict input models, injected storage/delivery interfaces and persistence-before-notification ordering. Failed delivery is reported separately from application acceptance.

[Service code](https://github.com/lolpul/kochura-deploy-showcase/blob/main/examples/application-flow/app/service.py) · [Tests](https://github.com/lolpul/kochura-deploy-showcase/blob/main/examples/application-flow/tests/test_flow.py) · [CI](https://github.com/lolpul/kochura-deploy-showcase/actions/workflows/python.yml) · [Case study](https://elisey.kochura.com/work/kochura-deploy)

This public example uses in-memory storage and synthetic inputs. The private product includes a website and beta-application API; hosting automation remains planned.

### Go systems — cancellation and resource ownership

[Networking showcase](https://github.com/lolpul/lolpul-networking-showcase): three standalone examples of serialized writer ownership, cooperative cancellation and worker joining, and cleanup after partial resource acquisition.

[Lifecycle code](https://github.com/lolpul/lolpul-networking-showcase/blob/main/examples/session-lifecycle/writer.go) · [Tests](https://github.com/lolpul/lolpul-networking-showcase/blob/main/examples/session-lifecycle/writer_test.go) · [CI with race checks](https://github.com/lolpul/lolpul-networking-showcase/actions/workflows/go.yml) · [Case study](https://elisey.kochura.com/work/lolpul-vpn)

These examples make concurrency contracts reviewable. Production networking integrations and throughput claims are outside their scope.

### Kotlin — state, lifecycle and stale results

[Android networking showcase](https://github.com/lolpul/vpn-android-showcase): a platform-neutral Kotlin/JVM state holder using StateFlow, coroutines, startup reconciliation and protection against superseded results.

[State holder](https://github.com/lolpul/vpn-android-showcase/blob/main/examples/ui-state/src/main/kotlin/example/state/ConnectionModel.kt) · [Tests](https://github.com/lolpul/vpn-android-showcase/blob/main/examples/ui-state/src/test/kotlin/example/state/ConnectionModelTest.kt) · [CI](https://github.com/lolpul/vpn-android-showcase/actions/workflows/kotlin.yml) · [Case study](https://elisey.kochura.com/work/android-networking)

This is a testable application-state example, not a production Android client or validated VPN service.

### Full-stack web — 3D printing service MVP

[3D Printing Order Website](https://github.com/lolpul/3d-printing-order-website): Next.js/TypeScript public and admin pages, Prisma/PostgreSQL data access, server-side validation, local image processing and SEO.

[Server actions](https://github.com/lolpul/3d-printing-order-website/blob/main/src/app/admin/portfolio/actions.ts) · [Validation tests](https://github.com/lolpul/3d-printing-order-website/blob/main/src/lib/validation.test.ts) · [Verification](https://github.com/lolpul/3d-printing-order-website/blob/main/docs/verification.md) · [CI](https://github.com/lolpul/3d-printing-order-website/actions/workflows/verify.yml)

Full MVP source is public. The database-free local demo is reproducible; production readiness and live deployment are not claimed.

## Technical focus

- **Backend & API design:** Python, FastAPI, Go, validation, error contracts, testing
- **Systems & infrastructure:** Linux, Docker, service deployment, networking and concurrency
- **Applications:** TypeScript, Next.js, React, Kotlin, Android architecture
- **Engineering workflow:** architecture review, automation, reproducible checks and documentation

The examples were prepared with AI assistance and validated to the extent documented in each repository. Private source, operational credentials and customer data remain excluded.

## Кратко по-русски

Я инженер-программист. Работаю с backend-разработкой, Go, Python, Linux, сетевыми системами, Android и веб-приложениями. Интересуют международные удалённые вакансии и проектная работа.

Выше — четыре проекта с прямыми ссылками на исходный код, тесты и документацию. Границы проверки и текущая зрелость решений описаны в каждом репозитории.

[Портфолио](https://elisey.kochura.com) · [Связаться: hello@kochura.com](mailto:hello@kochura.com)
