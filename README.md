# Playbook — Mindmaps de Aquisição de Soluções Digitais (Setor + Solução)

```mermaid
mindmap
  root((Aquisição de Soluções Digitais))
    01_Geral_Stakeholders
      Patrocinio_Executivo
        CEO_COO["Estratégia, prioridade, execução"]
        CFO["ROI, TCO, previsibilidade"]
        CHRO["Impacto em pessoas (quando muda operação)"]
      Area_Demandante
        CX_Operacoes["SLA, backlog, qualidade, escala"]
        Digital_Produto["Jornada, adoção, omnicanal"]
        Marketing_CRM["Conversão, retenção, campanhas"]
      TI_e_Dados
        CIO_TI["Integração, sustentação, padrão"]
        Arquitetura["Escalabilidade, legado"]
        Dados_IA["Governança, métricas, modelos"]
      Bloqueios_Transversais
        Seguranca_CISO["Acesso, logs, auditoria"]
        LGPD_DPO["Privacidade, retenção, base legal"]
        Risco_Auditoria["Controles, evidências"]
        Juridico["Contrato, DPA, responsabilidades"]
        Compras["RFP, negociação, risco fornecedor"]
      Destravas
        POC_Rapida["Prova de valor em 2-6 semanas"]
        KPI_Negocio["Saving, conversão, NPS, SLA"]
        Caso_Referencia["Case similar no setor"]
        Governanca["RACI, plano de implantação, suporte"]

    02_Segmentos_Mapa_de_Influencia
      Banco_Financeiro
        Lidera
          Canais_Digitais["Digital / Canais"]
          CX_Operacoes["Atendimento / Operações"]
        Bloqueia
          Risco_Compliance["Bacen, auditoria, AML"]
          Seguranca["Fraude, identidade, acesso"]
          Arquitetura["Core bancário e integrações"]
        Evidencias_que_Destravem
          Case_Regulado["Case em banco regulado"]
          Controles["Logs, trilha, segregação"]
          ROI["Redução custo + eficiência"]
          Continuidade["SLA, DR, observabilidade"]
      Energia_Utilities
        Lidera
          Operacoes["Operações / Atendimento"]
          Campo_Engenharia["Serviços de campo / backoffice"]
        Bloqueia
          Regulacao["ANEEL, compliance setorial"]
          Arquitetura["Legado crítico, integrações"]
          Sustentacao["Disponibilidade e suporte"]
        Evidencias_que_Destravem
          Escala_Picos["Sazonalidade e picos"]
          Reducao_Backlog["Backlog e SLA"]
          Caso_Utilities["Case em utilities"]
          Confiabilidade["Monitoramento e auditoria"]
      Varejo
        Lidera
          Marketing["Conversão e retenção"]
          Ecom_Digital["Omnichannel / e-commerce"]
          Operacoes["Logística e atendimento"]
        Bloqueia
          Financeiro["Margem e custo"]
          TI["Prioridade no roadmap"]
        Evidencias_que_Destravem
          Time_to_Value["Ganho em semanas"]
          Conversao["Uplift conversão / ticket"]
          Campanhas["Escala em datas (BF etc.)"]
          Integracao["Integração rápida (APIs)"]
      Saude
        Lidera
          Operacoes_Atendimento["Agendamento, atendimento"]
          Area_Clinica["Protocolos e jornada"]
        Bloqueia
          Privacidade["Dados sensíveis, LGPD"]
          Seguranca["Acesso e auditoria"]
          Juridico["Responsabilidade e consentimento"]
        Evidencias_que_Destravem
          Protecao_Dados["Criptografia, RBAC, auditoria"]
          Padroes["Trilhas e governança"]
          Reducao_Tempo["Tempo de atendimento / no-show"]
          Caso_Saude["Case em saúde"]
      Seguros_Assistencia
        Lidera
          Sinistros["Operação de sinistros"]
          Assistencia["Jornada de assistência"]
          CX["Atendimento e retenção"]
        Bloqueia
          Fraude["Antifraude e risco"]
          Juridico["Cláusulas e evidências"]
          Integracoes["Parceiros e prestadores"]
        Evidencias_que_Destravem
          Reducao_Fraude["Sinais e controles"]
          Tempo_Ciclo["Redução ciclo sinistro"]
          Caso_Seguros["Case em seguradora"]
          SLA_Rede["Controle da rede prestadora"]
      Telecom
        Lidera
          Canais_Digitais["Apps, WhatsApp, voice"]
          Operacoes["Atendimento massivo"]
        Bloqueia
          Seguranca["Fraude, SIM swap, identidade"]
          TI["Legado BSS/OSS"]
          Regulacao["Anatel e compliance"]
        Evidencias_que_Destravem
          Autenticacao["Camadas de autenticação"]
          Escala["Milhões de contatos/mês"]
          Caso_Telecom["Case telecom"]
          Observabilidade["SRE, logs, alertas"]
      Industria_Logistica
        Lidera
          Operacoes["Operação / chão de fábrica"]
          Supply_Logistica["Supply / transporte"]
        Bloqueia
          TI_OT["OT/ICS e restrições"]
          Seguranca["Rede industrial, acesso"]
        Evidencias_que_Destravem
          Reducao_Paradas["Impacto em paradas"]
          Integracao_Sistemas["ERP/WMS/TMS"]
          Caso_Industria["Case industrial/logística"]
      Setor_Publico
        Lidera
          Area_Finalistica["Serviço ao cidadão"]
          TI_Governo["TI e governança"]
        Bloqueia
          Compras_Licitacao["Processo licitatório"]
          Seguranca["Requisitos e normas"]
        Evidencias_que_Destravem
          Conformidade["Requisitos, auditoria, evidências"]
          Escala_Cidadao["Volume e acessibilidade"]
          Caso_Publico["Referência no setor público"]

    03_Solucoes_Produtos_Mapa_de_Compra
      Orquestrador
        Lidera
          CX_Digital["Canais e jornada"]
          TI_Arquitetura["Integrações e padrão"]
        Bloqueia
          Arquitetura["Padronização e legado"]
          Seguranca["Acesso e logs"]
        Evidencias_que_Destravem
          Reducao_Friccao["Menos handoff entre canais"]
          Governanca_Fluxos["Rastreabilidade e auditoria"]
          API_First["Integração por APIs"]
      WhatsApp_e_Voice_IA
        Lidera
          CX_Operacoes["Volume e eficiência"]
          Digital["Canal estratégico"]
        Bloqueia
          LGPD["Consentimento e retenção"]
          Seguranca["Autenticação e fraude"]
        Evidencias_que_Destravem
          POC_Atendimento["TMA/FCR/backlog"]
          Logs_Auditoria["Trilhas e gravações (quando aplicável)"]
          Reducao_Custo["Saving em atendimento"]
      RPA_Automacao
        Lidera
          Operacoes_Backoffice["Processos manuais"]
          PMO_Transformacao["Produtividade"]
        Bloqueia
          TI["Acesso a sistemas"]
          Excecoes_Processo["Processo não padronizado"]
        Evidencias_que_Destravem
          Mapa_Processo["As-is/to-be + regras"]
          Saving_FTE["Economia e compliance"]
          Monitoramento["Evidência e controle"]
      Analytics_e_IA
        Lidera
          DataOffice["Dados e governança"]
          Area_Negocio["Decisão e performance"]
        Bloqueia
          Qualidade_Dados["Base inconsistente"]
          Explicabilidade["Caixa preta"]
        Evidencias_que_Destravem
          Metricas["Baseline + ganho"]
          MLOps["Monitoramento de drift"]
          Explicavel["Regras/explicação"]
      Chatbot
        Lidera
          CX["Autoatendimento"]
          Digital["Experiência do usuário"]
        Bloqueia
          UX_Ruim["Bot genérico"]
          Conteudo["Base de conhecimento fraca"]
        Evidencias_que_Destravem
          Designer_Conversacional["Intenções e fluxos"]
          Handoff_Humano["Fallback e governança"]
          Resultado_Rapido["Deflexão + satisfação"]
      Gestao_Documental_GetDoc
        Lidera
          Operacoes["Documentos e rastreio"]
          Juridico_Compliance["Evidência e controle"]
        Bloqueia
          Acesso_Permissao["Controle de acesso"]
          Retencao["Políticas e versão"]
        Evidencias_que_Destravem
          Trilha_Auditoria["Versionamento e logs"]
          Link_vs_Repositorio["Modelo de referência (link/armazenamento)"]
          Caso_Similar["Case e ganhos"]
      Integracoes_APIs
        Lidera
          TI_Arquitetura["Padronização e sustentabilidade"]
          Dono_Sistema["Prioridade de integração"]
        Bloqueia
          Legado["Limitações técnicas"]
          Governanca["Mudança e dependências"]
        Evidencias_que_Destravem
          Catalogo_APIs["Contrato e documentação"]
          Plano_Rollout["Fases e mitigação"]
          SLA_Suporte["Operação e observabilidade"]
