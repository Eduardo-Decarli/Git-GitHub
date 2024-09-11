# Comandos Essenciais do Git

**git --version**  
Verifica a versão do Git instalada.

---

**git help**  
Mostra todos os comandos e uma versão resumida do que eles fazem.

---

**git help comando**  
Mostra a documentação completa do que aquele comando faz.

---

**git init**  
Cria a pasta `.git` no projeto e começa a rastrear as modificações.

---

**git status**  
Verifica o status do rastreio dos arquivos no repositório.

---

**git add .**  
Adiciona todos os arquivos à área de stage (preparação para commit).

---

**git add arquivoEspecifico**  
Adiciona um arquivo específico à área de stage.

---

**git rm --cached arquivoEspecifico**  
Remove o arquivo da área de stage, sem deletá-lo do diretório.

---

**git reset**  
Utilizado para retornar a um commit anterior, desfazendo mudanças.

---

**git commit -m "mensagem"**  
Realiza um commit com a mensagem especificada entre aspas.

---

**git diff**  
Mostra as diferenças entre as versões atuais e anteriores dos arquivos.

---

**git log**  
Mostra o histórico detalhado de commits realizados.

---

**git log -p**  
Exibe um histórico mais detalhado, com diferenças entre os commits.

---

**git log --oneline**  
Mostra um resumo do histórico de commits em uma única linha por commit.

---

**git commit -a -m "mensagem"**  
Realiza um commit automaticamente de arquivos modificados, pulando a área de stage (não funciona para novos arquivos).

---

**git restore nomeDoArquivo**  
Restaura o arquivo para a versão de um commit anterior.

---

**git mv nomeDoArquivo1 nomeDoArquivo2**  
Renomeia o arquivo, informando o Git da mudança.

---

**git commit -m "mensagem" --amend**  
Combina o commit atual com o último commit (usado para ajustar mensagens ou adicionar mudanças).

---

**git reset --soft hashDoCommit**  
Volta a um commit específico, mantendo os commits posteriores em stage.

---

**git reset --hard hashDoCommit**  
Retorna ao estágio de um commit específico, descartando todos os commits posteriores.

---

**git config alias.log1 "log --oneline"**  
Cria um alias para `log --oneline`. Agora, você pode usar `git log1` para o mesmo comando.

---

**git branch**  
Lista as branches locais existentes.

---

**git branch nomeDaBranch**  
Cria uma nova branch com o nome especificado.

---

**git checkout nomeDaBranch**  
Troca para a branch especificada.

---

**git branch -d nomeDaBranch**  
Deleta a branch especificada.

---

**git push origin main**  
Envia a branch `main` para o repositório remoto.

---

**git push --all**  
Envia todas as branches locais para o repositório remoto.
