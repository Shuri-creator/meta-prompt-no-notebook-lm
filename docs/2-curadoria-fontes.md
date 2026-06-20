## 📋 Curadoria de Fontes

### Fontes Utilizadas no Projeto

Este projeto foi fundamentado em 5 fontes técnicas principais, cuidadosamente 
selecionadas e processadas através do NotebookLM para extração de conhecimento 
estruturado.

#### 1. Fundação de Inteligência e Segurança (Hardened)

**Arquivo:** `01_Hardened_Agent_Foundation.md`

**Descrição:** Documento que estabelece a identidade industrial e defesas 
primárias contra Prompt Injections em escala pública. Cobre o padrão Dual LLM, 
tags salted, sanitização de escape e regras de ouro para segurança de agentes.

**Conceitos-chave:** Dual LLM Pattern, Salted Tags, Security Hardening, 
Prompt Injection Prevention, Zero-Trust Architecture.

---

#### 2. Matriz de Orquestração de Fluxos (Hardened RMP)

**Arquivo:** `02_Matriz_de_Orquestração_de_Fluxos.md`

**Descrição:** Implementa a orquestração via Meta-Prompting Recursivo (RMP), 
permitindo a decomposição de tarefas complexas em algoritmos de pensamento 
agnósticos a dados factuais. Define o pipeline de execução do Squad 
(Orquestrador, Executor e Auditor).

**Conceitos-chave:** Meta-Prompting Recursivo, Orquestração de Agentes, 
Morphismo Funcional, State Management, Error Boundaries.

---

#### 3. Registro de Esquemas e Dicionário de Variáveis (Hardened)

**Arquivo:** `03_Data_Schema_Registry.md`

**Descrição:** Garante interoperabilidade segura via JSON Schema e Pydantic, 
impedindo a deriva semântica e falhas de tipagem entre agentes. Define 
contratos de dados para Intenção, Decomposição e Auditoria.

**Conceitos-chave:** JSON Schema, Pydantic Validation, Data Contracts, 
Type Enforcement, Escape Sanitization, Observation Masking.

---

#### 4. Protocolos de Auditoria e Qualidade (Hardened)

**Arquivo:** `04_Audit_Quality_Protocols.md`

**Descrição:** Ativa o LLM-as-a-Judge para auditoria de fidelidade e cálculo 
de F1-Score, assegurando conformidade técnica sem intervenção humana constante. 
Implementa heurísticas de validação (Faithfulness, Conformidade Estrutural, 
Integridade de Isolamento e Densidade de Sinal).

**Conceitos-chave:** LLM-as-a-Judge, F1-Score Estimation, Drift Detection, 
Compliance Gates, Recursive Retry Protocol.

---

#### 5. Guia de Implementação e Deploy (Industrial Harness)

**Arquivo:** `05_Deployment_Integration_Harness.md`

**Descrição:** Define os requisitos de deploy (VRAM/quantização) e estabilização 
de prefixos para otimizar custos e performance via Prompt Caching. Cobre 
arquitetura StateGraph, hardware requirements e segurança runtime.

**Conceitos-chave:** Deployment Architecture, Prompt Caching, VRAM Optimization, 
Performance Tuning, Security Runtime Rules, Checkpointing.

---

### Critérios de Seleção das Fontes

As fontes foram filtradas de um dossiê maior de 46 documentos técnicos, 
aplicando os seguintes critérios:

1. **Engenharia de Contexto Industrial** - Priorizamos arquiteturas 
   Zero-Trust e isolamento sintático estrito via tags XML

2. **Interoperabilidade Determinística** - Tratamento do prompt como código 
   de compilação para garantir estabilidade e escalabilidade pública

3. **Purga de Dados Sensíveis** - Remoção total de PII (Personally Identifiable 
   Information) e ruído atencional

4. **Aplicabilidade Prática** - Foco em padrões comprovados e endurecidos, 
   não em experimentações teóricas

### Processo de Mineração de Conhecimento

O conhecimento foi extraído via pipeline **GSSC** (Gather, Select, Structure, 
Compress) dentro do NotebookLM:

- **Gather:** Coleta de 46 fontes técnicas iniciais
- **Select:** Filtragem para as 5 fontes críticas
- **Structure:** Organização em matrizes estruturais e conceitos-chave
- **Compress:** Aplicação de Observation Masking preservando 98% de fidelidade