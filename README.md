# Subindo meu primeiro projeto no GitHub
Este repositório contém o código e instruções para realizar o upload do seu primeiro projeto no GitHub. O projeto foi desenvolvido como parte do curso da DIO (Digital Innovation One) e tem como objetivo guiar os iniciantes no processo de versionamento de código utilizando a plataforma GitHub.

# 📋 Pré-requisitos
Antes de começar, você precisará instalar e configurar o seguinte:

Git: sistema de controle de versões. Clique [aqui para baixar.](https://git-scm.com/)

Conta no GitHub: se ainda não tem uma, crie em [GitHub](https://github.com/).

Visual Studio Code (ou qualquer outro editor de código). [Clique aqui para baixar](https://code.visualstudio.com/).


# 🚀 Começando
 
Siga os passos abaixo para subir seu projeto no GitHub:

1. Crie um novo repositório no GitHub
Acesse o GitHub e clique em New Repository.
Escolha um nome para o seu repositório (ex: meu-primeiro-projeto).
Defina se ele será público ou privado.
Clique em Create Repository.

3. Inicialize o Git no seu projeto local. No terminal, vá até o diretório do seu projeto e execute os seguintes comandos:

bash

`git init`

Isso inicializará um novo repositório Git local.

3. Adicione seus arquivos ao repositório
 
Use o comando abaixo para adicionar todos os arquivos do seu projeto:

bash

`git add .`

4. Faça o commit das suas alterações
   
Agora, crie um commit para salvar essas alterações no histórico do Git:

bash

`git commit -m "Meu primeiro commit"`

5. Adicione o repositório remoto
   
Agora, conecte seu repositório local ao repositório remoto no GitHub:

bash

`git remote add origin https://github.com/SEU-USUARIO/meu-primeiro-projeto.git`

6. Envie seu projeto para o GitHub
   
Finalmente, envie seus arquivos para o repositório remoto:

bash

`git push -u origin master`

# 📚 Referências

[Guia do Git e GitHub](https://www.youtube.com/watch?v=xEKo29OWILE)

[Documentação do Git](https://www.youtube.com/watch?v=xEKo29OWILE)

[Plataforma DIO](https://www.dio.me/)
