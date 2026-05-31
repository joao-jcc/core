# Core - Sistema de Gestão de Projetos

## Estrutura do Projeto

Esta pasta contém todos os meus projetos, reuniões, tarefas e informações organizadas em arquivos Markdown.

**Convenção de diretórios:**
```
core/
├── projetos/           # Subpastas com um projeto cada
│   └── [nome-projeto]/
│       ├── README.md   # Descrição e status geral
│       └── tarefas.md  # Tarefas específicas do projeto
├── reunioes/          # Registros de reuniões
├── tarefas/           # Tarefas gerais/pessoais
└── inbox/             # Anotações rápidas
```

## Como Interpretar Arquivos

### Status de Tarefas
- `[ ]` = Não iniciada
- `[x]` = Concluída
- `[~]` = Em progresso
- `[!]` = Bloqueada
- `[?]` = Aguardando feedback

### Prioridades
- `🔴 CRÍTICA` = Hoje, antes de tudo
- `🟠 ALTA` = Esta semana
- `🟡 MÉDIA` = Este mês
- `⚪ BAIXA` = Futura

### Status de Projetos
- `🟢 ATIVO` = Trabalhando agora
- `🟡 PAUSADO` = Temporariamente parado
- `🔴 BLOQUEADO` = Não pode prosseguir
- `⚪ PLANEJAMENTO` = Ainda não iniciado
- `✅ CONCLUÍDO` = Finalizado

## Comandos Úteis

Quando perguntado, você pode:

### "Quais são as tarefas para hoje?"
1. Procure por tarefas com `🔴 CRÍTICA`
2. Procure por tarefas com data de hoje ou "hoje"
3. Procure por `[~]` (em progresso)
4. Liste em ordem de prioridade e urgência

### "Qual é o estado de cada projeto?"
1. Leia o `README.md` de cada projeto em `projetos/`
2. Extraia o status (🟢 🟡 🔴 etc)
3. Mostre: Nome | Status | Progresso | Próximos Passos

### "O que aconteceu em [projeto]?"
1. Procure em `projetos/[projeto]/README.md`
2. Leia as tarefas relacionadas
3. Resuma as atividades recentes e contexto

### "Resumo da semana"
1. Revise tarefas concluídas (com `[x]`)
2. Mostre tarefas em progresso
3. Identifique bloqueios
4. Sugira prioridades para próxima semana

## Dicas para Claude

- **Sempre ler múltiplos arquivos**: Uma visão completa exige verificar relacionados
- **Respeitar contexto temporal**: Se há data nos arquivos, considere data de hoje (2026-05-31)
- **Ser conciso**: Resuma em formato legível (listas, tabelas quando possível)
- **Sugerir ações**: Ao final, sugira próximos passos ou chamadas à ação
- **Perguntar quando ambíguo**: "Encontrei X tarefas para hoje, mas há Y bloqueadas - quer que inclua essas?"

## Preferências

- Responda sempre em **português brasileiro**
- Use emojis para rápida visualização
- Agrupe por projeto quando relevante
- Destaque apenas o que realmente importa agora
