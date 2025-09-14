# Calculadora de Financiamento Imobiliário

Uma planilha em Excel para calcular parcelas de financiamento imobiliário, juros, amortização, prazo, entre outros. Ideal para quem quer simular cenários de compra de imóvel ou refinanciamento.

---

## 📋 O que ela faz

- Permite inserir valores como montante do empréstimo, taxa anual de juros, prazo em anos.  
- Calcula o valor da parcela mensal usando função `PMT`.  
- Mostra quanto de cada parcela vai para **juros** e quanto para **principal** (amortização).  
- Gera uma tabela de amortização (ex: para cada período: saldo devedor, principal pago, juros pago).  
- Possibilita simular **pagamentos extra** para ver como eles afetam o prazo ou o total de juros.  

---

## 🛠 Como usar

1. Abra o arquivo Excel (`.xlsx`).  
2. Preencha os dados de entrada:
   - Valor do empréstimo  
   - Taxa de juros anual (%)  
   - Prazo (anos)  
3. Veja os resultados automáticos de parcela mensal, juros, amortização.  
4. Se quiser, experimente incluir um pagamento extra mensal ou anual para ver o impacto.  

---

## 🔧 Funções principais usadas

| Função | Utilização |
|---|---|
| `PMT(rate, nper, pv, [fv], [type])` | Para calcular o valor da prestação mensal. |
| `IPMT(rate, per, nper, pv, [fv], [type])` | Para calcular a parte de juros em uma parcela específica. |
| `PPMT(rate, per, nper, pv, [fv], [type])` | Para calcular a parte de amortização (principal) em uma parcela específica. |

---

## 📸 Imagem / Pré‑visualização

![Pré‑visualização da Calculadora](https://raw.githubusercontent.com/Lydson/Planilhas-Excel/main/Calculadora_Financiamento_Imobiliario/Calculadora_financ_imob.png)

---

## 🚀 Aplicações e por que isso importa

- Permite simular o quanto o financiamento vai custar no longo prazo;  
- Ajuda a tomar decisões financeiras mais informadas (ex: pagar mais cedo, negociar taxa de juros);  
- Útil para quem trabalha com finanças pessoais, corretores, investidores ou estudantes.  

---

## ℹ️ Observações

- A planilha usa suposições simplificadas: pagamentos mensais iguais, juros compostos mensais. Pode não considerar taxas extras (seguros, impostos etc.).  
- Certifique‑se de que o Excel está configurado para o formato de data/número correto no seu sistema para evitar erros de cálculo.  
