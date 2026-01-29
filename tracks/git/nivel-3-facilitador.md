# Nível 3 — Facilitador (Organização e Automação)

## Objetivo
- Organizar repositórios e fluxos, introduzir boas práticas e automações para
  facilitar onboarding e manutenção.

## Tópicos principais
- Conventional Commits: padrõe de mensagens (`feat:`, `fix:`, `docs:`, etc.).
- `git rebase` vs `git merge`: quando usar cada um para o histórico do repositório.
- Templates de Issue/PR para padronizar contribuições.
- GitHub Projects (Kanban) para priorização e fluxo de trabalho.
- GitHub Actions: criar workflows básicos (linter, testes, checks em PRs).

## Boas práticas
- Definir políticas do repositório (branch protection, revisão obrigatória).
- Documentar o workflow (README CONTRIBUTING.md).
- Automatizar verificações básicas em PRs para reduzir trabalho manual.

## Exercício mínimo
- Adicionar um template de PR e um workflow de GitHub Actions que rode o
  linter em PRs. Validar que o workflow dispara ao abrir um PR.

## Exemplo mínimo de workflow (arquivo):
Crie `.github/workflows/ci.yml` com um job simples que roda um linter ou testes.

## Checklist de conclusão
- [ ] Template de Issue/PR adicionado
- [ ] Workflow de CI básico criado e validado em PR
- [ ] Documentação (`CONTRIBUTING.md`) atualizada com políticas

## Recursos
- Conventional Commits: https://www.conventionalcommits.org
- GitHub Actions docs: https://docs.github.com/actions
