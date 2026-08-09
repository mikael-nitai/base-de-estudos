# Cálculo A

## Missão da disciplina

Cálculo A constrói a linguagem de funções, limites e derivadas e ensina a usar variação local para compreender comportamento global, modelar fenômenos e resolver problemas. O curso deve formar compreensão conceitual, fluência técnica e capacidade de escolher estratégias; não deve se reduzir a uma coleção de regras de derivação.

**Base principal:** Stewart, *Cálculo*, 7ª edição, volume 1, capítulos 1 a 4, com apoio dos testes de verificação e apêndices.

**Plano compartilhado:** aplicar diagnóstico, critérios de domínio, política de pistas e revisão espaçada descritos em `fundamentos.md`.

## Resultado esperado

Ao concluir Cálculo A, o estudante deve ser capaz de:

- representar e analisar funções por fórmulas, gráficos, tabelas e descrições;
- compreender limite como comportamento e calcular limites por métodos adequados;
- distinguir continuidade de diferenciabilidade;
- interpretar derivada como taxa de variação, inclinação e aproximação linear;
- derivar funções elementares e compostas com justificativa;
- usar derivadas para analisar gráficos, modelar taxas, otimizar e aproximar;
- comunicar domínio, hipóteses, unidades e significado do resultado;
- verificar respostas sem depender exclusivamente de gabarito ou software.

## Gate de entrada

Aplicar o diagnóstico de `fundamentos.md`. Antes da unidade A2, exigir nível operacional em:

- frações, fatoração e simplificação algébrica;
- equações e desigualdades elementares;
- domínio, gráficos, composição e inversas;
- exponenciais, logaritmos e trigonometria básica;
- reta, inclinação e interpretação de taxa média.

Lacunas pontuais podem ser tratadas em paralelo. Lacunas graves em funções, fatoração ou notação devem acionar os módulos F1, F2, F4 ou F5 antes de limites algébricos e regra da cadeia.

## Arquitetura do curso

| Unidade | Conteúdo central | Referência Stewart |
|---|---|---|
| A0 | Diagnóstico, linguagem de funções e modelos | Testes; 1.1 a 1.6 |
| A1 | Tangente, velocidade e taxa média | 2.1 |
| A2 | Limite: conceito, estimativa e leis | 2.2 a 2.4 |
| A3 | Continuidade e comportamento no infinito | 2.5 e 2.6 |
| A4 | Derivada pela definição e como função | 2.7 e 2.8 |
| A5 | Regras básicas, produto, quociente e cadeia | 3.1 a 3.4 |
| A6 | Derivação implícita, logarítmica e inversas | 3.5 e 3.6 |
| A7 | Taxas, modelos, taxas relacionadas e linearização | 3.7 a 3.10 |
| A8 | Extremos, Teorema do Valor Médio e forma de gráficos | 4.1 a 4.5 |
| A9 | Otimização e métodos numéricos | 4.6 a 4.8 |
| A10 | Primitivas e movimento retilíneo | 4.9 |
| A11 | Síntese cumulativa e transição para integrais | Revisões dos caps. 1 a 4 |

## Unidades detalhadas

### A0 - Funções, modelos e múltiplas representações

**Pergunta orientadora:** como uma mesma dependência aparece em uma situação, tabela, gráfico e fórmula?

**Objetivos:**

- identificar variável independente, dependente, domínio, imagem, zeros e sinal;
- analisar crescimento, simetria e comportamento qualitativo;
- transformar gráficos e construir novas funções por operações e composição;
- compreender inversas como reversão de um processo;
- reconhecer funções lineares, polinomiais, racionais, potências, trigonométricas, exponenciais e logarítmicas;
- escolher um modelo simples e interpretar seus parâmetros.

**Erros a vigiar:** tratar `f(x)` como multiplicação; ignorar domínio; confundir inversa com recíproca; transformar gráfico por memorização sem testar pontos; ajustar modelo sem interpretar unidades.

**Evidência de saída:** converter um problema entre três representações, justificar o domínio e comparar dois modelos possíveis.

### A1 - Da taxa média à taxa instantânea

**Pergunta orientadora:** como definir uma taxa em um único instante quando toda razão precisa de um intervalo?

**Objetivos:**

- calcular e interpretar taxa média;
- relacionar secantes, tangente e velocidade;
- construir o quociente incremental;
- antecipar a ideia de limite sem começar por manipulação simbólica.

**Evidência de saída:** explicar por que a inclinação da tangente é obtida por um processo de aproximação e estimá-la com dados ou gráfico.

### A2 - Limites

**Pergunta orientadora:** que informação sobre uma função é necessária perto de um ponto, mesmo quando o valor no ponto é diferente ou inexistente?

