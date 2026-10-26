\# 🧠 Lógica de Decisão da Triagem de Adoção



Antes de programar o sistema, o fluxo de trabalho do algoritmo para aprovação de adoção de animais foi mapeado usando lógica condicional básica (SE / SENÃO):



1\. O adotante envia o formulário de interesse para um animal específico.

2\. \*\*SE\*\* `idade\_do\_adotante < 18` ➡️ \*\*Ação:\*\* Bloquear adoção. \*\*Mensagem:\*\* "Adoção permitida apenas para maiores de idade."

3\. \*\*SENÃO, SE\*\* `tipo\_de\_residencia\_do\_adotante == "Apartamento"` \*\*E\*\* `porte\_do\_animal == "Grande"` ➡️ \*\*Ação:\*\* Definir status como "Pendente de Análise da ONG".

4\. \*\*SENÃO\*\* ➡️ \*\*Ação:\*\* Definir status como "Aprovado para Entrevista".



