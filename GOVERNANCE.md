# GOVERNANCE

## Papéis
- **Maintainers**: definem diretrizes, revisam PRs, fazem releases.
- **Autores**: contribuem para um paper/projeto específico.
- **Revisores**: fazem code review técnico e de reprodutibilidade.

## Fluxo de trabalho
1. Crie branch: `feat/<slug>` ou `fix/<slug>`
2. Siga Conventional Commits.
3. Abra PR para `dev` (ou diretamente para `main` apenas hotfix).

## Aprovação de PR
- Mínimo de **1 aprovação** de maintainer + **1** autor da área afetada (conforme `CODEOWNERS`).

## Branches
- `main`: protegida; releases e estado publicado.
- `dev`: integração.
- `feat/*`, `fix/*`: desenvolvimento.

## Releases e DOI
- Tag `vX.Y.Z` no hub.
- Para papers, DOI via **Zenodo** no repo do paper (um DOI por release reprodutível).

## Segurança e Ética
- Dados sensíveis fora do Git.
- Checklist em `data/README.md` de cada paper.