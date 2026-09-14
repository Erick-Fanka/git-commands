# ⚡ Cheatsheet de comandos do git

## 🐱‍👤 Comandos essenciais

| Comando | Descrição | Onde atua |
| :--- | :--- | :--- |
| `git init` | Inicializa um repositório local | Local |
| `git status` | Exibe o estado dos arquivoes | Local |
| `git add .` | Envia as alterações para a área de Staging | Staging |
| `git commit -m "msg"` | Salva o histórico com uma mensagem | Repositório |
| `git chekout <arquivo>` | Volta o arquivo para o estado inicial | Local |
| `git restore <arquivo>` | Restaura todas as modificações do arquivo | Local| 

## 🌿 Comandos de Branching & Remoto

| Comando | Descrição |
| :--- | :--- |
| `git checkout -b <nome>` | Cria e alterna para a nova branch |
| `git push -u origin <nome>` | Sobe a branch local para o GitHub |
| `git push -u origin main` | Atualiza o código local com o remoto |
| `git branch -d <nome>` | Remove uma branch local mesclada | Local |
| `git stash` | Move arquivos da modified para uma "gaveta temporária" | Local |
| `git stash list` | Lista as stashs |Local |
| `git stash apply <id>` | Recupera a stash | Local |
| `git stash clear` | Limpando stashs | Local |
| `git stash drop <id>` | Apaga stash especifíca | Local |
| `git tag -a <nome> -m <msg>` | Um "checkpoint" na branch | Local |
| `git push origin <nome>` | Envia a tag selecionada | Repositório |
| `git push origin --tags` | Envia todas as tags | Repositório |

## ✔ Checklist de Boas Práticas
- [x] Nunca commitar direto na `main`
- [x] Usar nomes descritivos nas branches (`feature/`, `fix/`, `docs/`)
- [x] Testar o código antes de abrir Pull Request
