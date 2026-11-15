# Guia de Contribuição

Obrigado pelo interesse em contribuir com este projeto! Toda ajuda — seja reportando falhas, sugerindo melhorias, revisando documentação ou enviando código — é muito bem-vinda.

---

## Como Contribuir

### 1. Reportando Bugs
Antes de abrir um novo relato, pesquise nas **Issues** abertas e fechadas para verificar se o problema já foi registrado.
- Caso não exista, clique em **New issue** e selecione o formulário **Relatar um Bug**.
- Preencha todos os campos obrigatórios, incluindo versão utilizada, ambiente/sistema operacional, passos exatos para reproduzir e logs de erro (sem dados sensíveis).

### 2. Sugerindo Funcionalidades
Tem uma ideia de melhoria ou novo recurso?
- Clique em **New issue** e selecione **Sugerir uma Funcionalidade**.
- Explique claramente o problema atual que a sugestão resolve e o comportamento esperado.

### 3. Enviando Pull Requests (Código ou Documentação)
1. Faça um **Fork** deste repositório e crie uma branch a partir da `main`:

```bash
git checkout -b feat/nome-da-sua-melhoria
```

2. Faça alterações focadas e objetivas. Evite misturar correções de bugs distintos ou refatorações não relacionadas no mesmo Pull Request.
3. Teste suas alterações localmente garantindo que não quebrem funcionalidades existentes.
4. Abra o **Pull Request** preenchendo o checklist padrão e vinculando a Issue correspondente (`Closes #numero-da-issue`).

---

## Padrão de Commits

Utilizamos o padrão **Conventional Commits** para manter o histórico limpo e facilitar a geração de changelogs:

- `feat:` nova funcionalidade (ex.: `feat: adiciona suporte a cache em disco`)
- `fix:` correção de bug (ex.: `fix: corrige validação de cabeçalho HTTP`)
- `perf:` melhoria de desempenho (ex.: `perf: otimiza consulta SQL na listagem`)
- `refactor:` refatoração de código sem alterar comportamento
- `docs:` alterações apenas na documentação
- `chore:` tarefas de manutenção, dependências ou build

---

## Diretrizes Gerais

- Mantenha o código simples, legível e alinhado à arquitetura existente no repositório.
- Nunca inclua chaves de API, senhas, tokens ou arquivos temporários de ambiente nos commits.
- Mantenha uma comunicação respeitosa, técnica e construtiva nas discussões.
