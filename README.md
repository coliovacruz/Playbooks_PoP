# Residência Tecnológica em Resposta a Incidentes de Segurança - PoP-BA / RNP

Este repositório reúne os documentos, playbooks operacionais, planos de contingência e modelos de gestão desenvolvidos durante a Residência Tecnológica do Programa **Hackers do Bem** junto ao **Ponto de Presença da RNP na Bahia (PoP-BA)**.

---

## 🗂️ Estrutura do Repositório

```text
.
├── README.md
├── docs/
│   ├── relatorios/
│   │   ├── Relatorio_FINAL_Marco_Aurelio_Cruz.pdf
│   │   └── Apresentacao_Banca.pdf
│   ├── planos/
│   │   └── Plano_de_Resposta_a_Incidentes.md
│   └── treinamento/
│       └── Treinamento_Equipe_PoP-BA.pdf
├── playbooks/
│   ├── ddos/
│   │   ├── Playbook_DDoS.md
│   │   └── templates/
│   │       └── notificacao_cliente_ddos.txt
│   └── exploracao_varredura/
│       ├── Playbook_Varredura.md
│       └── templates/
│           └── notificacao_varredura.txt
└── templates/
    ├── cadeia_de_custodia.md
    └── relatorio_pos_incidente.md
```

---

## 📘 Resumo dos Documentos

- **[Plano de Resposta a Incidentes](docs/planos/Plano_de_Resposta_a_Incidentes.md):** Diretrizes de governança, papéis, responsabilidades e ciclo de vida NIST SP 800-61r3 / ISO 27035.
- **[Playbook de Resposta a DDoS](playbooks/ddos/Playbook_DDoS.md):** Procedimentos operacionais padrão para contenção e mitigação de ataques volumétricos e direcionados à infraestrutura de roteamento do PoP-BA.
- **[Playbook de Exploração e Varredura](playbooks/exploracao_varredura/Playbook_Varredura.md):** Triagem, classificação de severidade e resposta para varreduras de rede e tentativas de exploração.
- **[Cadeia de Custódia Forense](templates/cadeia_de_custodia.md):** Formulário padronizado para preservação e integridade de evidências digitais.
- **[Relatório Pós-Incidente](templates/relatorio_pos_incidente.md):** Modelo de documentação de lições aprendidas e análise pós-evento.

---

**Autor:** Marco Aurélio da Silva da Cruz  
**Instituição:** Ponto de Presença da RNP na Bahia (PoP-BA) / Programa Hackers do Bem  