**Objetivos:**

- estimar limites numericamente e graficamente;
- distinguir limite bilateral, laterais e limites infinitos;
- usar leis de limites com hipóteses explícitas;
- resolver indeterminações por fatoração, racionalização e reorganização;
- compreender a definição precisa como controle de erro, mesmo que a prova formal não seja o foco da avaliação;
- produzir ou analisar argumentos simples com `epsilon` e `delta` quando o curso exigir.

**Erros a vigiar:** substituir mecanicamente; concluir que o limite não existe apenas porque a função não está definida; cancelar fatores sem registrar restrições; confundir valor grande com infinito; inferir limite de desenho impreciso.

**Evidência de saída:** resolver um conjunto misto sem indicação de método e explicar, em cada caso, por que substituição direta funciona ou falha.

### A3 - Continuidade e limites no infinito

**Objetivos:**

- aplicar a definição de continuidade em um ponto e em intervalos;
- classificar descontinuidades;
- usar o Teorema do Valor Intermediário com hipóteses verificadas;
- analisar limites no infinito, assíntotas horizontais e crescimento relativo;
- separar comportamento local de comportamento assintótico.

**Evidência de saída:** analisar uma função por partes, ajustar parâmetros para continuidade e justificar existência de raiz em intervalo.

### A4 - Derivada pela definição

**Pergunta orientadora:** qual informação a derivada fornece que a função original não mostra diretamente?

**Objetivos:**

- calcular derivadas simples pela definição;
- interpretar unidade e sinal da derivada;
- distinguir número derivada, função derivada e derivadas de ordem superior;
- reconhecer pontos de não diferenciabilidade;
- explicar por que diferenciabilidade implica continuidade, mas não o contrário.

**Evidência de saída:** obter uma derivada pela definição, interpretá-la em contexto e analisar a diferenciabilidade de um gráfico com canto, cúspide ou tangente vertical.

### A5 - Regras de derivação

**Objetivos:**

- derivar polinômios, exponenciais e funções trigonométricas;
- aplicar linearidade, produto e quociente;
- decompor funções compostas e aplicar a regra da cadeia em múltiplas camadas;
- comparar uma derivação simbólica com previsão qualitativa do sinal ou crescimento.

**Erros a vigiar:** derivar produto termo a termo; esquecer quadrado no denominador do quociente; perder fatores internos; aplicar regra da potência onde a base e o expoente variam; simplificar de modo que o domínio seja alterado sem observação.

**Evidência de saída:** derivar uma lista intercalada em que o estudante precisa identificar as regras, explicar a estrutura de duas funções compostas e validar numericamente um resultado.

### A6 - Métodos avançados de derivação

**Objetivos:**

- usar derivação implícita e encontrar tangentes;
- derivar logaritmos e funções trigonométricas inversas;
- aplicar derivação logarítmica a produtos, quocientes e potências variáveis;
- explicitar dependências antes de diferenciar.

**Evidência de saída:** resolver um problema implícito, um de derivação logarítmica e um de escolha de método, sem rótulo.

### A7 - Taxas e aproximação local

**Objetivos:**

- interpretar derivadas em física, ciências naturais, economia e outros contextos;
- modelar crescimento e decaimento exponenciais;
- resolver taxas relacionadas com diagrama, equação de vínculo e unidades;
- construir linearização e diferenciais;
- estimar erro e avaliar quando uma aproximação é plausível.

**Protocolo para taxas relacionadas:** desenhar, definir variáveis, declarar o vínculo, diferenciar antes de substituir valores, resolver e interpretar sinal/unidade.

**Evidência de saída:** modelar um problema novo, justificar a equação de vínculo e explicar o significado do sinal da taxa encontrada.

### A8 - Informação global a partir de derivadas

**Objetivos:**

- encontrar extremos locais e absolutos em domínios adequados;
- compreender e aplicar os teoremas de Rolle e do Valor Médio;
- relacionar sinais de `f'` e `f''` a crescimento, concavidade e inflexão;
- usar a regra de L'Hôpital apenas após identificar forma indeterminada;
- construir esboço de curva coerente com domínio, interceptos, assíntotas e derivadas.

**Erros a vigiar:** chamar todo ponto crítico de máximo ou mínimo; ignorar extremos de intervalo; usar L'Hôpital fora das hipóteses; confundir `f'' = 0` com inflexão garantida.

**Evidência de saída:** produzir análise completa de uma função e reconstruir características de `f` a partir de informações sobre `f'`.

### A9 - Otimização e método de Newton

**Objetivos:**

- traduzir restrições verbais em equações;
- reduzir o problema a uma variável e definir domínio físico;
- localizar e justificar o ótimo global;
- interpretar sensibilidade e plausibilidade;
- compreender o método de Newton como linearização iterativa, incluindo casos de falha.

