# Python Insights - Analisando dados com Python

### Case - Cancelamento de Clientes

Uma empresa com mais de 800 mil clientes para um projeto de Dados recentemente percebeu que da sua base total de clientes, a maioria são clientes inativos, ou seja, que já cancelaram o serviço.

Precisando melhorar seus resultados ela quer conseguir entender os principais motivos desses cancelamentos e quais as ações mais eficientes para reduzir esse número.
<hr>

Utilizando Python foi possível identificar 3 problemas que causam a perda de clientes 👇

<li> Forma de contrato mensal 📆 </li>

Agrupando por tipo de contrato e definindo a média das colunas resultamos em 100% a média de cancelamento do tipo mensal em relação aos outros
![image](https://github.com/nayara-lucia/python-insights/assets/126920974/78ee03a7-7a6d-48f9-b038-991dfd2bd2f2)

Agora utilizando a biblioteca <b>Plotly Express</b> para melhor visualização

<li> Necessidade de mais de 5 ligações no call center 📞</li>

Foi possível identificar que clientes que ligam mais de 5 vezes para o call center cancelam
![image](https://github.com/nayara-lucia/python-insights/assets/126920974/36ab23da-a190-4bd4-aa0e-94ec86f6b289)

<li> Mais de 20 dias de atraso no pagamento 💵</li>

Foi possível identificar que quando um cliente atrasa mais de 20 dias ele cancela
![image](https://github.com/nayara-lucia/python-insights/assets/126920974/f6fa6625-bc67-4c3f-a998-5273846643d3)
<hr>
