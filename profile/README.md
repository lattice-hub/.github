# Lattice Hub

## 中文

Lattice Hub 致力于构建面向 AI Native 与云原生架构的 Pole 服务治理生态。我们希望用一套开放的控制面、协议规范、SDK 与 Sidecar 能力，帮助服务在多语言、多协议和多运行时环境中获得一致的注册发现、配置管理、流量治理与可观测治理体验。

Pole Control Plane 兼容 Nacos、Polaris、Apollo、Consul、Eureka、Envoy 等治理中心或数据面协议，并持续补齐面向 AI Native 场景的 MCP Registry、A2A Agent Registry 等能力。项目既关注传统微服务治理，也关注 Agent、工具和模型服务进入生产环境后的注册、发现、路由、鉴权、限流、镜像、Mock 与发布管理。

### 核心项目

- [pole-control-plane](https://github.com/lattice-hub/pole-control-plane)：Pole 的服务治理控制面，提供注册发现、配置中心、治理规则、Console 网关与 AI Native 能力。
- [specification](https://github.com/lattice-hub/specification)：Pole 的跨语言治理协议与数据契约，沉淀服务、配置、治理规则和 AI Native 能力的统一模型。
- [pole-client-rust](https://github.com/lattice-hub/pole-client-rust)：轻量 Rust SDK，用于 Proxyless Service Governance 场景。
- [pole-sidecar](https://github.com/lattice-hub/pole-sidecar)：面向 Sidecar 数据面形态的 Pole 生态组件。

欢迎从 issue、设计讨论、协议建模、SDK 适配、文档完善和测试用例开始参与。对于涉及协议或跨项目契约的变更，建议先在 `specification` 中对齐模型，再推进控制面和客户端实现。

## English

Lattice Hub builds the Pole service governance ecosystem for AI Native and cloud-native architectures. Our goal is to provide an open control plane, shared specifications, SDKs, and sidecar components so services can use consistent discovery, configuration, traffic governance, and operational control across languages, protocols, and runtimes.

Pole Control Plane is designed to be highly compatible with governance centers and data-plane protocols such as Nacos, Polaris, Apollo, Consul, Eureka, and Envoy. It also extends service governance into AI Native scenarios with capabilities such as MCP Registry and A2A Agent Registry. The project covers both traditional microservice governance and production concerns for agents, tools, and model-facing services, including registration, discovery, routing, authorization, rate limiting, mirroring, mocking, and release management.

### Key Projects

- [pole-control-plane](https://github.com/lattice-hub/pole-control-plane): the Pole service governance control plane, including service discovery, configuration, governance rules, the console gateway, and AI Native capabilities.
- [specification](https://github.com/lattice-hub/specification): cross-language governance specifications and data contracts for services, configuration, governance rules, and AI Native capabilities.
- [pole-client-rust](https://github.com/lattice-hub/pole-client-rust): a lightweight Rust SDK for proxyless service governance.
- [pole-sidecar](https://github.com/lattice-hub/pole-sidecar): Pole ecosystem components for sidecar-based data-plane deployments.

We welcome contributions through issues, design discussions, specification modeling, SDK integrations, documentation, and tests. For protocol-level or cross-project changes, start by aligning the model in `specification`, then carry the change through the control plane and clients.
