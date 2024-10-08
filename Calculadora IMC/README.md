# Resumo sobre o Cálculo de IMC 📏🏋️‍♂️

## Página IMC.razor 🖥️
@page "/imc": Define a rota da página para cálculo do IMC.

Título e Descrição: Apresenta o título e uma breve explicação sobre o que é o IMC e sua importância como indicador de saúde.

Imagem da Tabela de IMC: Exibe uma tabela de classificação do IMC centralizada na tela.

## Formulário de Entrada 📝
Campos de Altura e Peso: Contém dois campos de entrada (input) para o usuário informar sua altura (em metros) e peso (em quilogramas). Ambos os campos utilizam @bind para vincular os valores às propriedades Altura e Peso.

Botão Calcular: Um botão que, ao ser clicado, chama o método CalcularImc para realizar o cálculo do IMC.

Exibição do Resultado: Um label que mostra o IMC calculado e uma mensagem correspondente à classificação do IMC.

## Lógica de Cálculo @code { } 🔢
Propriedades: Declara as propriedades Altura, Peso, ImcCalculado e MensagemImc para armazenar os dados do usuário e o resultado do cálculo.

Método CalcularImc():

Cálculo do IMC: Se a altura for válida (maior que 0), calcula o IMC usando a fórmula 

IMC = Peso / Altura² e arredonda o resultado para duas casas decimais.

Classificação do IMC: Um conjunto de condições (if-else) que avalia o IMC calculado e atribui uma mensagem (MensagemImc) que indica a categoria do IMC (muito abaixo do peso, peso normal, obesidade, etc.).

Validação: Se a altura for inválida, exibe uma mensagem solicitando uma entrada válida.
