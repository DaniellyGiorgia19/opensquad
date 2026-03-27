---
id: revisao
agent: revisor
execution: inline
model_tier: powerful
inputFile: squads/marketing-pipeline/output/copys-completas.md
outputFile: squads/marketing-pipeline/output/copys-revisadas.md
on_reject: copywriting
---

# Step: Revisão de Textos

## Instruções

1. Leia todos os textos produzidos pelo Copywriter
2. Verifique gramática, ortografia e clareza
3. Valide alinhamento com o brand_profile
4. Corrija e ajuste conforme necessário
5. Marque status de cada peça (Aprovado / Ajustado / Reescrito)

## Veto Conditions
- Erros gramaticais persistentes
- Palavras proibidas presentes no texto
- Tom de voz desalinhado

## Output
Salvar textos revisados em `squads/marketing-pipeline/output/copys-revisadas.md`
