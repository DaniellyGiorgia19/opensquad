---
id: qa
agent: qa
execution: inline
model_tier: powerful
inputFile: squads/marketing-pipeline/output/pecas-visuais.md
outputFile: squads/marketing-pipeline/output/relatorio-qa.md
on_reject: design
---

# Step: Validação Final (QA)

## Instruções

1. Receba todas as peças (copy + design)
2. Valide consistência entre texto e visual
3. Confirme alinhamento com campanha e marca
4. Emita relatório com status de cada peça

## Veto Conditions
- Copy e design com mensagens conflitantes
- Objetivo da campanha não atendido
- Marca descaracterizada

## Output
Salvar relatório QA em `squads/marketing-pipeline/output/relatorio-qa.md`
