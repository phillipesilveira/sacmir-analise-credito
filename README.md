# sacmir-analise-credito
Sistema de Análise de Crédito e Mitigação de Riscos para servidores SIAPE (Java + Fullstack Logic).

# 🏦 SACMIR - Sistema de Análise de Crédito e Mitigação de Riscos

> **Status do Projeto:** 🚧 Em Desenvolvimento (Fase de Implementação de Lógica Core)

## 🎯 Sobre o Projeto
O **SACMIR** nasceu de uma necessidade real identificada no setor de crédito consignado. O objetivo é automatizar a validação de margem e análise de risco para servidores públicos (SIAPE), substituindo verificações manuais propensas a erro por um algoritmo seguro e consistente.

O sistema foca em duas vertentes críticas:
1. **Cálculo de Margem:** Validação precisa dos 5% para Cartão de Crédito e Cartão Benefício.
2. **Análise de Risco (Série Temporal):** Varredura dos últimos 6 contracheques para identificar inconsistências de descontos ou variações bruscas nos proventos.

## ⚙️ Regras de Negócio Implementadas
* **Validação SIAPE:** Algoritmo que respeita o teto de 5% sobre o salário líquido/base.
* **Detecção de Anomalias:** O sistema analisa uma lista histórica (6 meses) para alertar se houve falha no desconto da consignatária em meses anteriores (indicativo de risco alto).

## 🛠️ Tecnologias
* **Linguagem Principal:** Java (Foco em POO e Lógica de Negócio).
* **Estrutura de Dados:** Listas e manipulação de objetos para histórico financeiro.
* **Próximos Passos (Roadmap):** - [ ] Interface Web (Frontend).
  - [ ] Leitura automatizada de PDF (Contracheques).

---
*Desenvolvido por Phillipe Silveira como projeto de portfólio focado em soluções para Fintechs.*
