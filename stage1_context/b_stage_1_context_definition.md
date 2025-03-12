[Back to main Logbook Page](../hci_logbook.md)

---
# B. Stage 1 - Context Definition


# B.1. Competitor Identification
>	The competitor analysis will entail an identification of all competitors, with brief descriptions and a collection of the look and feel of their solutions, e.g., with screenshots, etc. It will also include a detailed analysis of the competitor deemed the best or more representative. It ends with a summary of the main findings including an HCI SWOT analysis



## B.1a. Competitors


| **Competitor**    | **Description**                             | Information repository              |
| ----------------- | ------------------------------------------- | ----------------------------------- |
| BusWay | App de transporte da BusWay        | [BusWay Analysis](../stage1_context/competitors/Competitor%20Analysis%20BusWay.md) |
 AveiroBus  | Website de transportes públicos de Aveiro | [AveiroBus Analysis](../stage1_context/competitors/Competitor%20Analysis%20AveiroBus.md) |




## B.1b. Detailed Competitor Analysis
>	AveiroBus


### - Heuristic Evaluation

#### Method
Foi avaliado o website por 3 especialistas, utilizando as 10 heuristicas de Jakob Nielsen, numa escala de 0 a 4. 


#### Individual Evaluations
<!-- For the individual heuristic evaluations by each member of the group, you can use the templates below, grouping problems by heuristic OR each evaluator can have a table listing all the detected problems with the number of the violated heuristics on the second column. Whichever your choice, you should have a list of problems, the severity, and a recommendation to mitigate it -->



- [Rodrigo Heuristic Evaluation](heuristic_evaluations/Rodrigo_heuristic_evaluation_workbook.md)

- [Vasco Heuristic Evaluation](heuristic_evaluations/Vasco_heuristic_evaluation_workbook.md)

- [Gonçalo Heuristic Evaluation](heuristic_evaluations/Goncalo_heuristic_evaluation_workbook.md)


#### Consensus


| **Issue**       | Rodrigo | Vasco | Gonçalo | Recommendations                             |
| --------------- | ------------ | -------- | -------- | ------------------------------------------- |
| Avisos mal identificados 					| 1	| 1 | 1 | Os avisos poderiam ser mais impactantes |
| Não existir rotas preferidas   			| 2 | 2 | 2 | Ser possivel selecionar rotas preferidas |
| Não ser possível procurar horários		| 4 | 3 | 3 | SearchBar/Menu com origem e destino para destino |
|Design de página complexo					| 3 | 3 | 1 | Simplificar estrutura do website|
|Falta de Documentação de ajuda				| 3 | 2 | 3 |Criar uma FAQ ou separador de Ajuda|
|Falta de botão Undo 						| 2 | 1 | 1 | Criar um botão claro para Undo |
| Mapa ilegivel 		            		| 3 | 3 | 3 | Refazer |
| Fraca compartimentalização da informação  | 2 | 2 | 1 | Divisão mais explícita da informação (elementos de design mais explícitos) |
| Barra de pesquisa pouco visível   		| 2 | 2 | 3 | Tornar a barra de pesquisa mais visível (elementos de design) |

---
### - Cognitive Walkthrough

#### Method
[Briefly described  the method you used for the Cognitive Walkthrough analysis. ]

#### Task Selection and Task Analysis

[Which tasks did you select and why. What are the subtasks entailed for each ]


| Task                        | Subtasks                               |
| --------------------------- | -------------------------------------- |
| **1. Buyng a grammar book** | Search for available grammar books     |
|                             | Identify a specific book from the list |
|                             | Add the selected book to the cart      |
|                             | Proceeed to checkout                   |


| Task                          | Subtasks                                |
| ----------------------------- | --------------------------------------- |
| **1. Booking a train ticket** | Select departure and destination cities |
|                               | Choose travel date and time             |
|                               | Pick a seat (if applicable)             |
|                               | Confirm booking and make payment        |


#### Results

Task: [This is the task]

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | [Step 1 description]   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 1]              |     |
| 2      | [Step 2 description]   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 2]              |     |
| 3      | [Step 3 description]   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 3]              |     |
| ...    | [Further steps]        | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestions]               |     |

## B.1c. Overall Analysis

[Here, you should summarize the main findings for the competitor panorama, listing key points that are valuable to inform the design of your solution, and also make an HCI SWOT analysis for the main competitor, taking into consideration what you learned from the heuristic evaluatio, cognitive walkthrough, online reviews, user feedback, etc.]
SWOT

---

# B.2. Users
>	For the users, there are two goals: 1) understand the current status of users in the domain you are addressing. How do they manage, what are the main tasks they do, if they use some tool for the purpose, what are current challenges, what might be improved, what might be new features, ...


## B.2a. Method

[What approach was followed to talk with users; what kind of users were considered. What was the goal of the interviews? What were the questions considered?]
Tentamos abordar os utilizadores que necessitam de algum tipo de deslocação diária. As entrevistas foram feitas de forma física como também online.

## B.2b. Results

>	This section tracks all informal user interviews, summarizing key insights and linking to detailed notes for each session. 

### Interview List 
| Date       | Participant / Role | Key Insights                                                    | Link to Notes                |
| ---------- | ------------------ | --------------------------------------------------------------- | ---------------------------- |
| 26-02-2025 | Maria/estudante    | Utiliza horários em papel     | [📄 Notes](interviews/interview-Maria_Freitas.md)|
| 26-02-2025 | Leonor/estudante   | Horários dificéis de pesquisar| [📄 Notes](interviews/interview-Leonor) |
| 25-02-2025 | Maria/estudante    |  							  | [📄 Notes](interviews/interview-Maria) |
| 25-02-2025 | Sandra/estudante   | 							  |[📄 Notes](interviews/interview-Sandra)|
| 26-02-2025 | Sofia/estudante    | 							  |[📄 Notes](interviews/interview-Sofia)|


### Common Themes & Patterns 

- **Recurring Problems:** 
	-  Procura horários confusa e difícil
	- Falta de conhecimento atraso
- **Frequently Used Tools:** 
	- AveiroBus
	- Andante
	- Uber
- **Desired Features / Solutions:** 
	- Saber tempo de atraso
	- Melhorar 
- --- 



---
[Back to main Logbook Page](../hci_logbook.md)

---
