git --version -> Verifica a versão do Git instalada
git help -> Mostra todos os comandos e uma versão resumida do que eles fazem
git help comando -> Mostra a documentação completa do que aquele comando faz
git init -> Cria a pasta .git no projeto e começa a rastrear as modificações
git status -> Verifica o Status do rastreio
git add . -> Adiciona todos os arquivos a area de commit
git add arquivoEspecifico -> Adiciona um arquivo em especifico para a area de commit
git rm --cached arquivoEspecifico -> remove o arquivo da area de commit
git reset -> reseta a area de commit, retirando todos os arquivos.
git commit -m "" -> Realiza um commit, a mensagem do commit é definida dentro das aspas duplas
git diff -> Mostra as diferenças entre duas versões do arquivo
git log -> Mostra o histórico de commits realizados, esse comando mostra um maior detalhamento entre os commits
git log --oneline -> Versão resumida para poder-se visualizar o histórico de commits em apenas uma linha
git commit -a -m "" -> Realiza um commit pulando a area de stage(Esse comando serve apenas para arquivos modificados, e não para arquivos criados ou deletados)
git restore nomeDoArquivo -> Restaura o arquivo para a versão de um commit anterior
git mv nomeDoArquivo1 nomeDoArquivo2 -> Mostra para o Git que um arquivo foi renomeado