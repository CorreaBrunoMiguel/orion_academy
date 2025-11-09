# 📘 Guia de Criação de Curso – Orion Academy

## Propósito

Este documento orienta como criar **novos cursos dentro da Orion Academy**,
mantendo alinhamento com o **Protocolo Geral do Professor (PGP)** e a estrutura
de rastreabilidade.

---

## Estrutura Padrão de Curso

```tree
/courses/{nome-do-curso}/
│
├── README.md
├── protocol-{nome}.md
├── alignment/
│ ├── state.json
│ ├── context-key.md
│ ├── roadmap.md
│ └── logs/
└── modules/
├── 00-intro/
├── 01-fundamentos/
└── ...
```

---

## Passos para Criar um Curso

1. **Defina o Tema e Escopo**

   - Exemplo: _React Pro Developer_
   - Nível: Intermediário → Avançado
   - Objetivo final: Projeto completo, integrando conceitos.

2. **Crie a Estrutura**

   - Copie o modelo acima.
   - Gere um `protocol-{curso}.md` derivado do PGP.
   - Crie o primeiro módulo em `/modules/00-intro/`.

3. **Defina o `roadmap.md`**

   - Liste os módulos, objetivos e projetos práticos.
   - Inclua checkpoints de domínio.

4. **Configure o `state.json`**

   - Inicie com:

     ```json
     {
       "currentModule": "00-intro",
       "currentPhase": "inicial",
       "completedModules": [],
       "notes": "Curso recém-criado"
     }
     ```

5. **Crie o `README.md`**
   - Explique o propósito do curso, público-alvo e resultado esperado.

---

## Diretrizes de Criação

- Nenhum curso deve contradizer o PGP.
- Cada curso precisa ter seu próprio **protocolo didático (PDE)**.
- Cada módulo deve conter teoria + prática + reflexão + avaliação.
- Todos os arquivos devem estar sob versionamento Git.

---

## Princípio de Modularidade

Cada curso é uma arquitetura independente, mas todas compartilham o mesmo DNA
pedagógico.

> “Um curso Orion é um organismo vivo conectado ao mesmo coração: o PGP.”
