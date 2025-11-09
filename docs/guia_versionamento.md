# 🔁 Guia de Versionamento – Orion Academy

## Propósito

Manter rastreabilidade e clareza nas evoluções de protocolos, cursos e módulos.

---

## Padrão de Versionamento Semântico

Usamos a convenção **MAJOR.MINOR.PATCH**

- **MAJOR (1.x)** → Mudanças estruturais profundas.
- **MINOR (x.1)** → Adição de seções, novos módulos, ajustes pedagógicos.
- **PATCH (x.x.1)** → Correções menores ou melhorias textuais.

---

## Exemplo

| Versão  | Descrição                          |
| ------- | ---------------------------------- |
| `1.0.0` | Versão inicial do protocolo        |
| `1.1.0` | Adicionado guia de continuidade    |
| `2.0.0` | Revisão total da metodologia Orion |

---

## Versionamento de Cursos

Cada curso tem seu próprio versionamento, registrado no topo do `README.md` e no
`roadmap.md`.

Exemplo:

```txt
Versão: 1.2
Última atualização: 2025-11-09
Status: Ativo
```

---

## Versionamento de Protocolos

Cada protocolo tem um arquivo de changelog:

```tree
/protocols/PGP_changelog.md
```

### Modelo:

v1.1 – 2025-12-01:

- Adicionado novo princípio pedagógico sobre aprendizado colaborativo.
- Ajuste de terminologia em seção 5.2.

---

## Boas Práticas

- Atualize sempre que houver **mudança de lógica**, não apenas de texto.
- Registre o **porquê** de cada mudança.
- Mantenha logs limpos, datados e descritivos.

> “Versionar é respeitar a história da sua própria evolução.”
