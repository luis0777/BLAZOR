@page "/imc"
<h1>Calcule seu IMC</h1>

<p>
    O Índice de Massa Corporal (IMC) é uma medida utilizada para avaliar se uma pessoa está com o peso ideal em relação à sua altura.
    Ele é amplamente utilizado como um indicador de saúde, pois pode ajudar a identificar se alguém está abaixo do peso, com peso normal,
    sobrepeso ou obesidade. Embora o IMC seja uma ferramenta útil, é importante lembrar que ele não considera outros fatores, como a composição corporal.
</p>

    <div style="text-align: center;margin-bottom: 20px;">
    <img src="https://superafarma.com.br/wp-content/uploads/2022/12/Supera-Farma-Tabela-IMC-Classificacao.png" alt="Tabela de IMC" style="width:400px; height:auto;" />
</div>

<div style="display: flex; flex-direction: column; max-width: 400px;">
    <label for="altura">Altura (em metros)</label>
    <input @bind="Altura" id="altura" type="number" step="0.01" min="0" style="margin-bottom: 15px;" />

    <label for="peso">Peso (em quilogramas)</label>
    <input @bind="Peso" id="peso" type="number" step="0.1" min="0" style="margin-bottom: 15px;" />

    <button @onclick="CalcularImc">Calcular IMC</button>

    <label>O IMC é <span>@ImcCalculado</span> @MensagemImc</label>
</div>

@code {
    private double Altura { get; set; }
    private double Peso { get; set; }
    private double ImcCalculado { get; set; }
    private string MensagemImc { get; set; }

    private void CalcularImc()
    {
        if (Altura > 0) 
        {
            ImcCalculado = Math.Round(Peso / Math.Pow(Altura, 2), 2);

            
            if (ImcCalculado < 16.9)
            {
                MensagemImc = "Muito abaixo do peso";
            }
            else if (ImcCalculado >= 17 && ImcCalculado <= 18.4)
            {
                MensagemImc = "Abaixo do peso";
            }
            else if (ImcCalculado >= 18.5 && ImcCalculado <= 24.9)
            {
                MensagemImc = "Peso normal";
            }
            else if (ImcCalculado >= 25 && ImcCalculado <= 29.9)
            {
                MensagemImc = "Acima do peso";
            }
            else if (ImcCalculado >= 30 && ImcCalculado <= 34.9)
            {
                MensagemImc = "Obesidade grau I";
            }
            else if (ImcCalculado >= 35 && ImcCalculado <= 39.9)
            {
                MensagemImc = "Obesidade grau II (severa)";
            }
            else
            {
                MensagemImc = "Obesidade grau III (mórbida)";
            }
        }
        else
        {
            MensagemImc = "Insira uma altura válida.";
        }
    }
}
