# ⚡ Cheatsheet de comandos do git

## 🐱‍👤 Comandos essenciais

| Comando | Descrição | Onde atua |
| :--- | :--- | :--- |
| `git init` | Inicializa um repositório local | Local |
| `git status` | Exibe o estado dos arquivoes | Local |
| `git add .` | Envia as alterações para a área de Staging | Staging |
| `git commit -m "msg"` | Salva o histórico com uma mensagem | Repositório |

## 🌿 Comandos de Branching & Remoto

| Comando | Descrição |
| :--- | :--- |
| `git checkout -b <nome>` | Cria e alterna para a nova branch |
| `git push -u origin <nome>` | Sobe a branch local para o GitHub |
| `git push -u origin main` | Atualiza o código local com o remoto |
| `git branch -d <nome>` | Remove uma branch local mesclada | 

## ✔ Checklist de Boas Práticas
- [x] Nunca commitar direto na `main`
- [x] Usar nomes descritivos nas branches (`feature/`, `fix/`, `docs/`)
- [x] Testar o código antes de abrir Pull Request
