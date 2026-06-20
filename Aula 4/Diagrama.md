# Diagrama — Aula 04: TI nas Organizações

## Estrutura funcional da área de TI

```mermaid
flowchart TD
    TI[Área de TI]

    TI --> INF[Infraestrutura]
    TI --> DEV[Desenvolvimento de Sistemas]
    TI --> SUP[Suporte Técnico]
    TI --> SEG[Segurança da Informação]
    TI --> GD[Gestão de Dados]

    INF --> I1[Servidores, redes e armazenamento]
    DEV --> D1[Criação e manutenção de softwares]
    SUP --> S1[Atendimento e resolução de incidentes]
    SEG --> SE1[Políticas, controles e conformidade]
    GD --> G1[Qualidade, disponibilidade e BI]
```

---

## Modelos de organização da TI

```mermaid
graph TD
    subgraph Centralizado
        C1[Padronização tecnológica]
        C2[Maior governança e controle]
        C3[Menor agilidade por área]
    end

    subgraph Descentralizado
        D1[Autonomia por departamento]
        D2[Proximidade com o negócio]
        D3[Risco de fragmentação]
    end

    subgraph Híbrido
        H1[Infraestrutura central]
        H2[Autonomia parcial das áreas]
        H3[Equilíbrio entre controle e flexibilidade]
    end
```

---

## Funções da TI e sua relação com os objetivos organizacionais

```mermaid
flowchart LR
    F1[Suporte às Operações] --> OBJ[Objetivos Organizacionais]
    F2[Automação de Processos] --> OBJ
    F3[Gestão da Informação] --> OBJ
    F4[Governança e Controle de Riscos] --> OBJ
    F5[Serviços de TI gerenciados] --> OBJ
```

---

## Indicadores da Pesquisa FGV (2025) — uso de TI nas empresas brasileiras

```mermaid
pie title Adoção de tecnologias nas empresas pesquisadas
    "ERP — sistemas integrados de gestão" : 91
    "Computação em nuvem" : 52
    "Outras tecnologias corporativas" : 30
```
