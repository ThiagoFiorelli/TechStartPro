
# Configurações para execução da aplicação

# Instalar:
* Visual Studio Community;
* Node.js;
* SDK Asp net Core 3.1;
* Git;

# Instalações pela linha de comando
* Após instalar o node.js instalar o CLI do Angular através do comando "npm install -g @angular/cli"
* Após realizar o fork do projeto, acessar a pasta "TechStartPro/TechStartPro/ClientApp/" e executar o comando "npm install" para instalar as dependencias do front-end do projeto.


# Como participar
* Faça um fork deste repositório no Github. Se você não pode criar um fork público deste projeto, faça um repositório privado e adicione permissão de leitura para o usuário abaixo:
  + mgranemann
* Siga as instruções do README.md (este arquivo);
* Candidate-se ao cargo na nossa página de carreiras com o link para o fork no Github.
  + caso ja tenha realizado a candidatura na pagina de carreiras sem o envio do desafio, responda ao e-mail que lhe foi enviado pela equipe do seleção com o link do seu repositório.



# Especificação
Você deve implementar um aplicativo para armazenar dados de produtos e categorias.

1. Receba um CSV com as categorias e importe para o banco de dados

  Dado um arquivo CSV com muitas categorias, você precisa construir um comando para importar os dados para o banco de dados. O arquivo CSV terá o seguinte formato:

> nome
> * Móveis
> * Decoração
> * Celular 
> * Informática
> * Brinquedos

Cada registro de categoria no banco de dados deve ter os seguintes campos:
* id (autogerado)
* nome

Você precisa armazenar os dados das categorias para complementar os dados do produto que serão armazenados posteriormente (consulte o item # 2).


2. CRUD (criar, ler, atualizar e excluir) de produtos:

Você precisa implementar estas ações:
* Criar um produto
* Ler os dados do produto
* Atualizar os dados do produto
* Excluir os dados do produto

Cada registro de produto possui os campos:
* id (autogerado)
* nome
* descrição
* valor
* categorias (um produto pode estar em mais de uma categoria)

Para recuperar um produto, podemos filtrar por 4 campos (ou uma composição desses quatro):
* nome
* descrição
* valor
* categorias
Deve ser possível navegar pelos dados de todos os produtos sem nenhum filtro.

Para criar um produto, será necessário informar os dados abaixo:
* "nome": // Nome do produto;
* “descrição”: // Descrição do produto
* “valor”:// Valor do produto
* “categorias”:// Lista de ids de categorias


# Requisitos do projeto:
1. Pode ser feita em qualquer linguagem de programação que suporte o paradigma de orientação a objetos
2. Utilizar padrões de projeto
3. Boas práticas de desenvolvimento de software
4. Utilizar paradigma de orientação a objetos
5. Utilizar GitHub
6. Camada visual pode ser console, desktop ou web
7. Variáveis, código e strings devem estar todos em inglês.
8. Escreva a documentação do projeto contendo:

>  * Descrição;
>  * Instruções de instalação (configuração) e teste;
>  * Breve descrição do ambiente de trabalho utilizado para executar este projeto (Computador / sistema operacional, editor de texto / IDE, bibliotecas, etc).
>  * Variáveis, código e strings devem estar todos em inglês.
  
# Recomendações
  * Escreva testes! Por favor, faça testes ... nós apreciamos testes <3 ... testes tornam o mundo melhor;
  * Use boas práticas de programação;
  * Use as melhores práticas do git, com mensagens claras;
  * Esteja ciente ao modelar o banco de dados;

# Divirta-se!

