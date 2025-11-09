# 🧭 Guia de Continuidade – Orion Academy

## Propósito

Este guia explica **como manter a continuidade pedagógica** entre sessões,
garantindo que o aprendizado, os módulos e as interações com o Professor Orion
mantenham coerência e contexto.

A Orion Academy trabalha com **aprendizado persistente e rastreável**, usando
arquivos de alinhamento armazenados localmente.

---

## Estrutura de Alinhamento

Cada curso ativo contém a pasta:

```tree
/courses/{curso}/alignment/
│
├── state.json
├── context-key.md
├── roadmap.md
└── logs/
```

**Função de cada arquivo:**

- **`state.json`** → Armazena o progresso técnico e pedagógico (módulo atual,
  fase, status).
- **`context-key.md`** → Resumo textual curto que descreve o ponto exato de
  retomada.
- **`roadmap.md`** → Cronograma completo do curso.
- **`logs/`** → Reflexões e registros narrativos por data.

---

## Fluxo de Continuidade

1. **Encerrando uma Sessão**

   - O Professor Orion gera o `context-key.md` com:
     - Resumo do que foi feito;
     - Próximos passos;
     - Data e módulo.
   - O Aprendiz salva e versiona.

2. **Iniciando uma Nova Sessão**

   - O Aprendiz informa:
     > “Retomar do alignment/state.json (curso X, módulo Y, fase Z).”
   - O Professor reconstrói o contexto, lê o `context-key.md` e dá continuidade
     sem perda narrativa.

3. **Persistência**
   - Os arquivos de alinhamento são **a memória externa do curso**.
   - Nenhuma sessão deve iniciar sem leitura deles.

---

## Recomendações

- Use uma sessão por módulo ou submódulo.
- Evite múltiplas conversas paralelas do mesmo curso.
- Sempre encerre uma sessão com o `context-key.md` atualizado.
- Faça commits frequentes no GitHub — isso é o histórico do seu aprendizado.

---

## Princípio Central

> “A continuidade não é lembrar, é rastrear com intenção.”

O sistema Orion confia na rastreabilidade, não na memória volátil. O
conhecimento é construído e salvo como engenharia viva.

---

**Última atualização:** 2025-11-09
