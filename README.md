# Mindmap – Compra de Soluções Digitais (Stakeholders)

```mermaid
mindmap
  root((Compra de Soluções Digitais))
    Patrocinio_Executivo
      CEO["Visão estratégica"]
      CFO["ROI e viabilidade"]
      COO["Execução e prioridades"]
    Area_Demandante
      CX_Operacoes["Eficiência, SLA, backlog"]
      Digital_Produto["Jornada, adoção"]
      Marketing_CRM["Automação, retenção"]
    TI_e_Arquitetura
      CIO["Governança e integração"]
      Arquitetura["Padrões e escalabilidade"]
      Infra_Cloud["Custos, HA, performance"]
    Seguranca_e_Compliance
      CISO["Segurança"]
      LGPD_DPO["Privacidade"]
      Risco_Auditoria["Controles"]
    Compras_e_Juridico
      Procurement["RFP e negociação"]
      Juridico["Contrato e DPA"]
    Execucao_e_Adocao
      PMO["Cronograma e dependências"]
      Change["Treinamento e engajamento"]
    Usuarios_e_Champions
      Usuarios_Finais["Usabilidade e ganho real"]
      Champion_Interno["Influência e validação"]

mindmap
  root((Banco - Compra de Soluções Digitais))
    Lidera
      CX_Operacoes["CX / Atendimento"]
      Digital_Produtos["Canais Digitais"]
    Patrocinio
      COO["Eficiência operacional"]
      CFO["ROI, redução de custo"]
    Viabiliza
      TI_Arquitetura["Integração core bancário"]
      Dados_IA["Modelos e analytics"]
    Bloqueia
      Risco_Compliance["Bacen, auditoria"]
      Seguranca["Fraude e acesso"]
    Destrava
      Evidencias
        Case_Regulado["Cases em bancos regulados"]
        ROI_Comprovado["Saving operacional"]
        Compliance_LGPD["LGPD + Bacen"]

mindmap
  root((Energia - Compra de Soluções Digitais))
    Lidera
      Operacoes["Operações / Atendimento"]
      Engenharia["Campo e backoffice"]
    Patrocinio
      COO["Continuidade e escala"]
      Diretoria["Experiência do cliente"]
    Viabiliza
      TI["Integração sistemas legados"]
      Dados["Medições e eventos"]
    Bloqueia
      Regulacao["ANEEL / Compliance"]
      Arquitetura["Legado crítico"]
    Destrava
      Evidencias
        Reducao_Backlog["Redução de backlog"]
        Escala_Massiva["Picos e sazonalidade"]
        Casos_Setor["Cases utilities"]

mindmap
  root((Varejo - Compra de Soluções Digitais))
    Lidera
      Marketing["Conversão e retenção"]
      Digital["Omnichannel"]
    Patrocinio
      CMO["Receita"]
      COO["Escala operacional"]
    Viabiliza
      TI["Integrações rápidas"]
      Dados["Personalização"]
    Bloqueia
      Financeiro["Custo vs margem"]
      TI["Prioridade roadmap"]
    Destrava
      Evidencias
        Conversao["Aumento conversão"]
        Time_to_Value["Resultado rápido"]
        Black_Friday["Escala comprovada"]

flowchart TD
  A[Dor no atendimento] --> B[CX / Operações]
  B --> C[POC rápida]
  C --> D{Compliance OK?}
  D -->|Não| E[Ajustes segurança]
  D -->|Sim| F[CFO / ROI]
  F --> G[Contratação]

flowchart TD
  A[Backoffice manual] --> B[Operações]
  B --> C[Mapeamento processos]
  C --> D[TI / Arquitetura]
  D --> E[CFO]
  E --> F[Escala]

flowchart TD
  A[Decisão pouco precisa] --> B[Dados / BI]
  B --> C[Modelo / POC]
  C --> D{Explicável?}
  D -->|Não| E[Ajuste modelo]
  D -->|Sim| F[Executivo]

flowchart TD
  A[Volume repetitivo] --> B[CX]
  B --> C[UX Conversacional]
  C --> D[TI]
  D --> E[Produção]

flowchart TD
  A[Documentos manuais] --> B[Operações]
  B --> C[Jurídico / Compliance]
  C --> D[TI]
  D --> E[Contratação]

