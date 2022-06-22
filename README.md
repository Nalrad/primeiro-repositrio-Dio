# primeiro-repositório-Dio
Tutorial Simples de criação de repositório
## Tutorial para Criação, atualização e sincronização

#### Passos Iniciais

 - Faça o download e instalação do git no seu pc (https://git-scm.com/).

 - Crie uma conta no GitHub (https://github.com/).

 - Crie uma pasta específica para guardar seus arquivos.

 - Acesse a pasta criada com git bash.

 - Configure e-mail: git config --global user.email "usar o mesmo e-mail da conta GitHub".

 - Configure name: git config --global user.name "usar o mesmo nickname da conta GitHub".

   

#### Criação do Repositório

- Acesse sua conta no GitHub, acesse a opção new repository.
- Nomeie o repositório, escolha a opção entre público ou privado, marque a opção "add a README file" e em seguida clique em "Create repository".

#### Atualização

- Na sua página do GitHub acessando o repositório e a opção "edit file". Ao final das alterações clique na opção "commit changes".
- No seu PC: copie o link do repositório na página GitHub.
  - abra  o git bash na pasta criada para salvar seus arquivos.
  - use o comando no git bash: git clone (cole o link do repositório), aperte enter.
  - pronto, agora você tem uma cópia do repositório. Abra e faça as atualizações.

#### Sincronização

- Após as atualizações no repositório local, salve e volte ao git bash e execute os comandos:
  - git add * ou git add .
  - git commit -m "adicione um comentário plausível à atualização".
  - git push origin main ou git push origin master.
  - git status (verifique se todas as ações foram concluídas com êxito).
- Verifique na página GitHub se atualizações foram sincronizadas.
