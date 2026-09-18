<div align="center">

# Thiago Pereira
### Arquiteto de Software · Engenheiro de Software

Projeto e desenvolvo sistemas corporativos com foco em domínio, arquitetura e sustentabilidade técnica.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/thiago-rpereira/)
[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](#)
[![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)](#)
[![Location](https://img.shields.io/badge/Brasília-DF-111827?style=for-the-badge)](#)

</div>

---

### Experiência & Atuação

Engenheiro de software com mais de 16 anos de experiência em sistemas corporativos para os setores público, financeiro e de saúde. Atuo na definição arquitetural e na implementação técnica de soluções backend.

Critérios adotados nas decisões técnicas:
* Baixo acoplamento e limites claros entre módulos
* Domínio desacoplado de infraestrutura e frameworks
* Evolução contínua do código em detrimento de reescritas completas

```text
  [ Regras de Negócio ]
           │
           ▼
    Bounded Contexts   ──►   Arquitetura Hexagonal   ──►   Infraestrutura
```

---

### Competências Técnicas

| Dimensão | Tecnologias e Práticas |
| :--- | :--- |
| **Arquitetura & Design** | `Domain-Driven Design (DDD)` `Arquitetura Hexagonal` `Monólitos Modulares` `CQRS` `Event-Driven` |
| **Backend & Frameworks** | `Java` `Spring Boot` `Spring Security` `Spring Cloud` `APIs RESTful` |
| **Persistência & Mensageria** | `PostgreSQL` `Oracle` `Kafka` `RabbitMQ` |
| **Infraestrutura & DevOps** | `Docker` `Kubernetes` `GitOps` `ArgoCD` `Testcontainers` |

*Experiência prévia no desenvolvimento web frontend (React, Vue, Angular), com atuação atual voltada a backend e arquitetura.*

---

### Projeto Atual

Atuação como arquiteto de software no desenvolvimento de uma plataforma de gestão arquivística e governança digital de documentos.

Principais responsabilidades:
* Modelagem de regras de negócio complexas via Bounded Contexts.
* Isolamento de domínio utilizando Arquitetura Hexagonal (Ports & Adapters).
* Integração com repositórios e serviços legados de ECM/GED.
* Garantia de rastreabilidade, auditoria e consistência de dados.

---

### Diretrizes de Engenharia

* Modelar requisitos de domínio antes de selecionar frameworks e bibliotecas.
* Explicitar dependências estruturais entre módulos.
* Restringir regras de negócio e validações à camada de domínio.
* Adicionar padrões distribuídos apenas sob requisitos claros de escala ou integração.
* Basear otimizações de desempenho em métricas e telemetria.
