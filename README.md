
# Configurações para execução da aplicação

# Instalar o seguintes arquivos
* Visual Studio Community;
* Node.js;
* SDK Asp net Core 3.1;
* Git;

# Instalações pela linha de comando
* Após instalar o node.js instalar o CLI do Angular através do comando "npm install -g @angular/cli";
* Após realizar o fork do projeto, acessar a pasta "TechStartPro/TechStartPro/ClientApp/" e executar o comando "npm install" para instalar as dependencias do front-end do projeto.


# Configurar o banco de dados local através do Migration
* Dar o comando Build na solução para verificar se não existem erros;
* Abra o Package Manager Console (no VS Tools >> NuGet Package Manager >> Package Manager Console);
* No Package Manager Console executar o comando "Add-Migration Initial" e depois "Update-Database" para criar e mapear as estruturas no banco de dados local.

Após isso é só navegar pelas telas Categorias, para importar um arquivo .csv que gerará um objeto no banco de dados, e Produtos, para criar, editar, e deletar produtos.
  
