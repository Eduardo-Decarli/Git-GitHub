# Comandos Essenciais do Git

---

## 📋 Comandos Gerais

- **git --version**  
  Verifica a versão do Git instalada.

- **git help**  
  Mostra todos os comandos e uma versão resumida do que eles fazem.

- **git help comando**  
  Mostra a documentação completa do que aquele comando faz.

- **git status**  
  Verifica o status do rastreio dos arquivos no repositório.

---

## 🔄 Inicialização 

- **git init**  
  Cria a pasta `.git` no projeto e começa a rastrear as modificações.

- **git remote add origin linkDoRepositorio**
  Adiciona um repositório remoto ao projeto.

- **git remote -v**
  Lista todos os repositórios remotos no projeto.

- **git remote set-url origin linkDoRepositorio**
  Troca o repositorio remoto caso já tenha sido adicionado.

---

## 📝 Adição e Remoção de Arquivos

- **git add .**  
  Adiciona todos os arquivos à área de stage (preparação para commit).

- **git add arquivoEspecifico**  
  Adiciona um arquivo específico à área de stage.

- **git rm --cached arquivoEspecifico**  
  Remove o arquivo da área de stage, sem deletá-lo do diretório.

  **git reset**
  Remove todos os arquivos da área de stage

---

## 🔄 Commit

- **git commit -m "mensagem"**  
  Realiza um commit com a mensagem especificada entre aspas.

- **git commit -a -m "mensagem"**  
  Realiza um commit automaticamente de arquivos modificados, pulando a área de stage (não funciona para novos arquivos).

- **git commit -m "mensagem" --amend**  
  Combina o commit atual com o último commit (usado para ajustar mensagens ou adicionar mudanças).

---

## 📊 Histórico e Diferenças

- **git log**  
  Mostra o histórico detalhado de commits realizados.

- **git log -p**  
  Exibe um histórico mais detalhado, com diferenças entre os commits.

- **git log --oneline**  
  Exibe um histórico resumido de commits em uma única linha por commit.

- **git diff**  
  Mostra as diferenças entre as versões atuais e anteriores dos arquivos.

---

## 🔄 Branch (Ramificações)

- **git branch**  
  Lista as branches locais existentes.

- **git branch nomeDaBranch**  
  Cria uma nova branch com o nome especificado.

- **git checkout nomeDaBranch**  
  Troca para a branch especificada.

  **git switch nomeDaBranch**
  Possui a mesma funcionalidade do checkout, usado para trocar de branch.

- **git branch -d nomeDaBranch**  
  Deleta a branch especificada.

---

## 🚀 Push

- **git push origin main**  
  Envia a b'ranch `main` para o repositório remoto.

- **git push --all**  
  Envia todas as branches locais para o repositório remoto.

- **git push -f**
  Força o envio dos commits locais para o remoto, isso fará o remoto perder qualquer commit dessincronizado com o local.

---

## 🔄 Delete, Reset e Recuperação de Commits

- **git reset**  
  Utilizado para retornar a um commit anterior, desfazendo mudanças.

- **git reset --soft hashDoCommit**  
  Volta a um commit específico, mantendo os commits posteriores em stage.

- **git reset --hard hashDoCommit**  
  Retorna ao estágio de um commit específico, descartando todos os commits posteriores.

- **git restore nomeDoArquivo**  
  Restaura o arquivo para a versão de um commit anterior.

- **git clean -df**
  Descarta todas as alterações feitas desde o ultimo commit.

---

## 📂 Movimentação de Arquivos

- **git mv nomeDoArquivo1 nomeDoArquivo2**  
  Renomeia o arquivo, informando o Git da mudança.

---

## 📝 Editor Vim

- **vim nomeDoArquivo**  
  Abre um arquivo no Vim para edição.

- **:q**  
  Sai do Vim (se não houver mudanças).

- **:q!**  
  Sai do Vim sem salvar as mudanças.

- **:w**  
  Salva o arquivo.

- **:wq**  
  Salva e sai do Vim.