**Evidência de saída:** resolver dois problemas de otimização de estruturas diferentes e analisar uma solução incorreta que escolhe um ponto crítico inviável.

### A10 - Primitivas e movimento

**Objetivos:**

- reconhecer família de primitivas e papel da constante;
- determinar constante a partir de condição inicial;
- reconstruir velocidade e posição a partir de aceleração;
- preparar a distinção entre primitiva e integral definida.

**Evidência de saída:** resolver um problema de movimento com condições iniciais e interpretar constantes e unidades.

### A11 - Síntese

Realizar um conjunto cumulativo que combine funções, limites, derivadas e aplicações. Pelo menos um problema deve exigir modelagem; um deve exigir justificativa conceitual; um deve conter uma solução errada para diagnóstico; e um deve conectar derivada a acumulação, preparando o Teorema Fundamental do Cálculo.

## Gates de progressão

Além dos itens específicos, cada gate de unidade exige pelo menos 85% em conjunto misto, nenhum erro conceitual crítico, dois problemas rotineiros e um de transferência resolvidos sem ajuda. Isso autoriza avanço provisório; os estados operacional e consolidado dependem das confirmações tardias de `fundamentos.md`.

### Gate A-Funções

- domínio e composição sem erros estruturais;
- conversão entre representações;
- leitura de parâmetros e unidades;
- trigonometria e logaritmos suficientes para o capítulo 3.

### Gate A-Limites

- escolha correta entre substituição, fatoração, racionalização e análise lateral;
- continuidade analisada pelas três condições;
- interpretação de infinito e assíntota;
- explicação verbal do conceito de limite.

### Gate A-Derivação

- derivada pela definição em caso simples;
- regras aplicadas em conjunto misto com pelo menos 85% de precisão;
- regra da cadeia reconhecida em várias camadas;
- distinção entre erro algébrico e erro de regra.

### Gate A-Aplicações

- análise de gráfico a partir de derivadas;
- uma taxa relacionada independente;
- uma otimização independente;
- interpretação e verificação de resultados;
- retenção demonstrada em revisão posterior.

## Avaliação recomendada

- **Diagnóstico inicial:** pré-requisitos e representações.
- **Verificações de unidade:** 15 a 25 minutos, cumulativas a partir de A2.
- **Avaliação intermediária:** funções, limites e definição de derivada.
- **Avaliação técnica:** regras de derivação com seleção de método.
- **Avaliação de aplicações:** gráficos, taxas e otimização.
- **Avaliação final cumulativa:** 30% conceito, 40% técnica, 30% modelagem/transferência.

Corrigir por categoria de erro e exigir refação explicada. A nota, quando necessária, não substitui o mapa de evidências.

## Ritmo de referência

Em 16 semanas, usar aproximadamente:

- 2 semanas para A0 e recuperação focal;
- 3 semanas para A1 a A3;
- 4 semanas para A4 a A6;
- 4 semanas para A7 a A9;
- 1 semana para A10;
- 2 semanas distribuídas em revisão, avaliações e recuperação.

Se o diagnóstico revelar defasagem forte, aumentar o tempo de A0 a A4 e reduzir exercícios redundantes nas unidades já dominadas. Não comprimir regra da cadeia, interpretação de derivada ou otimização, pois são pré-requisitos persistentes.

## Instruções específicas ao agente tutor

- Começar limites e derivadas por problemas de variação, não por uma tabela de regras.
- Pedir previsão de sinal, tamanho e forma do gráfico antes da conta.
- Exigir que a regra da cadeia seja verbalizada como composição.
- Não deixar que software substitua domínio, argumento ou verificação; usá-lo para explorar e conferir.
- Em aplicações, avaliar separadamente modelagem, cálculo e interpretação.
- Inserir problemas mistos desde A5 para impedir dependência do rótulo da seção.
- Manter uma revisão curta de funções e álgebra enquanto houver erros recorrentes.

## Critério de conclusão e transição para Cálculo B

O estudante está pronto para Cálculo B quando consegue, em duas ocasiões diferentes:

- analisar funções e limites sem método indicado;
- derivar combinações de funções com boa precisão;
- interpretar derivada e unidades;
- resolver uma aplicação de taxas e uma de otimização;
- encontrar primitivas elementares;
- explicar a relação intuitiva entre taxa de variação e acumulação.

Se apenas a técnica estiver forte, mas a interpretação permanecer frágil, iniciar B com integração conceitual e manter revisão de modelagem. Se regra da cadeia, álgebra de funções ou primitivas estiverem abaixo do nível operacional, recuperar antes das técnicas de integração.
