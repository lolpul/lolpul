# Elisey Kochura

**R&D / Software Engineer — backend, systems and embedded integration**

I work across software, electronics, embedded Linux, server infrastructure and UAV systems. My work connects component boundaries with implementation, diagnosis and verification.

Open to Python Backend, Go Backend, Systems, Embedded Linux, IoT and R&D roles, including remote work.

[Engineering portfolio and case studies](https://elisey.kochura.com) · [hello@kochura.com](mailto:hello@kochura.com)

## Selected engineering work

### Python backend — validation and failure boundaries

[Kochura Deploy showcase](https://github.com/lolpul/kochura-deploy-showcase): a small FastAPI application with strict input models, injected storage/delivery interfaces and persistence-before-notification ordering. A failed notification is a separate outcome from acceptance.

[Service code](https://github.com/lolpul/kochura-deploy-showcase/blob/main/examples/application-flow/app/service.py) · [Tests](https://github.com/lolpul/kochura-deploy-showcase/blob/main/examples/application-flow/tests/test_flow.py) · [Actions](https://github.com/lolpul/kochura-deploy-showcase/actions/workflows/python.yml) · [Case study](https://elisey.kochura.com/work/kochura-deploy)

The public example uses in-memory storage and synthetic inputs. The private product has a website and beta-application API; hosting automation remains planned.

### Go systems — cancellation and resource ownership

[Networking showcase](https://github.com/lolpul/lolpul-networking-showcase): three standalone examples of serial writer ownership, cooperative cancellation followed by joining a worker, and cleanup after partial resource acquisition.

[Lifecycle code](https://github.com/lolpul/lolpul-networking-showcase/blob/main/examples/session-lifecycle/writer.go) · [Tests](https://github.com/lolpul/lolpul-networking-showcase/blob/main/examples/session-lifecycle/writer_test.go) · [Actions with race checks](https://github.com/lolpul/lolpul-networking-showcase/actions/workflows/go.yml) · [Case study](https://elisey.kochura.com/work/lolpul-vpn)

The examples make concurrency contracts reviewable. Real transports and experimental networking protocols stay private; no production VPN or performance claim is implied.

### Embedded / UAV — observable state and fault handling

[ArduPilot Lua examples](https://github.com/lolpul/ardupilot-lua-scripts): sensor-event qualification, guarded sequences and virtual resource leases, with mocked firmware boundaries and timing/float32 checks.

[State machine](https://github.com/lolpul/ardupilot-lua-scripts/blob/main/modules/portfolio_sequence.lua) · [Host tests](https://github.com/lolpul/ardupilot-lua-scripts/blob/main/tests/run.lua) · [Actions](https://github.com/lolpul/ardupilot-lua-scripts/actions/workflows/checks.yml) · [Case study](https://elisey.kochura.com/work/uav-flight-systems)

These independent demonstrations read state and emit status text. Host tests do not establish aircraft behavior; SITL, HIL, bench and flight validation remain outside their recorded evidence.

### Kotlin — state, lifecycle and stale results

[Android networking showcase](https://github.com/lolpul/vpn-android-showcase): a platform-neutral Kotlin/JVM state holder using StateFlow, coroutines, authoritative startup lookup and guards against superseded results.

[State holder](https://github.com/lolpul/vpn-android-showcase/blob/main/examples/ui-state/src/main/kotlin/example/state/ConnectionModel.kt) · [Tests](https://github.com/lolpul/vpn-android-showcase/blob/main/examples/ui-state/src/test/kotlin/example/state/ConnectionModelTest.kt) · [Actions](https://github.com/lolpul/vpn-android-showcase/actions/workflows/kotlin.yml) · [Case study](https://elisey.kochura.com/work/android-networking)

This demonstrates application-state reasoning; Compose rendering, Android services and real VPN connectivity require separate integration evidence.

### Full application — 3D printing service MVP

[3D Printing Order Website](https://github.com/lolpul/3d-printing-order-website): Next.js/TypeScript public and admin pages, Prisma/PostgreSQL data access, server validation, local image processing and SEO.

[Server actions](https://github.com/lolpul/3d-printing-order-website/blob/main/src/app/admin/portfolio/actions.ts) · [Validation tests](https://github.com/lolpul/3d-printing-order-website/blob/main/src/lib/validation.test.ts) · [Local demo and verification](https://github.com/lolpul/3d-printing-order-website/blob/main/docs/verification.md)

Full MVP source is already public. Database-free local demonstration is reproducible; there is no verified public deployment or Actions workflow for this project.

## Tools in context

Python / FastAPI and Go for backend and systems work; Linux / Docker for service environments; Kotlin for Android; TypeScript / Next.js / SQL for applications; ArduPilot / Lua and embedded Linux for integration work. Project code and documented verification define the scope of each claim.

The three software showcases and Lua demonstrations were independently prepared with AI assistance. Their READMEs describe contracts, tradeoffs, reproducible checks and limits; private source, employer materials and operational data remain excluded.

## Кратко по-русски

Я R&D / Software Engineer: работаю на пересечении программирования, электроники, embedded Linux, серверной инфраструктуры и беспилотных систем. Рассматриваю Python Backend, Go Backend, Systems, Embedded Linux, IoT и R&D позиции, включая удалённую работу.

Выше — пять проектов с прямыми ссылками на код и проверки. Публичные примеры показывают конкретные инженерные решения; закрытые продукты и материалы работодателя остаются приватными. Границы проверки указаны в каждом README.

[Портфолио](https://elisey.kochura.com) · [Связаться: hello@kochura.com](mailto:hello@kochura.com)
