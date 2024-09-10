# Comandos de Configurações

git config --global user.name "Seu Nome" -> Define o nome default do dispositivo

/*
git config -> é o comando usado para definir configurações no Git.

--global faz com que essa configuração seja aplicada a todos os repositórios no sistema. 
Se você omitir o --global, a configuração será aplicada apenas ao repositório atual.

"Seu Nome" deve ser substituído pelo nome que você deseja que apareça nos commits.
*/

git config --global user.email "seu-email@exemplo.com" -> Configura o email default utilizado pelo dispositivo

git config --global --list -> Lista todas as configurações globais do dispositivo

Git config --global init.default branch main -> Declara que todo repositório iniciado no git terá a branch main como padrão