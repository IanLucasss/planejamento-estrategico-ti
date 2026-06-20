# Diagrama — Aula 05: Estratégia Competitiva (Porter, 1997)

## As Cinco Forças Competitivas de Porter

```mermaid
flowchart TD
    RC[Rivalidade entre\nConcorrentes Estabelecidos]

    NE[Ameaça de\nNovos Entrantes] --> RC
    PB[Poder de Barganha\ndos Compradores] --> RC
    PF[Poder de Barganha\ndos Fornecedores] --> RC
    PS[Ameaça de Produtos\nou Serviços Substitutos] --> RC

    RC --> LUC[Lucratividade\nda Indústria]
```

---

## Estratégias genéricas de Porter

```mermaid
graph TD
    EG[Estratégias Genéricas]

    EG --> LC[Liderança em Custos]
    EG --> DIF[Diferenciação]
    EG --> FOC[Foco — Nicho de Mercado]

    LC --> L1[Eficiência operacional e economia de escala]
    LC --> L2[Competição por preço sem comprometer margens]

    DIF --> D1[Atributos únicos percebidos pelo mercado]
    DIF --> D2[Marca, tecnologia, qualidade ou serviço]

    FOC --> F1[Segmento específico de clientes ou região]
    FOC --> F2[Pode combinar foco em custo ou diferenciação]
```

---

## Aplicação ao Projeto Integrador — sistema de monitoramento industrial IoT

```mermaid
flowchart TD
    subgraph Cinco Forças no setor de automação industrial
        NE2[Novos Entrantes:\nstartups de IoT e plataformas open-source]
        RV2[Rivalidade:\nsoluções SCADA e MES tradicionais]
        PB2[Compradores:\nindústrias exigem ROI e escalabilidade]
        PF2[Fornecedores:\npoucos fabricantes globais de chips e sensores]
        PS2[Substitutos:\nAWS IoT, Azure IoT Hub, Google Cloud IoT]
    end

    subgraph Posicionamento estratégico do projeto
        EST[Foco com Diferenciação]
        EST --> E1[Nicho: empresas industriais de médio porte]
        EST --> E2[Custo acessível com tecnologias abertas — ESP32, MQTT]
        EST --> E3[Integração com sistemas legados existentes]
        EST --> E4[Via gradual de entrada na Indústria 4.0]
    end
```
