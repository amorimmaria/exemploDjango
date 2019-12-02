# exemploDjango
Tutorial de Django para a disciplina de PWeb.
Link do tutorial: https://docs.djangoproject.com/pt-br/2.2/intro/tutorial01/

# Framework Django
Django é um framework para aplicações web gratuito e de código aberto, escrito em Python. Um web framework é um conjunto de componentes que ajuda você a desenvolver sites de forma mais rápida e fácil.

# Padrão arquiteturial MTV
 - Como Funciona o MVT
O MVT separa estruturalmente o projeto do software em três partes:

Model;
View;
Template.
- Model
As Models do MVC e do MVT são equivalentes em responsabilidades. O framework Django facilita na interface com o banco de dados. Cada classe da modelo se compara a uma tabela do banco de dados, e as instâncias destas classes, representam os registros destas tabelas. Para adicionar valores ao banco, basta definí-los nas respectivas variáveis. Esta camada contém qualquer coisa e tudo sobre os dados: como acessá-lo , como validá-lo , quais comportamentos que tem e as relações entre os dados. Para o mapeamento dos dados, não será necessário utilizar códigos em SQL para garantir a persistência dos dados no banco.

- View
A camada View é responsável pela implementação das regras de apresentação e negócio do nosso sistema. É nela onde iremos nos comunicar com a Model e a Template, cadastrando e tratando as informações recebidas. Retornando para o usuário uma resposta, como HTMLs, XML, ou erros encontrados.

- Template
Templates é a camada que retorna a visão para o usuário do programa. Essa camada é composta por, HTML,CSS, javascript e etc. Geralmente linguagens focadas na apresentação do site para o usuário.


# Referências
 - https://tutorial.djangogirls.org/pt/django/
 - https://github.com/fga-eps-mds/A-Disciplina/wiki/Padrões-Arquiteturais---MVC-X-Arquitetura-do-Django

