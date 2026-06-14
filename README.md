# 🏛️ As 8 Regras que Todo Agente de IA Deve Seguir

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![YAML](https://img.shields.io/badge/policy-YAML-blue.svg)](CONSTITUICAO.yaml)
[![DevOS](https://img.shields.io/badge/plataforma-DevOS-orange.svg)](https://devosplatform.com)

**1 arquivo YAML. 8 regras. Governança real para agentes de IA.**

---

## Por que isso existe?

Agentes de IA autônomos estão rodando em produção — tomando decisões, acessando bancos, executando comandos. Mas ninguém definiu as regras do jogo.

A **Constituição DevOS** é um contrato entre humanos e IAs. Transparente, auditável, e sem guardrails invisíveis.

Não é um whitepaper. É um arquivo YAML que você coloca no raiz do seu projeto e o agente obedece.

---

## As 8 Regras

| # | Regra | Nível |
|---|-------|:-----:|
| R1 | **Soberania dos Dados** — Dados nunca saem do cluster | 🔴 HARD |
| R2 | **Audit Trail Imutável** — Toda ação registrada e assinada | 🔴 HARD |
| R3 | **Human Gate Obrigatório** — Ações destrutivas exigem humano | 🔴 HARD |
| R4 | **Transparência Radical** — Nada de guardrails invisíveis | 🔴 HARD |
| R5 | **Compliance por Design** — LGPD, setorial e regulatório nativos | 🟡 SOFT |
| R6 | **Orquestração Declarativa** — Política em YAML, não em código | 🟡 SOFT |
| R7 | **Custo Consciente** — Modelos locais primeiro, APIs só quando necessário | 🟡 SOFT |
| R8 | **Melhoria Contínua** — Toda correção vira regra, toda regra é testada | 🟡 SOFT |

---

## Uso (30 segundos)

```bash
wget https://raw.githubusercontent.com/devosplatform/constituicao-agentes-ia/main/CONSTITUICAO.yaml
```

Cole no raiz do seu projeto. Qualquer policy engine compatível lê e aplica.

---

## Contexto

Este arquivo governa os agentes do **DevOS** — uma plataforma de orquestração de IA multi-agente com:
- 4 agentes especializados (POTÊNCIA, LUNA, BISTURI, CORTEX)
- 50+ skills empacotadas
- Infraestrutura local-first, zero exfiltração de dados
- Stack: DeepSeek V4 + Hermes Agent + MQTT + Linux

Mas as regras são **universais**. Funcionam para qualquer agente autônomo — CrewAI, AutoGen, LangGraph, ou seu próprio script.

---

## Licença

MIT — use, modifique, contribua. Se melhorar alguma regra, abra um PR.

---

**[devosplatform.com](https://devosplatform.com)** — Harness Engineering Platform
