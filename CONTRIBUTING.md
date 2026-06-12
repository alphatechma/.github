# Guia de Contribuição — AlphaTech

Obrigado por contribuir com os projetos da **AlphaTech**. Este documento resume o fluxo de trabalho que seguimos em todos os repositórios da organização.

## Fluxo de Git

1. **Branch a partir de `develop`.** Nunca trabalhe diretamente em `main` ou `develop`.

   ```bash
   git checkout develop
   git pull origin develop
   git checkout -b tipo/descricao-curta
   ```

   Use prefixos como `feat/`, `fix/`, `chore/`, `docs/` ou `refactor/`.

2. **Faça commits pequenos e descritivos** seguindo o padrão de [Conventional Commits](https://www.conventionalcommits.org/pt-br/):

   ```
   feat(obras): adiciona relatório fotográfico georreferenciado
   fix(auth): corrige expiração de token no refresh
   docs(readme): atualiza instruções de setup
   ```

   Tipos mais usados: `feat`, `fix`, `docs`, `style`, `refactor`, `perf`, `test`, `chore`.

3. **Abra um Pull Request para `develop`.** Preencha o template, descreva o que foi feito e vincule a issue relacionada.

## Revisão de Pull Requests

- Todo PR exige **pelo menos uma revisão aprovada** antes do merge — revisão é obrigatória.
- O autor do PR **não** aprova o próprio PR.
- A pipeline de CI (build, lint e testes) deve passar antes do merge.
- Prefira **Squash and merge** para manter o histórico limpo.

## Antes de abrir o PR

- [ ] O código compila e roda localmente.
- [ ] Testes novos e existentes passam.
- [ ] Lint e formatação aplicados.
- [ ] Documentação atualizada quando necessário.

## Reportando problemas

Use os templates de issue (Bug Report ou Feature Request) e forneça o máximo de contexto possível.

---

Em caso de dúvidas, fale com o time pelo e-mail {{EMAIL}}.
