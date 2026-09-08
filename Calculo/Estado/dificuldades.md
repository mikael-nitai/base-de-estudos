# Dificuldades

## Cálculo C — pontos de atenção após 08/09/2026

- A ideia de derivar as coordenadas de uma curva parametrizada e obter o vetor tangente foi usada corretamente. Em uma formulação, apareceu a expressão imprecisa “derivada dos parâmetros”; manter a distinção entre o parâmetro `t` e as funções coordenadas `x(t)` e `y(t)`.
- A relação `dy/dx=(dy/dt)/(dx/dt)` foi aplicada corretamente no exemplo `r(t)=(t,t^2)` em `t=1`. Ainda é necessário verificar esse procedimento quando `dx/dt` não é constante e discutir os pontos em que `dx/dt=0`.
- Não há evidência suficiente sobre orientação, restrição do intervalo do parâmetro ou não unicidade de parametrizações. Classificação: conteúdo ainda não verificado, não dificuldade conceitual confirmada.

## Dificuldade ativa — domínio de funções

Em 10/08/2026, o conceito de domínio foi inicialmente lembrado com insegurança após longo intervalo sem uso. Depois de uma explicação conceitual, o estudante determinou corretamente o domínio de (f(x)=\\sqrt{2x-1}), obtendo (x\\geq1/2).

Classificação: esquecimento recuperável, não lacuna estrutural confirmada.

Próxima verificação: recuperar o conceito em funções polinomiais, racionais, com raízes e com logaritmos, sem consultar a explicação. Confirmar novamente após intervalo de pelo menos 48 horas.

## Dificuldade ativa — sinais na substituição algébrica

Em exercícios de taxa instantânea pela definição, o estudante compreendeu o procedimento de substituir (t) por (a+h), expandir, subtrair e dividir por (h). Entretanto, em duas tentativas apareceu a troca incorreta de:

\[
-(a+h)
\]

por:

\[
-a+h.
\]

A classificação é erro algébrico de sinal, não dificuldade conceitual sobre derivadas. A correção é lembrar que o sinal negativo multiplica todo o parêntese:

\[
-(a+h)=-a-h.
\]

Próxima verificação: resolver independentemente um quociente incremental que contenha termos lineares negativos antes de avançar para manipulações mais extensas.
