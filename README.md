codeigniter_pt-br
=================

CodeIgniter - Translation Project PT-BR

Projeto de tradução do Guia do Usuário do CodeIgniter para Português do Brasil.



Como usar o GIT para o GitHub:
-----------------------------------------

PRIMEIRO, CRIE SUA CHAVE:
-------------------------
Confira se vc já tem alguma chave com um "ls ~/.ssh/", se já existir uma você pode utilizá-la ou gerar uma nova:

1
ssh-keygen -t rsa -C "comment"
"comment" é só um lembrete para saber do que se trata a chave, normalmente usa-se o seu nome de usuário do serviço que vai usar, por exemplo o github.

Acesse https://github.com/account, clique em "SSH Public Keys" e "add another public key".
A cópia da chave precisa ser exata. Copie todo o conteúdo do arquivo id_rsa.pub em seu computador e cole-o na SSH Public Keys do GitHub.

Teste se ficou ok:
Insira o comando abaixo e forneça sua senha quando solicitada:
ssh git@github.com


NA PRIMEIRA VEZ QUE FOR SE COMUNICAR COM O GITHUB:
-------------------------
1. Crie uma pasta onde irão ficar os arquivos. Por exemplo: codeigniter_pt-br

2. Acesse a pasta que acabou de criar. Digite cd codeigniter_pt-br

3. Digite o comando a seguir para iniciar o repositório: git init
Deve aparecer no seu terminal: Initialized empty Git repository in ~/nomedodiretoriodoprojeto/.git/

4. Digite: git remote add origin git@github.com:SEU-USUARIO/codeigniter_pt-br.git . Ao invés de SEU-USUARIO, informe seu usuário no GitHub.

5. Puxe os arquivos para a máquina local OU para fazer merge com o comando a seguir:
git pull origin master 

6. Para baixar novos arquivos sem merge, digite: git fetch origin master

7. Adicione os arquivos ao GitHub:
Para adicionar um arquivo ao controle de versão
git add <Arquivo>

OU para adicionar todo o conteúdo do diretório
git add .

8. Digite git commit -m "Mensagem descrevendo o commit". Informe aqui o que você está commitando. Seja claro!

9. Levar as suas modificações ao controle de versão:
git push origin master 


A PARTIR DA SEGUNDA VEZ QUE FOR SINCRONIZAR COM O GITHUB:
-------------------------

1. Obtenha as alterações e faça merge:
git pull origin master 

2. Adicione os novos arquivos:
git add <Arquivo>

OU adicione todo o diretório
git add .

3. Digite git commit -m "Mensagem descrevendo o commit". Informe aqui o que você está commitando. Seja claro!

9. Levar as suas modificações ao controle de versão:
git push origin master 


=====================================
Atenção: é uma boa prática fazer o MERGE antes de levar as suas alterações ao controle de versão.
------------------------------------------------------------------------
