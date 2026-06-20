# Diagrama — Aula 06: CRM (Customer Relationship Management)

## CRM como integrador entre áreas organizacionais

```mermaid
graph LR
    TI[TI\n— integra sistemas\ne centraliza dados] --> CRM[CRM]
    MKT[Marketing\n— gera leads e\nsegmenta públicos] --> CRM
    COM[Comercial\n— gerencia oportunidades\ne conversão] --> CRM
    CRM --> DEC[Decisões orientadas\npor dados sobre o cliente]
```

---

## Objetivos estratégicos do CRM

```mermaid
flowchart TD
    CRM[CRM]

    CRM --> ORG[Organizar Clientes]
    CRM --> REL[Melhorar o Relacionamento]
    CRM --> VEN[Ampliar Vendas]

    ORG --> O1[Centralização de dados em um único sistema]
    ORG --> O2[Histórico completo de interações e compras]

    REL --> R1[Atendimento personalizado]
    REL --> R2[Antecipação de necessidades e fidelização]

    VEN --> V1[Qualificação e priorização de leads]
    VEN --> V2[Gestão e visibilidade do pipeline comercial]
```

---

## Tipos de CRM e suas funções

```mermaid
graph TD
    subgraph CRM Operacional
        OP1[Automação do processo de vendas]
        OP2[Gestão de contatos e histórico]
        OP3[Disparo automático de campanhas]
    end

    subgraph CRM Analítico
        AN1[Segmentação e pontuação de leads]
        AN2[Previsão de vendas e análise de churn]
        AN3[Geração de relatórios e dashboards]
    end

    subgraph CRM Colaborativo
        CO1[Compartilhamento de histórico entre equipes]
        CO2[Atendimento integrado em múltiplos canais]
        CO3[Comunicação interna orientada ao cliente]
    end
```

---

## Funil de vendas e jornada do cliente

```mermaid
flowchart TD
    T[Topo do Funil\n— Atração e descoberta] --> M[Meio do Funil\n— Consideração e qualificação]
    M --> F[Fundo do Funil\n— Decisão e conversão]
    F --> C[Cliente]
    C --> |Retenção e fidelização| POS[Pós-venda e relacionamento contínuo]

    T -.-> TM[Visitantes, interesse inicial, geração de leads]
    M -.-> MM[Leads qualificados, comparação de soluções]
    F -.-> FM[Oportunidades identificadas, negociação, fechamento]
```
