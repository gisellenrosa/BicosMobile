# Especificações do Projeto

A definição exata do problema e os pontos mais relevantes a serem tratados neste projeto foi consolidada com a participação dos usuários em um trabalho de imersão feita pelos membros da equipe a partir da coleta de dados dos usuários em seu local natural. Os detalhes levantados nesse processo foram consolidados na forma de personas e histórias de usuários.

## Personas

|    `Nome`: Juliana Silveira Brancis  | `Profissão`: Desempregada       |     `Idade`: 38 Anos    |
|--------------------|------------------------------------|----------------------------------------|
| <img width="250" alt="image" src="https://user-images.githubusercontent.com/55036173/188963711-7db4ab2c-ea9d-4674-83e6-b1c8f8f4fb90.png">| `Motivações`: <br> Sustento <br> <br>  Experiência profissional  <br> <br>     |  `Frustrações`: <br>  Falta de capacitação  <br> <br> Poucas oportunidades na área <br><br>                    
|  `Hobbies`: |   `História`:  | `Personalidade`:  |
| <br> Adora assistir filmes <br><br> Gosta de passear ao Ar livre<br><br> Conhecer lugares novos <br> <br>     | Juliana é assistente administrativa,   que ama sua área <br> porém tem buscado bicos com objetivo de levantar capital para que possa ajuda-la a abrir seu próprio negócio  <br>            | Organizada <br><br> Extrovertida <br><br> Esfoçada<br>   |


|    `Nome`: Mario José Dantas  | `Profissão`: Desenvolvedor         |     `Idade`: 32 Anos    |
|--------------------|------------------------------------|----------------------------------------|
| <img width="250" alt="image" src="https://user-images.githubusercontent.com/55036173/188989388-76071b6b-c8b8-41e2-9f92-fa8ddb89d5c3.png">| `Motivações`: <br>  Aumentar rendimentos <br> <br> Criar seu próprio portifolio de trabalhos externos  <br> <br> Conhecimento na área |  `Frustrações`: <br>   Pouco tempo sobrando para trabalhar <br> <br> Cansaço de trabalhar com tecnologia o dia inteiro <br><br> Pressão da paternidade           
|  `Hobbies`: |   `História`:  | `Personalidade`:  |
| <br> Jogar Games  <br><br> Ouvir música livre<br><br> Conhecer tecnologias novas <br> <br>        | Mario José é um desenvolvedor focado<br>  Mário precisa fazer renda extra pois sua família está crescendo <br> mario gosta de webdesign e adora programação, está a procura de empregos informais na sua área de atuação.    <br>        | Bondoso <br><br> Introvertido <br><br> Metodico  <br>    |


|    `Nome`: Marcelo Belchior Melo  | `Profissão`: Aposentado         |     `Idade`: 70 Anos    |
|--------------------|------------------------------------|----------------------------------------|
| <img width="250" alt="image" src="https://user-images.githubusercontent.com/100283917/189008834-552789bd-d695-44eb-80f3-22b56fe5610e.jpg">| `Motivações`: <br>   Amor pelos bichos <br> <br> Distração  <br> <br> Trabalhar por hobby |  `Frustrações`: <br>   Não conseguir emprego no trabalho formal <br> <br> Idade avançada <br><br>            
|  `Hobbies`: |   `História`:  | `Personalidade`:  |
| <br> Ler  <br><br> Jogos de mesa<br><br> Conversar com as pessoas <br> <br>        | Marcelo é um professor aposentado e se sente desmotivado com a sua rotina,<br> sempre foi uma pessoa ativa que gostou de trabalhar  quer voltar a ser a como antes e usar aprender sobre novas áreas. Ele tem se interessado pela área de pet, e quer aprender a trabalhar cuidando de cachorros.   <br>        | Esforçado <br><br> Sério <br><br> Amante da Natureza  <br>    |



## Histórias de Usuários


Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Juliana Brancis    | Eficiencia e agilidade na marcação| Facilitar e agilizar a marcacão dos pacientes  |
|Juliana Brancis    | Visualizar as marcações | organizar melhor a agenda |
|Juliana Brancis    | Gerenciar os dados dos  pacientes | Facilidade na organização dos dados dos pacientes |
|Mario Dantas        | Realizar a marcação de consultas/exames | Marcar consultas com rapidez |
|Mario Dantas        | Realizar alteração de consultas/exames | Facilidade em gerenciar datas da marcação |
|Mario Dantas        | Visualizar a marcação de consultas e exames | Evitar esquecimento de datas |
|Usuário do sistema  | Registrar minhas tarefas           | Não esquecer de fazê-las               |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| A aplicação deverá possuir uma apresentação breve do aplicativo | BAIXA |
|RF-002| A aplicação deverá cadastrar dois tipos de usuários, o contratatante e o contratado | ALTA | 
|RF-003| A aplicação deverá permitir a edição do perfil desses usuários | ALTA | 
|RF-004| A aplicação terá um perfil de usuário para o contratado com suas qualificações e preferências | ALTA | 
|RF-005| A aplicação deverá permitir o contratante criar oportunidades de serviço | ALTA|
|RF-006| A aplicação deverá permitir o contratante selecionar a categoria do serviço em questão.| MEDIA |
|RF-007| A aplicação deverá exibir as especificações de cada serviço aos contratados como VALOR, LOCAL, PERÍODO e FUNÇÃO | ALTA |
|RF-009| A aplicação deve permitir que o contratado canditate-se as oportunidades de serviço | ALTA | 
|RF-010| A aplicação deverá possuir a funcionalidade de busca e filtragem das oportunidades de serviço | BAIXA |
|RF-011| A aplicação deverá sugerir serviços aos contratados baseando-se em seus dados pessoais | MEDIA | 
|RF-012| A aplicação deverá permitir que os usuários tenham as infomações de contato de ambos | ALTA | 
|RF-013| A aplicação deverá permitir que os usuários façam o login e loggout | ALTA |
|RF-014| A aplicação deverá possuir o contratante avaliar o contratado e vice-versa após o serviço | BAIXA |



### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O App deve operar em dispositivos móveis no ANDROID e IOS | ALTA | 
|RNF-002| O App possuirá responsividade para atender os dispositivos móveis | ALTA | 
|RNF-003| O App deve ter bom nível de contraste entre os elementos da tela em conformidade| MÉDIA |
|RNF-004| O App deverá seguir as normas da LGPD| ALTA |
|RNF-005| O App não deve consumir mais que 10GB de memória ao realizar seu download | BAIXA |

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do segundo semestre de 2022 |
|02| O projeto não possui orçamento |
|03| O projeto deve possuir apenas 6 integrantes |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)

## Diagrama de Casos de Uso

![Caso de uso Atualizado](https://user-images.githubusercontent.com/58198111/193125578-2a668cad-90a0-4ed4-b41c-897fa659f830.PNG)


As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)
