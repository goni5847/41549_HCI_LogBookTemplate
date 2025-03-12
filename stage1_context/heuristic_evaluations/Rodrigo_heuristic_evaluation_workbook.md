<!-- This Heuristic Evaluation Workbook replicates the one proposed by the 
Nielsen Norman Group available at: https://media.nngroup.com/media/articles/attachments/Heuristic_Evaluation_Workbook_-_Nielsen_Norman_Group.pdf
-->

**Evaluator**: Rodrigo Costa
**Date**: 26/02/2025
**Product**: AveiroBus

Severity Scale adopted: [[severity_scale_heuristic_evaluation]]
Summary of each usability heuristic: [here](https://media.nngroup.com/media/articles/attachments/Heuristic_Summary1-compressed.pdf)

# 1 Visibility of System Status ---------- 1
>	The design should always keep users informed about what is going on, through appropriate feedback within a reasonable amount of time. 
>	- Does the design clearly communicate its state?
>	- Is feedback presented quickly after user actions?

| **Issue**       | **Severity** | Recommendation                                           |
| --------------- | ------------ | ---------------------------------------------------------|
| Falta de feedback nas ações do user | 2 | Ao realizar uma ação, mostrar uma mensagem como "A carregar..." ou "Procurar horários. " até que a informação apareça, para garantir que o utilizador saiba que o sistema está a processar a sua solicitação |

# 2 Match Between System and The Real World ---------- 3
>	The design should speak the users' language. Use words, phrases, and concepts familiar to the user, rather than internal jargon. Follow real-world conventions, making information appear in a natural and logical order. 
>	- Will user be familiar with the terminology used in the design? 
>	- Do the design’s controls follow real-world conventions?

| **Issue**       | **Severity** | Recommendation                                           |
| --------------- | ------------ | ---------------------------------------------------------|
| O design do site não segue completamente as convenções comuns em sites de transportes públicos| 4 | Utilizar novos métodos de procura de hórarios, permitindo ao utilizador uma melhor experiencia |
| Páginas como as dos circuitas são longas e exigem um tempo de carregamento significativo | 3 | Otimizar e organizar as páginas para conter curta e boa informação para o utilizador |

**Comentário**
Ao procurar horários ou percursos, a estrutura da informação pode não ser imediata ou intuitiva para quem está habituado a outros sistemas de transporte. Algumas páginas têm uma apresentação excessivamente textual e pouco visual, o que pode ser desafiador para os utilizadores, especialmente os menos familiarizados com leitura de horários complexos.


# 3 User Control and Freedom ------------------- 3
>	Users often perform actions by mistake. They need a clearly marked "emergency exit" to leave the unwanted action without having to go through an extended process. 
>	- Does the design allow users to go back a step in the process? 
>	- Are exit links easily discoverable? 
>	- Can users easily cancel an action? 
>	- Is Undo and Redo supported?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
|Falta de Opções Visíveis de "Voltar" ou "Cancelar" nas Páginas  | 2            |  Adicionar botões que permitam ao utilizador voltar á página anterior, ou então cancelar algo              |
| Requisação de passe não pode ser cancelada  | 3           |  Adicionar um separador que permita ao user obter informações sobre o seu pedido de passe e que o permita cancelar/editar              |



# 4 Consistency and Standards --------------------- 2
>	Users should not have to wonder whether different words, situations, or actions mean the same thing. Follow platform and industry conventions. 
>	- Does the design follow industry conventions? 
>	- Are visual treatments used consistently throughout the design?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Inconsistência no Estilo Visual entre Páginas | 2            |Manter um estilo consistente em todo o site |

**Comentário**
O estilo visual da página Circuitos urbanos, é completamente diferente do estilo visual da página Requisição de passes.

# 5 Error Prevention --------------------- 1
>	Good error messages are important, but the best designs carefully prevent problems from occurring in the first place. Either eliminate error-prone conditions, or check for them and present users with a confirmation option before they commit to the action. 
>	- Does the design prevent slips by using helpful constraints? 
>	- Does the design warn users before they perform risky actions?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Falta de Confirmação Antes de Ações Irreversíveis | 3            |  Implementar uma etapa de confirmação em processos irreversíveis. Mostrar um separador com um resumo da ação que o utilizador está prestes a realizar, permitindo-lhe confirmar ou cancelar a operação antes de avançar |




# 6 Recognition Rather than Recall --------------------- 4
>	Minimize the user's memory load by making elements, actions, and options visible. The user should not have to remember information from one part of the interface to another. Information required to use the design (e.g. field labels or menu items) should be visible or easily retrievable when needed. 
>	- Does the design keep important information visible, so that users do not have to memorize it? 
>	- Does the design offer help in-context?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| O site não apresenta algumas informações importantes, como horários ou percursos, de maneira constante e acessível | 3            | Garantir que informações essenciais, como horários e percursos, sejam facilmente acessíveis de acordo com as preferências do user |

**Comentário**
O site não apresentar algumas informações importantes, exige  ao utilizador que memorize ou procure ativamente por essas informações em várias páginas.

# 7 Flexibility and Efficiency of Use ---------------------- 3
>	Shortcuts — hidden from novice users — may speed up the interaction for the expert user such that the design can cater to both inexperienced and experienced users. Allow users to tailor frequent actions. 
>	- Does the design provide accelerators like keyboard shortcuts and touch gestures? 
>	- Is content and funtionality personalized or customized for individual users?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
|O site não permite que os utilizadores personalizem a sua experiência | 2 | Implementar a um sistema de login e personalização, permitindo que os utilizadores guardem percursos/horários |
| O site não permite ao user escolher opções para a sua pesquisa | 3 | Adicionar uma função de pesquisa avançada, que permita aos utilizadores filtrar percursos e horários de acordo com critérios específicos |

# 8 Aesthetic and Minimalist Design ------------------------- 3
>	Interfaces should not contain information that is irrelevant or rarely needed. Every extra unit of information in an interface competes with the relevant units of information and diminishes their relative visibility. 
>	- Is the visual design and content focused on the essentials? 
>	- Have all distracting, unnescessary elements been removed?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
|A página inicial do site apresenta muitos elementos e informações ao mesmo tempo | 3 | Simplificar a página inicial |
| Alguns textos têm tamanho de fonte pequeno   | 3 | Em vez de usar imagens com percursos, utilizar tabelas com tamanho de letra visivel |


# 9 Help Users Recognize, Diagnose, and Recover from Errors ---------- 3 (avisa erro um a um)
>	Error messages should be expressed in plain language (no error codes), precisely indicate the problem, and constructively suggest a solution. 
>	- Does the design use traditional error message visuals, like bold, red text? 
>	- Does the design offer a solution that solves the error immediately?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| O site frequentemente não oferece orientações ou soluções claras para os erros que ocorrem | 2            | O site deverá tentar ajudar o user sugerindo uma correção               |

**Comentário**
No caso de pesquisa de linhas, caso pesquise "hospitel" na vez de "hospital", aparece erro por não haver nenhuma paragem com esse nome. 
O site deverá tentar ajudar o user sugerindo uma correção do género "Queria dizer Hospital?".


# 10 Help and Documentation --------------- 4
>	It’s best if the system doesn’t need any additional explanation. However, it may be necessary to provide documentation to help users understand how to complete their tasks. 
>	- Is help documentation easy to search? 
>	- Is help provided in context right at the moment when the user requires it?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| O site não apresenta um separador onde os utilizadores possam encontrar respostas para dúvidas frequentes | 3 |  Criar um separador de "Ajuda" ou "Perguntas Frequentes (FAQ)" acessível no menu principal |




