# Skills

Repositório de skills (funcionalidades reutilizáveis) para o Claude, construídas a partir de prompts.

## Estrutura

```
skills/
  <nome-da-skill>/
    SKILL.md        # instruções principais (obrigatório)
    ...             # arquivos de apoio opcionais (exemplos, modelos, scripts)
templates/
  SKILL.md          # modelo para criar uma nova skill
index.html          # site TechFix (já existia no repositório)
```

Cada skill é uma pasta dentro de `skills/` com um `SKILL.md`. O cabeçalho (frontmatter) do arquivo
precisa de `name` (letras minúsculas e hífens) e `description` (o que faz e quando usar — é isso que
o Claude lê para decidir quando ativar a skill).

## Criando uma nova skill

1. Copie `templates/SKILL.md` para `skills/<nome-da-skill>/SKILL.md`.
2. Preencha `name`, `description` e as seções com o prompt.
3. Faça commit e push.

## Como usar

- **Claude Code:** copie a pasta da skill para `~/.claude/skills/` (uso pessoal) ou
  `.claude/skills/` de um projeto.
- **claude.ai:** compacte a pasta da skill em `.zip` e envie em *Configurações → Capacidades → Skills*.

## Skills disponíveis

_Nenhuma ainda._
