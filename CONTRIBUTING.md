# Guia de Contribuição e Alteração — Governança MHC

Este guia define os trâmites para propor melhorias, correções e atualizações ao **Código de Conduta** e aos demais documentos de governança do **Madeira Hacker Club (MHC)**.

---

## 1. Tipos de Alteração

### A. Ajustes Formais (Baixo Impacto)
Inclui correções ortográficas, ajustes de formatação em Markdown, atualização de links quebrados ou melhorias de clareza que **não alteram o sentido das regras**.
- **Fluxo:** Abra um **Pull Request (PR)** diretamente na branch `main` descrevendo o ajuste.
- **Aprovação:** Revisão e merge por qualquer pessoa mantenedora do repositório.

### B. Alterações de Mérito (Regras, Pilares, Escopo ou Consequências)
Inclui criação, remoção ou mudança de regras, procedimentos de relato, escopo de aplicação ou atualização de versão (ex.: `V1.0` → `V1.1` / `V2.0`).
- **Fluxo:**
  1. **Discussão prévia (Issue):** Abra uma **Issue** explicando o problema identificado, o contexto e a proposta de redação. Compartilhe o link nos canais oficiais do clube (como o grupo da comunidade e os encontros dos *Domingos Hackers*) para colher opiniões.
  2. **Pull Request:** Após a discussão inicial, envie um **Pull Request** referenciando a Issue (`Closes #N`).
  3. **Janela de revisão:** Aguarde um período mínimo de **7 dias** (ou validação em encontro presencial/assembleia do clube) para que membros possam revisar e comentar.
  4. **Aprovação e versionamento:** Havendo consenso ou deliberação favorável da comunidade/coordenação, o PR é aprovado, atualizando a **Versão** e a data no cabeçalho do documento.

---

## 2. Boas Práticas ao Contribuir

- Escreva em **Markdown padrão** (evite HTML desnecessário para manter a leitura limpa no terminal e no GitHub).
- Mantenha a consistência de nomes: **Madeira Hacker Club (MHC)**.
- Preserve o equilíbrio entre a **clareza institucional** do corpo principal e o respeito às referências comunitárias do clube.
- Caso adicione ou altere imagens em `assets/`, utilize formatos leves e nomes descritivos em minúsculas separados por hífen.

---

## 3. Sincronização Organizacional

O arquivo `CODE_OF_CONDUCT.md` deste repositório (`MadeiraHackerSpace/estatuto`) é espelhado em [`MadeiraHackerSpace/.github`](https://github.com/MadeiraHackerSpace/.github) para que o GitHub o exiba automaticamente em todos os repositórios da organização. Após a aprovação de uma alteração aqui, ela deve ser sincronizada com o repositório `.github`.
