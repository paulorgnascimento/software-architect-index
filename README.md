# Arquitetura de Soluções e Software

## 1. Por que Arquitetura Importa?
1.1 O que é Arquitetura de Software e Soluções  
1.2 O Impacto das Decisões Arquiteturais  
1.3 Papel Estratégico do Arquiteto  
1.3.1 Competências Técnicas  
1.3.2 Competências Comportamentais  
1.4 Pensamento Sistêmico e Visão de Negócio  

## 2. Como Pensar Arquiteturalmente
2.1 Análise de Trade-offs  
2.2 Técnicas de Priorização Arquitetural  
2.3 Requisitos Não Funcionais  
2.4 Well-Architected Framework (WAF)  
2.4.1 Excelência Operacional  
2.4.2 Segurança  
2.4.3 Confiabilidade  
2.4.4 Eficiência de Performance  
2.4.5 Otimização de Custos  
2.4.6 Sustentabilidade  

## 3. Modelagem Estratégica e Design
3.1 Visões Arquiteturais  
3.1.1 4+1 Views Model  
3.1.2 Modelo C4  
3.1.3 UML e BPMN  
3.2 Técnicas de Modelagem e Descoberta de Domínio  
3.2.1 Domain-Driven Design (DDD)  
3.2.1.1 Bounded Contexts  
3.2.1.2 Context Mapping  
3.2.2 Event Storming  
3.3 Orquestração vs Coreografia de Serviços  
3.4 Arquitetura Evolutiva  
3.4.1 Fitness Functions  
3.4.2 Experimentação Controlada  
3.5 Documentação de Arquitetura  
3.5.1 Architecture Decision Records (ADR)  
3.5.2 Arc42, TOGAF e Documentação Viva  

## 4. Estilos Arquiteturais e Padrões
4.1 Estilos Arquiteturais  
4.1.1 Monolitos  
4.1.2 Microsserviços  
4.1.3 Arquitetura Serverless  
4.1.4 Arquitetura Orientada a Eventos (EDA)  
4.1.5 Arquiteturas Híbridas (Microsserviços + Serverless)  
4.1.6 Service Mesh (Istio, Linkerd)  
4.2 Padrões Arquiteturais  
4.2.1 Integrações Síncronas (REST, gRPC)  
4.2.2 Integrações Assíncronas (Mensageria, Pub/Sub)  
4.2.3 Event Sourcing  
4.2.4 CQRS (Command Query Responsibility Segregation)  
4.2.5 Saga Pattern  
4.2.6 Two-Phase Commit  
4.2.7 API Composition  
4.2.8 Deduplicação de Eventos e Mensagens  
4.2.9 Idempotência em Sistemas Distribuídos  

## 5. Qualidades Arquiteturais (Ilities)
5.1 Disponibilidade  
5.2 Escalabilidade  
5.3 Desempenho e Latência  
5.4 Resiliência  
5.5 Segurança  
5.6 Observabilidade  
5.7 Manutenibilidade e Evolutividade  
5.8 Portabilidade e Interoperabilidade  
5.9 Elasticidade  
5.10 Adaptabilidade  

## 6. Arquitetura em Nuvem e Sistemas Distribuídos
6.1 Fundamentos de Cloud Computing  
6.2 Arquitetura Multi-Cloud e Híbrida  
6.3 Infraestrutura como Código (IaC)  
6.4 Arquiteturas Resilientes  
6.4.1 Retry Pattern  
6.4.2 Circuit Breaker  
6.4.3 Bulkhead Pattern  
6.4.4 Timeout e Backoff Exponencial  
6.4.5 Failover e Disaster Recovery  
6.4.6 Multi-Region Deployments  
6.5 Arquiteturas de Alta Disponibilidade  
6.5.1 Multi-AZ Architectures  
6.5.2 Load Balancing Global e Regional  
6.5.3 Replicação de Dados Síncrona e Assíncrona  
6.6 Arquiteturas de Alto Desempenho  
6.6.1 Escalabilidade Horizontal e Vertical  
6.6.2 Otimização de Latência e Proximidade  
6.6.3 Edge Computing e CDNs  
6.6.4 Banco de Dados para Alta Performance (Sharding, Read Replicas)  
6.6.5 Compressão e Cache Distribuído  
6.7 FinOps: Otimização de Custos em Cloud  

## 7. Governança e Evolução Arquitetural
7.1 Architecture Review Board (ARB)  
7.2 Ciclo de Vida da Arquitetura  
7.2.1 Planejamento Estratégico  
7.2.2 Implementação e Entrega Contínua  
7.2.3 Avaliação, Revisão e Melhoria Contínua  

## 8. Segurança e Conformidade em Arquitetura
8.1 Princípios de Segurança por Design  
8.2 Modelos de Ameaças e Táticas de Mitigação (STRIDE, DREAD)  
8.3 Zero Trust Architecture  
8.4 Compliance as Code (GDPR, LGPD, HIPAA)  
8.5 DevSecOps e Automação de Segurança  
8.6 Gerenciamento de Segurança em Sistemas Distribuídos  
8.6.1 Criptografia em Trânsito e Repouso  
8.6.2 Gerenciamento de Chaves e Segredos  
8.6.3 Auditoria e Rastreabilidade de Acessos  
8.6.4 Privacidade por Design (Anonimização, Minimização de Dados)  

## 10. Arquitetura e Cultura Organizacional
10.1 Team Topologies e Arquitetura de Sistemas  
10.2 Arquitetura Colaborativa e InnerSource  
10.3 Gestão de Conhecimento Arquitetural (Guildas, Comunidades)  
10.4 Estratégias para Adoção de Novas Tecnologias  
10.5 Gestão de Conflitos em Decisões Arquiteturais  
10.6 Arquitetura em Contextos Ágeis (SAFe, LeSS, Scrum em Escala)  

## 11. Modernização e Gestão de Legados
11.1 Estratégias de Migração (Strangler Fig, Anti-Corruption Layer)  
11.2 Refactoring Tático vs. Re-architecting Estratégico  
11.3 Gestão de Technical Debt Arquitetural  
11.4 Plataformas de Modernização (Low-Code, Legacy Rehosting)  
11.5 Simulação de Ambientes Legacy para Migração  

## 12. Ferramentas e Automação
12.1 Ferramentas de Análise Arquitetural (CAST, SonarQube)  
12.3 Cloud-Native Toolchain (Terraform, Kubernetes, Service Mesh)  
12.4 Observabilidade em Tempo Real (OpenTelemetry, eBPF)  
12.5 Simuladores de Falhas (Chaos Engineering Tools)  
12.6 Plataformas de Experimentação Arquitetural (A/B Testing em Nível de Infra)  

## 14. Métricas e Avaliação de Impacto
14.1 OKRs para Arquitetura (% Redução de Incidentes Críticos)  
14.2 Health Checks Arquiteturais (Fitness Functions Quantitativas)  
14.3 ROI de Decisões Arquiteturais (Custo Total de Propriedade - TCO)  
14.4 Benchmarks de Performance e Custo (Comparativos Multi-Cloud)  