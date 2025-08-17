# Comandos Essenciais do Git

#### **Verificação e Preparação**
- `git status`
  > Mostra o estado do seu diretório de trabalho. É o primeiro comando que você deve rodar para saber se há arquivos modificados ou a serem "commitados".

- `git add .`
  > Adiciona todas as modificações (arquivos novos e alterados) para a área de "staging", preparando-as para o próximo commit.

#### **Salvando Alterações**
- `git commit -m "Sua mensagem"`
  > Salva as alterações que estão na área de "staging" no seu repositório local com uma mensagem descritiva.

- `git push`
  > Envia os commits do seu repositório local para o repositório remoto no GitHub.

#### **Sincronizando com o Repositório Remoto**
- `git pull`
  > Puxa as alterações mais recentes do repositório remoto para o seu repositório local.

- `git pull --rebase`
  > Puxa as alterações e as "re-baseia" em cima do seu commit local, criando uma linha do tempo de commits mais limpa.

- `git clone [URL]`
  > Cria uma cópia local de um repositório remoto já existente.

#### **Navegação e Histórico**
- `git branch`
  > Lista todas as branches (ramificações) do seu projeto.

- `git checkout [nome-da-branch]`
  > Muda para a branch que você especificar.

- `git log`
  > Mostra o histórico de todos os commits feitos no repositório.

---

### Comandos Adicionais Úteis

- `git diff`
  > Mostra as diferenças entre o seu diretório de trabalho e a última versão "commitada". Ótimo para revisar mudanças antes de adicionar.

- `git restore [nome-do-arquivo]`
  > Descarta as alterações feitas em um arquivo específico desde o último commit. É um "botão de pânico" útil.

- `git stash`
  > Salva temporariamente as alterações que você não quer commitar no momento, permitindo que você mude para outra branch com um "ambiente limpo".

- `git log --oneline`
  > Exibe o histórico de commits de forma mais compacta e fácil de ler.

- `git commit --amend`
  > Permite alterar a mensagem do seu último commit. Perfeito para corrigir erros de digitação.