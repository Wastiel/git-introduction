# 🌟 Comandos Git Essenciais em Git Bash

## Essa seção traz os principais comandos utilizados no git com uma pequena explanação

## 🔑 10 Comandos Mais Usados

```bash
# Abrindo o Git Bash
# 1. Inicializa um novo repositório Git no diretório atual.
# Cria um novo repositório Git, permitindo que você comece a rastrear mudanças em arquivos.
$ git init

# 2. Clona um repositório remoto para o seu ambiente local.
# Baixa todos os arquivos e histórico do repositório remoto para sua máquina local.
$ git clone <url-do-repositório>

# 3. Adiciona arquivos ou diretórios à área de stage, preparando-os para o commit.
# Seletivamente adiciona arquivos para que as mudanças sejam incluídas no próximo commit.
$ git add <arquivo-ou-diretório>

# 4. Registra as mudanças adicionadas com uma mensagem descritiva.
# Cria um novo commit com as alterações que você adicionou à área de stage, documentando as mudanças.
$ git commit -m "mensagem do commit"

# 5. Exibe o estado atual do repositório.
# Mostra quais arquivos foram modificados, quais estão em stage e se há novos arquivos não rastreados.
$ git status

# 6. Atualiza o repositório local com as mudanças do repositório remoto.
# Faz o download das alterações do repositório remoto e as integra ao seu repositório local.
$ git pull

# 7. Envia os commits locais para o repositório remoto.
# Envia suas mudanças para o repositório remoto, tornando-as disponíveis para outros colaboradores.
$ git push

# 8. Mostra o histórico de commits do repositório.
# Exibe uma lista de todos os commits feitos no repositório, mostrando mensagens e IDs dos commits.
$ git log

# 9. Lista todas as branches locais no repositório.
# Mostra uma lista das branches que você possui localmente e destaca a branch atual.
$ git branch

# 10. Altera para a branch especificada.
# Muda o contexto de trabalho para a branch que você especificar, permitindo que você trabalhe em diferentes versões do código.
$ git checkout <nome-da-branch>
```

## 📜 Outros Comandos

```bash
# 11. Mescla a branch especificada na branch atual.
# Combina as alterações de outra branch com a branch atual.
$ git merge <nome-da-branch>

# 12. Mostra os repositórios remotos configurados.
# Exibe os repositórios remotos que estão associados ao seu repositório local.
$ git remote -v

# 13. Exibe as diferenças entre as alterações não comitadas e o último commit.
# Mostra as modificações feitas nos arquivos que ainda não foram comitados.
$ git diff

# 14. Remove arquivos ou diretórios da área de stage.
# Remove um arquivo da área de stage, revertendo a adição anterior.
$ git reset <arquivo-ou-diretório>

# 15. Remove um arquivo do repositório e do sistema de arquivos.
# Exclui um arquivo do repositório e o remove do seu diretório de trabalho.
$ git rm <arquivo>

# 16. Salva temporariamente as alterações não comitadas.
# Armazena suas alterações não comitadas para que você possa trabalhar em algo mais, sem perder seu progresso.
$ git stash

# 17. Cria uma nova tag no commit atual.
# Adiciona uma tag ao commit atual, útil para marcar versões importantes.
$ git tag <nome-da-tag>

# 18. Exibe informações sobre um objeto específico, como um commit ou uma tag.
# Mostra detalhes sobre um commit, tag ou outro objeto referenciado.
$ git show <referência>

# 19. Mostra o histórico de commits de forma compacta.
# Exibe o histórico de commits em uma única linha por commit, facilitando a visualização rápida.
$ git log --oneline

# 20. Exibe o histórico de referências atualizadas no repositório local.
# Mostra um histórico das referências, incluindo commits recentes e mudanças de branch.
$ git reflog
```


## 📘 Comandos Adicionais

```bash
# 21. Aplica as mudanças de um commit específico em outra branch.
$ git cherry-pick <hash-do-commit>

# 22. Reaplica os commits da branch atual sobre a base da branch especificada.
$ git rebase <branch>

# 23. Utiliza busca binária para encontrar o commit que introduziu um bug.
$ git bisect

# 24. Mostra a última modificação de cada linha em um arquivo.
$ git blame <arquivo>

# 25. Remove arquivos não rastreados do diretório de trabalho.
$ git clean -f

# 26. Move ou renomeia um arquivo no repositório.
$ git mv <arquivo-antigo> <arquivo-novo>

# 27. Cria um arquivo compactado com os conteúdos de uma branch ou commit.
$ git archive

# 28. Gerencia repositórios Git incorporados dentro de um repositório pai.
$ git submodule

# 29. Define configurações específicas para o usuário ou repositório.
$ git config
```