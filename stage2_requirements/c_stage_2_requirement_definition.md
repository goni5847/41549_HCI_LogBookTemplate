[Back to main Logbook Page](../hci_logbook.md)

---
# C. Requirement Definition
>	Based on all the gathered context, including an understanding of current practices, competitors, and user feedback and expectations: 
>	- summarize the user characteristics, context, and motivations using Personas
>	- explain your vision for a novel solution that will target user motivations using Scenarios
>	- identify requirements

# Personas

## Persona: [Persona Name] 
### Summary 
| Attribute        | Details                                       |
| ---------------- | --------------------------------------------- |
| **Photo**        | ![Persona Name\|100](personas/persona1.jpeg)  |
| **Name**         | [Persona Name]                                |
| **Age**          | [Persona Age]                                 |
| **Occupation**   | [Job Title or Role]                           |
| **Location**     | [City, Country]                               |
| **Goals**        | [Brief summary of their main goals]           |
| **Pain Points**  | [Key frustrations or challenges]              |
| **Motivation**   | [One-line motivation or quote]                |
| **Full Profile** | [📄 Read More](personas/persona1_template.md) |

---
## Persona: [Persona Name] 
### Summary 
| Attribute        | Details                                       |
| ---------------- | --------------------------------------------- |
| **Photo**        | ![Persona Name](path/to/photo.jpg)            |
| **Name**         | [Persona Name]                                |
| **Age**          | [Persona Age]                                 |
| **Occupation**   | [Job Title or Role]                           |
| **Location**     | [City, Country]                               |
| **Goals**        | [Brief summary of their main goals]           |
| **Pain Points**  | [Key frustrations or challenges]              |
| **Motivation**   | [One-line motivation or quote]                |
| **Full Profile** | [📄 Read More](personas/persona2_template.md) |

---





# Scenarios


## Scenario 1: O Emanuel precisa de carregar o passe

[O Emanuel vive em Esgueira, longe de locais de carregamento de passe de autocarro e precisa, todos os meses, de usar transporte público para frequentar aulas na Universidade de Aveiro. Por isso, prefere **usar o site da empresa** fornecedora de transporte para **carregar o seu passe mensal**. ]

[**Ao aceder ao website**, são apresentados os serviços que a empresa fornece. Viagens de longo curso, viagens de ferry e circuito urbano. O Emanuel **escolhe o circuito urbano**. No **mapa fornecido**, o Emanuel **procura a origem da sua viagem e destino**. Ao obter as rotas, **determina a(s) linha(s)** para o seu passe. ]

[Para carregar o passe, **o Emanuel faz Login com um nome de utilizador e uma palavra-passe**. O cartão-passe do autocarro está associado à sua conta. O Emanuel **escolhe carregar esse passe**. **Escolhe a(s) linha(s)**, e efetua o **pagamento online** (MBWay?). O site confirma a realização do pagamento.]

## Scenario 2: O Emanuel precisa de comprar viagens individuais

[O Emanuel precisa de visitar uma área em Aveiro longe das rotas associadas ao seu passe mensal. Para isso determinou que obter viagens individuais que compensa mais.]

[Ao **aceder ao website**, são apresentados os serviços que a empresa fornece. Viagens de longo curso, viagens de ferry e circuito urbano. O Emanuel **escolhe o circuito urbano**. No mapa fornecido, o Emanuel **procura os locais** que correspondem à origem da sua viagem e destino. Ao obter o nome das paragens mais próximas, **pesquisa possíveis rotas** e **determina a(s) linha(s)** para a sua viagem. ]

[Para comprar viagens individuais não é necessário fazer login, pois o a plataforma regista o pagamento e emite um código QR identificador da viagem.]

## Scenario 3: O Emanuel quer comprar viagens de ferry

[O Emanuel quer visitar amigos em S.Jacinto e para isso precisa de comprar viagens de ferry. Ao **aceder ao website**, ele **escolhe a opção de transporte fluvial** que o reencaminha para a empresa que gere os transportes fluviais entre Aveiro e S.Jacinto.]

[A partir daqui, o Emanuel **utilizará a plataforma da empresa que explora o ferry**.]

## Scenario 4: O Emanuel quer verificar o atraso do autocarro

[O Emanuel está na paragem de autocarros mas o autocarro está um pouco atrasado. Ele quer verificar se o atraso se vai prolongar para decidir se continua a esperar ou se escolhe uma alternativa como o Uber. Para isso, o Emanuel **vai ao site** da empresa e **pesquisa pelas paragens origem destino** que representa a sua viagem.]

[Ao pesquisar a lista de autocarros do dia que efetuam essa rota, ele **seleciona o autocarro da hora atual**. Ele é redirecionado para um mapa em tempo real que indica a posição atual do autocarro. Com esta informação, **se o atraso se prolongar, ele irá escolher uma alternativa de última hora.**]

---


# Requirements


## C.1. Functional requirements
- tem de ter forma de selecionar circuito urbano
- tem de ter forma de selecionar transporte fluvial
- tem de ter uma barra de pesquisa de viagens pela origem e/ou destino
- tem de ter forma de selecionar viagens da pesquisa
- tem de ter forma de criar conta
- tem de ter forma de fazer login numa conta
- tem de ter forma de efetuar pagamento online
- tem de apresentar um mapa relativo à viagem

## C.2. Non-functional requirements
- a pesquisa de viagens tem de informar que está a dar load
- a pesquisa de viagens tem de apresentar uma lista por ordem cronológica da viagem mais próxima (temporalmente) à mais distante
- a pesquisa de viagens tem de indicar a linha em que a viagem se realiza
- ao selecionar transporte fluvial o site tem de avisar que vai redirecionar o utilizador para um novo separador direcionado para o site da empresa do ferry.
- o sítio para criar/fazer login duma conta deve existir conforme normas de outros sites(em cima à direita) e estar bem visível
- ao efetuar pagamento online o site tem de indicar claramente a(s) plataforma(s) que usa
- o site tem de identificar claramente se o pagamento foi efetuado com sucesso ou se falhou
- o mapa relativo à viagem tem de ser responsivo e interativo
- o mapa deve apresentar a posição do autocarro em tempo real

---
[Back to main Logbook Page](hci_logbook.md)