# Projeto 03 - 2020-2

A **Visiona Tecnologia Espacial**  *é a empresa brasileira resultante de uma iniciativa única do Governo brasileiro de estimular a criação de uma empresa integradora na indústria espacial. a Visiona é uma joint-venture entre a Telebras, empresa de economia mista do setor de telecomunicações, e a Embraer, empresa privada líder nos setores aeroespacial e de defesa. A criação da Visiona corresponde a uma das ações selecionadas como prioritárias no Programa Nacional de Atividades Espaciais (PNAE) para atender aos objetivos e às diretrizes da Política Nacional de Desenvolvimento das Atividades Espaciais (PNDAE) e da Estratégia Nacional de Defesa (END)*. (fonte:https://www.visionaespacial.com.br/)

No projeto 03 do segundo semestre de 2020 a Visiona trouxe como proposta o desenvolvimento de um sistema web ETL, que tem a finalidade de extrair de shapefiles dados georeferenciados, transformar e carregar os dados geográficos em banco de dados, de baixo custo
Com a proposta/desafio apresentada pela empresa parceira,  a equipe desenvolveu VisGeo.

![Untitled](https://user-images.githubusercontent.com/56441321/138614599-210672c6-300f-4c2a-9105-70655bae9a8b.png)

A VisGEO então surgiu com o objetivo de ser intuitivo e de baixo custo, sendo uma aplicação web que realiza uma extração de dados georeferenciados de shapefiles, transformando e carregando essas informações para um banco de dados geográfico.
A seguir podemos observar as funcionalidades do sistema. 
Visando a segurança, para acessar as funcionalidade da ferramenta é necessário que todos os usuários sejam cadastrados e autenticados no sistema.
A autenticação no banco de dados ocorre de maneira simples e intuitiva.
O usuário possui autonomia, pois com o sistema DE → PARA para a realização do upload dos shapefiles, ele decide o que será salvo.
E caso não seja necessário realizar a configuração do DE → PARA, pode-se enviar diretamente todas as informações para o banco de dados com apenas um clique.
Na aplicação também é possível também baixar todos os shapefiles salvos no banco de dados.

![API 3](https://user-images.githubusercontent.com/56441321/142759695-0477e41b-9ffa-4cbd-b40a-3f01e57ac86b.jpg)


**Link do github do Projeto**

[https://github.com/JDanrley/VisGeo-ETL](https://github.com/JDanrley/VisGeo-ETL)

### Tecnologias Utilizadas

-	Python:Utilizada em nosso projeto foi utilizada em conjunto com as bibliotecas PyShp e Postgresql para o desenvolvimento do ETL.
-	Flask:Foi utilizado no projeto para auxílio no desenvolvimento das rotas da API REST.
-	Java: Utilizada no projeto conforme requisito não funciona, utilizada no desenvolvimento do CRUD de usuários.
-	Docker: É uma forma de virtualizar aplicações no conceito de “containers”. Utilizado nesse projeto na implementação do banco de dados.
-	PostgreSQL:Sistema gerenciador de banco de dados objeto relacional, escolhido por conter a extensão espacial PostGIS, muito importante para visualização dos dados.
-	PostGIS: Extensão espacial que permite o uso de objetos GIS ser armazenado em banco de dados.
-	ReactJS: Utilizada para o desenvolvimento de todo frontend da aplicação.
-	Styled Components: é uma biblioteca para React que permite use estilos ao nível de componente na sua aplicação. Utilizada para melhoria da qualidade do código e facilidade da sintaxe.


### Contribuições Pessoais

Neste projeto auxiliei no levantamento de requisitos e definição das regras de negócio, na documentação das sprints, explicando a priorização e valores entregues, criação do método e rota de carga de shapefiles de forma automática sem preparação “de-para”

### Hard Skills

•	Documentação do projeto: Sei fazer com autonomia.

•	Tratamento de dados georreferenciados: Sei fazer com ajuda.

•	Desenvolvimento utilizando Python: sei fazer com autonomia.

•	Criação de containers utilizando Docker: sei fazer com ajuda.

### Soft Skill

Neste projeto foram essenciais  as habilidades soft skills como: cooperação, adaptação, organização, foco e responsabilidade
