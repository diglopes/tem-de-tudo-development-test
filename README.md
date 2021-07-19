# Teste para Desenvolvedor

Definir as características de um bom software não é fácil, visando que existem diversas formas de chegar em uma mesma solução não existe forma correta ou errada de solucionar um problema, mas podemos afirmar que existem melhores maneiras de se solucionar um problema, adoção de boas praticas e desing patterns que facilita a criação e manutenção de uma ferramenta. 

Este teste se propõe a dar a você candidato a oportunidade de mostrar não só sua capacidade de chegar na solução do desafio proposto, mas também a mostrar seus conhecimentos em aplicar a melhor implementação com boas práticas e escolha das melhores tecnologias. 

Os critérios de avaliação serão os abaixo:

1. Code review.
2. Implementação de novas funcionalidades. 

## O Desafio da Loja Tem de tudo.

![assets/imagem_capa.png](assets/imagem_capa.png)

Celeste é proprietária da Loja Tem de Tudo, loja localizada em Pinheiros - São Paulo. Sua loja iniciou com produtos de papelaria, e hoje vende diversos tipos de produtos. Hoje Celeste tem dois funcionários, porém somente ela irá usar o sistema (não se preocupe com o Login).

Como o espaço físico de seu estabelecimento é pequeno Celeste gostaria de realizar vendas pela internet para os clientes do bairro.

Atualmente Celeste controla tudo relacionado a sua loja em planilhas.

Celeste gostaria que você desenvolvesse um sistema onde ela possa abandonar as planilhas e realizar suas vendas online. 

## As Planilhas

[Produtos](assets/Produtos.csv)

[Clientes](assets/Clientes.csv)

[Vendas](assets/Vendas.csv)

## Os Dados

Através dessas planilhas Celeste extraí os seguintes dados:

- Vendas Semanais (é a soma de todas as vendas)
- Lucro semanal (é a soma das vendas - a soma de todos valores de custo dos produtos vendidos)
- Melhores vendedores (é o vendedor que vendeu o maior valor)
- Melhores clientes (é o cliente que comprou o maior valor)

Lembrando que isso deve ser dinâmico, ou seja, os valores devem ser inseridos e os cálculos atualizados.

## Importante:

Celeste lhe dá total liberdade para que seja criativo e incremente novas funcionalidades além daquelas que ela já possui com as planilhas, seja criativo e se sinta livre para mostrar suas habilidades como desenvolvedor, mas não esqueça de fazer o essencial.

## Comentários:
- Crie a sua API utilizando Node.js e um banco de dados relacional
- Fique a vontade para utilizar outras tecnologias que achar pertinente
- Foque na qualidade e funcionamento das features principas. Garantir um sistema funcional pesa mais do que um sistema totalmente inovador com detalhes que não funcionam.
- Faça uma boa documentação dos endpoints disponibilizados e da própria aplicação

## Entregas:

É necessário você definir, descrever e estimar tempo para tarefas a serem realizadas a partir do escopo do projeto.

Exemplo:

- Criar listagem de produtos com filtro de status
  - BACK - Criar API para consultar produtos com diferenciação de status. - 30 minutos
  - DOC - Documentar API de consultas de produtos com diferenciação de status - 10 minutos

É necessário você desenvolver a ferramenta através das tarefas definidas por você (uma sugestão é criar branches e commits relacionados).

É necessário você subir a aplicação em algum ambiente CLOUD e disponibilizar um link público para os testes (não se esqueça de mostrar seu conhecimento com devops, por exemplo utilizando CD e CI), assim como já ter disponibilizada as configurações parar criar uma imagem docker da aplicação.

É necessário utilizar o Github para versionar (procure realizar pequenos commits durante o desenvolvimento) a aplicação e criar um README.md com descrição da ferramenta e processo de instalação. Disponibilizar repositório para análise.
