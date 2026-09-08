# Exercícios resolvidos

## 2026-09-08 — Cálculo C, C1: curvas parametrizadas

Fonte: `Tarefa 1_260908_183650.pdf`, arquivo externo apresentado pelo estudante; material, capítulo/seção e numeração original não informados, portanto não há `material_id` catalogado.

1. **A — Derivada de uma curva parametrizada.** Para `r(t)=(x(t),y(t))`, foi identificada a derivada componente a componente `r'(t)=(x'(t),y'(t))` como a variação instantânea das coordenadas.
2. **B — Interpretação do vetor tangente.** Foi explicado que `r'(t)` indica a direção e a variação instantânea da curva quando o parâmetro varia. A explicação foi conceitualmente adequada.
3. **C — Exemplo com `r(t)=(t,t^2)`.** Foi obtido `r'(t)=(1,2t)`, logo `r'(1)=(1,2)`, no ponto `(1,1)`.
4. **D — Reta tangente em `t=1`.** Usando `dy/dx=(dy/dt)/(dx/dt)`, foi encontrada a inclinação `m=2` e, pela forma ponto-inclinação, `y-1=2(x-1)`, isto é, `y=2x-1`.

**Classificação:** resolvidos corretamente conforme as respostas apresentadas. Recomenda-se revisão independente de orientação, intervalo do parâmetro, eliminação de parâmetro e casos em que `dx/dt=0` antes de considerar C1 consolidada.

## 2026-08-10 — Diagnóstico inicial dos fundamentos

1. \\(\\frac{2}{3}-\\frac{5}{4}=-\\frac{7}{12}\\). Resolvido corretamente.
2. \\(x^2-5x+6=0\\). Raízes \\(2\\) e \\(3\\) identificadas corretamente por soma e produto. As relações de Viète foram recordadas.
3. Para \\(f(x)=\\sqrt{2x-1}\\): \\(f(3)=\\sqrt5\\) e \\(D_f=[1/2,\\infty)\\). Resolvido corretamente após recuperação do conceito de domínio.
4. Para \\(g(x)=2x+1\\): \\(g^{-1}(x)=\\frac{x-1}{2}\\). Resolvido corretamente.
5. \\(\\sin(5\\pi/6)=1/2\\). Resolvido corretamente pela conversão para \\(150^\\circ\\) e uso do ângulo de referência.
6. \\(2^x=8\\Rightarrow x=3\\). Resolvido corretamente pela reescrita \\(8=2^3\\).

## 2026-08-23 — Cálculo A, A1 e introdução a A2

### Taxa média e taxa instantânea

Para (s(t)=3t^2+1), entre (t=1) e (t=1{,}5):

\[
v_{m}=\\frac{7{,}75-4}{1{,}5-1}=7{,}5.
\]

No ponto (t=1):

\[
\\frac{s(1+h)-s(1)}{h}=6+3h,
\qquad
\\lim_{h\\to0}(6+3h)=6.
\]

O resultado foi interpretado como taxa instantânea, com unidade dependente das unidades de (s) e (t).

### Derivada geral

Para (f(t)=2t^2-t), a definição foi aplicada com acompanhamento:

\[
f'(t)=\\lim_{h\\to0}\\frac{f(t+h)-f(t)}{h}=4t-1.
\]

Consequentemente:

\[
f'(3)=11.
\]

O cálculo no ponto (t=3) exigiu correção de um erro de sinal em (-(3+h)), portanto foi registrado como resolvido com ajuda, não como evidência de domínio independente.

### Limites

Foi apresentada a ideia de limite como comportamento nas proximidades de um ponto. Também foi mostrado o exemplo:

\[
\\lim_{x\\to2}\\frac{x^2-4}{x-2}=4,
\]

resolvido por fatoração após a substituição direta produzir (0/0). O exercício equivalente em (x\\to3) ficou pendente.
