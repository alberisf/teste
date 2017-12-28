# Versionamento de projetos

Verificar se já existem chaves SSH criadas, para verificar entrar no diretório **~/.ssh** do usuário _git_, ela deve conter
os arquivos **id_rsa** e **id_rsa.pub**.<br>
Se não existirem deve-se gerar as chaves.

Comando para gerar chaves SSH: <br>
**ssh-keygen**

Enviar chave pública (**id_rsa.pub**) para ser adicionada no servidor onde está hospedado o repositório git.

Logo após, entrar na pasta de cada projeto e executar os seguintes comandos:

* **`git init`**
* **`git add .`**
* **`git commit -m 'commit inicial'`**
* **`git remote add origin git@23.251.156.225:/var/www/nome_projeto.git`** 
* **`git push origin master`** 
