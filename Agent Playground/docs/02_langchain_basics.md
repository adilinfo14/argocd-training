# LangChain – Concepts fondamentaux

## Contexte
LangChain est la brique de base des agents IA.
Il permet de structurer la relation entre un LLM, des instructions et des actions.

## Concepts clés
- Agent : LLM + règles + boucle de décision
- Prompt structuré : rôle, règles, format
- Chain : enchaînement d’étapes

## Ce que j’ai compris
Un agent n’est pas un prompt unique.
C’est un système qui contraint le LLM.

## Points de vigilance
- Laisser le LLM improviser = hallucinations
- Trop de liberté = comportements instables