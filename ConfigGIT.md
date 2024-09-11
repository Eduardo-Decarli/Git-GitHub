# Comandos de Configurações

**git config --global --list**  
Lista todas as configurações globais do dispositivo.

---

**git config --global user.name "Seu Nome"**  
Define o nome default do dispositivo. Substitua "Seu Nome" pelo nome que você deseja que apareça nos commits.

---

**git config**  
Comando usado para definir configurações no Git.

---

**--global**  
Aplica a configuração a todos os repositórios no sistema. Se você omitir o --global, a configuração será aplicada apenas ao repositório atual.

---

**git config --global user.email "seu-email@exemplo.com"**  
Configura o e-mail default utilizado pelo dispositivo. Substitua "seu-email@exemplo.com" pelo e-mail que deseja usar nos commits.

---

**git config --global init.defaultBranch main**  
Declara que todo repositório iniciado no Git terá a branch `main` como padrão, em vez de `master`.

---

**git config alias.log1 "log --oneline"**  
Cria um alias para `log --oneline`. Agora, você pode usar `git log1` para o mesmo comando.