README - App Calcula Salário
📱 Sobre o Projeto

O App Calcula Salário é uma aplicação Android simples desenvolvida em Java, responsável por calcular o reajuste salarial de um funcionário.

O usuário informa o salário atual e escolhe uma das opções de aumento disponíveis:

40%
45%
50%

Após clicar no botão Calcular, o sistema exibe o novo salário reajustado através de uma caixa de diálogo.

🛠️ Componentes Utilizados

A aplicação utiliza os seguintes componentes visuais:

TextView
EditText
RadioGroup
RadioButton
Button
AlertDialog
📂 Estrutura da Aplicação
Layout (activity_salario.xml)

O layout contém:

Campo para digitar o salário
Grupo de opções de aumento (RadioGroup)
Três RadioButtons
Botão para calcular o novo salário
💻 Lógica da Aplicação

No arquivo SalarioActivity.java:

O usuário digita o salário.
Escolhe o percentual de aumento.
O sistema calcula o novo salário.
O resultado é mostrado em uma janela (AlertDialog).
📌 Fórmulas Utilizadas
40% → salario + (salario * 0.4)
45% → salario + (salario * 0.45)
50% → salario + (salario * 0.5)
▶️ Exemplo
Entrada:
Salário: 2000
Aumento: 45%
Resultado:
Novo salário: 2900
🚀 Tecnologias Utilizadas
Java
Android Studio
XML
👨‍💻 Autor

Projeto desenvolvido para fins de aprendizado em desenvolvimento Android.
