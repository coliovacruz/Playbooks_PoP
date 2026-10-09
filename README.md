# Capacidade de Resposta a Incidentes — PoP-BA/RNP

Trabalho desenvolvido na **Residência Tecnológica em Resposta a Incidentes e Forense Computacional**, programa **Hackers do Bem** (RNP / MCTI / Softex / SENAI), junto ao **PoP-BA — Ponto de Presença da RNP na Bahia**.

- **Autor:** Marco Aurelio Cruz (Residente Tecnológico)
- **Mentoria:**
- **Período:** Set/2025 – Fev/2026

## Contexto

O PoP-BA é infraestrutura crítica de conectividade: atende 50+ instituições de ensino e pesquisa e cerca de 150 mil usuários finais. Um incidente de rede tem efeito cascata imediato. O objetivo do projeto foi **formalizar e elevar a maturidade da resposta a incidentes**, com processo estruturado, playbooks operacionais e capacitação da equipe.

## Metodologia

1. **Levantamento de dados** — OSINT + entrevista estruturada com gestores (roteiro cobrindo o ciclo de vida do NIST)
2. **Análise quantitativa** — matriz de risco Probabilidade × Impacto (escala 1–5), com a prioridade do cliente como critério de desempate
3. **Validação operacional** — playbooks ajustados às capacidades técnicas reais do PoP-BA
4. **Desenvolvimento iterativo** — playbooks revisados com mentor e equipe
5. **Entrega normativa** — relatório, plano, playbooks e treinamento

## Entregas

| # | Entrega | Pasta |
|---|---------|-------|
| 1 | Relatório de análise inicial (diagnóstico, 9 cenários de risco) | [`docs/relatorio`](docs/relatorio) |
| 2 | Playbook de **DDoS** | [`playbooks/ddos`](playbooks/ddos) |
| 3 | Playbook de **Exploração/Varredura** | [`playbooks/exploracao-varredura`](playbooks/exploracao-varredura) |
| 4 | **Plano formal de resposta a incidentes** | [`plano-resposta-incidentes`](plano-resposta-incidentes) |
| 5 | **Programa de capacitação** (treinamento da equipe e simulações) | [`treinamento`](treinamento) |
| — | Templates de comunicação e matriz de risco | [`templates-comunicacao`](templates-comunicacao), [`matriz-risco`](matriz-risco) |

## Priorização de riscos (resumo)

| Ordem | Tipo de incidente | P | I | P×I |
|-------|-------------------|---|---|-----|
| 1º | DoS/DDoS | 5 | 3 | 15 |
| 2º | Exploração / varredura | 5 | 2 | 10 |
| 3º | Phishing / engenharia social | 2 | 3 | 6 |
| 4º | Comprometimento de site / aplicação web | 2 | 3 | 6 |
| 5º | Ransomware | 1 | 5 | 5 |

## Referências normativas

- NIST SP 800-61 Rev. 3
- ISO/IEC 27035-1:2023
- LGPD — Lei nº 13.709/2018
- MITRE ATT&CK
- ISO 31000 (gestão de riscos)

## Estrutura do repositório

```
.
├── docs/
│   ├── relatorio/          # Relatório técnico final (versão pública/sanitizada)
│   └── apresentacoes/      # Apresentação da banca e treinamento da equipe
├── playbooks/
│   ├── ddos/
│   └── exploracao-varredura/
├── plano-resposta-incidentes/
├── templates-comunicacao/
├── matriz-risco/
├── treinamento/
└── SANITIZACAO.md          # Checklist antes de publicar
```

## Aviso

Este repositório contém material derivado de um trabalho realizado para uma instituição real. Consulte [`SANITIZACAO.md`](SANITIZACAO.md) antes de qualquer publicação.

O relatório técnico final está marcado como **"Documento RESERVADO — uso interno"**.
