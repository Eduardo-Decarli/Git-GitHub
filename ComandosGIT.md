git --version -> Verifica a versão do Git instalada
git help -> Mostra todos os comandos e uma versão resumida do que eles fazem
git help comando -> Mostra a documentação completa do que aquele comando faz
git init -> Cria a pasta .git no projeto e começa a rastrear as modificações
git status -> Verifica o Status do rastreio
git add . -> Adiciona todos os arquivos a area de commit
git add arquivoEspecifico -> Adiciona um arquivo em especifico para a area de commit
git rm --cached arquivoEspecifico -> remove o arquivo da area de commit
git reset -> Utilizado para retornar um commit anterior
git commit -m "" -> Realiza um commit, a mensagem do commit é definida dentro das aspas duplas
git diff -> Mostra as diferenças entre duas versões do arquivo
git log -> Mostra o histórico de commits realizados, esse comando mostra um maior detalhamento entre os commits
git log -p -> Histório mais detalhado sobre os antigos commits
git log --oneline -> Versão resumida para poder-se visualizar o histórico de commits em apenas uma linha
git commit -a -m "" -> Realiza um commit pulando a area de stage(Esse comando serve apenas para arquivos modificados, e não para arquivos criados ou deletados)
git restore nomeDoArquivo -> Restaura o arquivo para a versão de um commit anterior
git mv nomeDoArquivo1 nomeDoArquivo2 -> Mostra para o Git que um arquivo foi renomeado
git commit -m "" --amend -> Isso irá juntar o commit atual com o ultimo commit(normalmente utilizado para trocar o nome do ultimo commit)
git reset --soft HasDoCommit -> Retorna o documento a um commit especifico mantendo os commit posteriores
git reset --hard HasDoCommit -> Isso irá retornar o documento ao estágio do commit realizado e descartar todos os outros commits posteriores
git config alias.log1 "log --oneline" -> Armazena um atalho ao git, toda vez que digitar 'log1' o git irá realizar o comando 'log --online'
git branch -> lista as branch locais existentes
git branch nomeDaBranch -> Cria uma nova Branch
git checkout nomeDaBranch -> troca a branch atual para a branch especificada
git branch -d nomeDaBranch -> Comando para deletar a branch especificada
git push origin main -> Envia a branch main para o repositorio remoto
git push --all -> Envia todas as branchs locais para o repositorio remoto