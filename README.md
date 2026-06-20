# meta-prompt-no-notebook-lm
Caderno temático criado no NotebookLM para estudar e desenvolver Meta Prompts. O projeto explora técnicas de engenharia de prompts, curadoria de fontes, testes práticos e refinamento de instruções para IA. Como resultado, reúne resumos, glossário e prompts reutilizáveis para futuras aplicações.

<objetivo>
Criação de um NotebookLM que atue como copiloto especializado na criação, refinamento e otimização de prompts.
</objetivo>

## summary_framework
Este resumo técnico consolida a transição de um ambiente de prototipagem pessoal para uma arquitetura multiagente de nível industrial, fundamentada na documentação técnica minerada via pipeline GSSC.

<origem_das_fontes_iniciais> As fontes iniciais foram geradas a partir de um protótipo pessoal de NotebookLM construído para atuar como copiloto na geração de prompts otimizados e orquestração de agentes. O ambiente original operava como uma base de conhecimento para o nicho pessoal, servindo de laboratório para testes de arquiteturas RAG e agentes autônomos. Através da análise de 46 fontes técnicas, extraímos o sinal crítico para converter fluxos artesanais em uma estrutura endurecida e escalável. </origem_das_fontes_iniciais>

<criterios_de_seleção> Filtramos as fontes originais para expurgo total de dados sensíveis (PII) e remoção de ruído atencional. O critério central foi a Engenharia de Contexto Industrial: priorizamos arquiteturas Zero-Trust e isolamento sintático estrito via tags XML para neutralizar ataques de vazamento de instrução. Buscamos fontes que validassem a interoperabilidade determinística do squad (Orquestrador, Executor, Auditor), tratando o prompt como código de compilação para garantir estabilidade e escalabilidade pública. </criterios_de_seleção>

<processo_de_pesquisa> A pesquisa operou via pipeline GSSC (Gather, Select, Structure, Compress) dentro deste ambiente. Mineramos o "Dossiê de Meta-Prompting" para extrair a lógica categórica (Funtores e Monads) aplicada à orquestração recursiva (RMP), garantindo que sub-agentes recebam blueprints modulares. Implementamos o "Hardening" analisando vetores de ataque do OWASP Top 10 e mitigando-os com o Dual LLM Pattern. Investigamos a economia de tokens via Observation Masking e Prompt Caching para combater o efeito "Lost in the Middle" e reduzir a latência de primeiro token (TTFT) em até 90% em fluxos de longo horizonte. O processo converteu o conhecimento empírico em uma infraestrutura agnóstica e endurecida. </processo_de_pesquisa>

<justificativa_das_fontes> 
<01_Hardened_Agent_Foundation>
    • Motivo da seleção: Estabelece a identidade industrial e defesas primárias (Salted Tags/Dual LLM) contra Prompt Injections em escala pública. </01_Hardened_Agent_Foundation>
<02_Matriz_de_Orquestração_de_Fluxos>
    • Motivo da seleção: Implementa a orquestração via Meta-Prompting Recursivo (RMP), permitindo a decomposição de tarefas complexas em planos de execução modulares. </02_Matriz_de_Orquestração_de_Fluxos>
<03_Data_Schema_Registry>
    • Motivo da seleção: Garante interoperabilidade segura via JSON Schema e Pydantic, impedindo a deriva semântica e falhas de tipagem entre os agentes do squad. </03_Data_Schema_Registry>
<04_Audit_Quality_Protocols>
    • Motivo da seleção: Ativa o LLM-as-a-Judge para auditoria de fidelidade e cálculo de F1-Score, assegurando conformidade técnica sem intervenção humana constante. </04_Audit_Quality_Protocols>
<05_Deployment_Integration_Harness>
    • Motivo da seleção: Define os requisitos de deploy (VRAM/quantização) e estabilização de prefixos para otimizar custos e performance via Prompt Caching. </05_Deployment_Integration_Harness>
      </justificativa_das_fontes>
