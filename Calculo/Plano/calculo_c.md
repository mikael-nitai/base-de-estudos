# Cálculo C

## Missão da disciplina

Cálculo C amplia o cálculo de uma variável para curvas parametrizadas, coordenadas polares, curvas espaciais e funções de várias variáveis. A disciplina deve desenvolver visualização geométrica, mudança de representação e análise local em dimensões superiores, culminando em otimização com e sem restrições.

Este plano incorpora integralmente a ementa registrada em `../Referencias/ementa.md`:

- curvas definidas por equações paramétricas;
- cálculo com curvas parametrizadas;
- coordenadas polares, áreas e comprimentos;
- funções vetoriais e curvas espaciais;
- derivadas e integrais de funções vetoriais;
- comprimento de arco e curvatura;
- funções de várias variáveis, limites e continuidade;
- derivadas parciais;
- planos tangentes e aproximações lineares;
- regras de derivação;
- derivadas direcionais e vetor gradiente;
- valores máximo e mínimo;
- multiplicadores de Lagrange.

**Base principal:** Stewart, *Cálculo*, 7ª edição, volume 2, seções 10.1 a 10.4, capítulo 12 como ponte de pré-requisitos, seções 13.1 a 13.3 e capítulo 14.

**Enriquecimento opcional:** seção 13.4, movimento no espaço. As seções 10.5 e 10.6 sobre cônicas também podem ser usadas como revisão ou ampliação, mas não pertencem ao núcleo da ementa registrada.

**Plano compartilhado:** aplicar `fundamentos.md`. O capítulo 12 não altera a ementa; funciona como módulo preparatório para que a geometria vetorial não se torne uma dificuldade invisível dentro do cálculo.

## Resultado esperado

Ao concluir Cálculo C, o estudante deve ser capaz de:

- alternar entre representações cartesianas, paramétricas, polares e vetoriais;
- analisar tangentes, áreas e comprimentos de curvas parametrizadas e polares;
- descrever curvas espaciais e operar com funções vetoriais;
- interpretar funções de várias variáveis por gráficos, traços e curvas de nível;
- analisar limites e continuidade em mais de uma variável;
- calcular e interpretar derivadas parciais, direcionais e gradientes;
- construir planos tangentes e aproximações lineares;
- aplicar regras da cadeia e diferenciação implícita em várias variáveis;
- resolver otimização local, global e condicionada;
- justificar escolhas geométricas, domínios e restrições.

## Gate de entrada

Antes da unidade C1, verificar:

- domínio, composição e inversas;
- derivadas, regra da cadeia e derivação implícita;
- integrais definidas, substituição e comprimento de arco básico;
- trigonometria em radianos e identidades fundamentais;
- geometria analítica de retas e cônicas;
- vetores, produto escalar, produto vetorial, retas e planos.

Aplicar um diagnóstico com quatro tarefas de pré-requisito, sem cobrar conteúdos que serão ensinados em C:

1. analisar um gráfico trigonométrico em radianos;
2. derivar e integrar uma função composta elementar;
3. calcular produto escalar e determinar uma equação de plano a partir de dados suficientes;
4. usar regra da cadeia e interpretar a unidade de uma derivada.

Se vetores ou geometria espacial estiverem abaixo do nível operacional, realizar C0/F6 antes de C3. Se trigonometria polar estiver frágil, recuperar F5 antes de áreas polares.

## Arquitetura do curso

| Unidade | Conteúdo central | Referência Stewart |
|---|---|---|
| C0 | Vetores e geometria do espaço | 12.1 a 12.6 |
| C1 | Curvas paramétricas e cálculo | 10.1 e 10.2 |
| C2 | Coordenadas polares, áreas e comprimentos | 10.3 e 10.4 |
| C3 | Funções vetoriais e curvas espaciais | 13.1 e 13.2 |
| C4 | Comprimento de arco e curvatura | 13.3 |
| C+ | Movimento no espaço, opcional | 13.4 |
| C5 | Funções de várias variáveis e visualização | 14.1 |
| C6 | Limites e continuidade | 14.2 |
| C7 | Derivadas parciais | 14.3 |
| C8 | Planos tangentes, linearização e diferenciais | 14.4 |
| C9 | Regra da cadeia e diferenciação implícita | 14.5 |
| C10 | Derivadas direcionais e gradiente | 14.6 |
| C11 | Extremos livres e absolutos | 14.7 |
| C12 | Multiplicadores de Lagrange | 14.8 |
| C13 | Síntese geométrica e preparação para D | Revisões dos caps. 10, 12, 13 e 14 |

## Unidades detalhadas

### C0 - Vetores e geometria espacial

**Pergunta orientadora:** como traduzir relações geométricas no espaço para linguagem algébrica que o cálculo possa usar?

**Objetivos:**

- trabalhar com coordenadas tridimensionais, distância e esferas;
- decompor vetores e interpretar norma e direção;
- usar produto escalar para ângulo, projeção e ortogonalidade;
- usar produto vetorial para normal, área e orientação;
- escrever equações de retas e planos;
- reconhecer cilindros e superfícies quádricas por traços.

**Erros a vigiar:** confundir ponto e vetor; omitir normalização; interpretar produto vetorial como número; trocar vetor diretor por normal; desenhar superfície apenas pelo nome sem analisar traços.

**Evidência de saída:** resolver problema que combine projeção, reta/plano e interpretação de uma superfície por seus traços.

### C1 - Curvas parametrizadas

**Pergunta orientadora:** o que ganhamos ao descrever uma curva por posição ao longo de um parâmetro, em vez de apenas por uma equação cartesiana?

**Objetivos:**

- traçar orientação e identificar intervalos do parâmetro;
- eliminar parâmetro quando útil, sem perder sentido de percurso;
- construir parametrizações para curvas simples;
- calcular tangente e segunda derivada;
- calcular área, comprimento e área de superfície em casos previstos pela seção;
- interpretar parâmetro como tempo quando apropriado.

**Erros a vigiar:** ignorar orientação; assumir parametrização única; eliminar parâmetro e perder restrição; usar `dy/dx` sem verificar `dx/dt`; integrar comprimento sem norma positiva.

**Evidência de saída:** comparar duas parametrizações da mesma curva, calcular tangente e comprimento, e explicar o papel do intervalo do parâmetro.

### C2 - Coordenadas polares

**Pergunta orientadora:** quando distância e ângulo descrevem uma geometria de modo mais natural que `x` e `y`?

**Objetivos:**

- converter pontos e equações entre formas polar e cartesiana;
- compreender não unicidade de coordenadas polares;
- analisar simetrias e traçar curvas por comportamento angular;
- encontrar tangentes;
- montar áreas entre curvas polares;
- calcular comprimento de arco polar;
- escolher intervalos que percorrem a região exatamente uma vez.

**Erros a vigiar:** tratar representação polar como única; perder regiões por escolha de intervalo; integrar sobre percurso duplicado; confundir raio negativo com ponto inexistente; decorar formas sem testar ângulos.

**Evidência de saída:** esboçar uma curva a partir da equação, justificar intervalo e simetria, e montar uma área entre duas curvas.

### C3 - Funções vetoriais e curvas espaciais

**Objetivos:**

- interpretar função vetorial como trajetória;
- obter limites e continuidade por componentes;
- diferenciar e integrar funções vetoriais;
- construir reta tangente;
- aplicar regras de derivação com produtos escalar e vetorial;
- relacionar posição, velocidade e aceleração.

**Erros a vigiar:** confundir curva com superfície; esquecer que operações são por componentes; perder interpretação geométrica da derivada; aplicar regra de produto escalar como produto ordinário.

**Evidência de saída:** analisar trajetória espacial, obter tangente e reconstruir posição a partir de dados de velocidade e condição inicial.

### C4 - Comprimento de arco e curvatura

**Objetivos:**

- parametrizar por comprimento de arco em casos acessíveis;
- compreender vetor tangente unitário;
- calcular e interpretar curvatura;
- obter vetores normal e binormal quando incluídos.

**Erros a vigiar:** usar vetor tangente não unitário em fórmulas; tratar curvatura apenas como conta; ignorar domínio onde a derivada se anula; confundir curvatura alta com rapidez alta.

**Evidência de saída:** interpretar o vetor tangente e comparar geometricamente a curvatura de dois trechos ou curvas.

### C+ - Enriquecimento opcional: movimento no espaço

Ativar somente se houver tempo, interesse ou exigência institucional.

**Objetivos:** relacionar posição, velocidade, rapidez e aceleração; decompor aceleração em componentes tangencial e normal; interpretar mudança de rapidez e direção; aplicar a trajetórias espaciais.

**Evidência de saída:** explicar geometricamente as componentes tangencial e normal e resolver um problema de movimento com unidades consistentes.

### C5 - Funções de várias variáveis

**Pergunta orientadora:** como representar uma função cujo valor depende simultaneamente de duas ou mais entradas?

**Objetivos:**

- determinar domínios no plano e no espaço;
- interpretar gráficos de superfícies;
- usar curvas de nível e traços;
- alternar entre fórmula, superfície, mapa de contorno e descrição;
- reconhecer superfícies quádricas relevantes;
- interpretar unidades e parâmetros em modelos multivariados.

**Erros a vigiar:** confundir domínio com gráfico; ler curva de nível como trajetória temporal; ignorar restrições combinadas; tentar visualizar sem usar traços ou níveis.

**Evidência de saída:** descrever uma superfície por domínio, traços e níveis, e reconstruir informação qualitativa a partir de mapa de contorno.

### C6 - Limites e continuidade em várias variáveis

**Pergunta orientadora:** por que testar algumas trajetórias pode provar que um limite não existe, mas normalmente não prova que ele existe?

**Objetivos:**

- estimar limites por tabela, gráfico e trajetórias;
- usar trajetórias distintas para demonstrar não existência;
- aplicar propriedades de limites e continuidade;
- usar desigualdades, coordenadas polares ou comparação para provar existência em casos adequados;
- compreender a multiplicidade de caminhos de aproximação.

**Erros a vigiar:** verificar apenas eixos; concluir existência após testar duas curvas; usar polar sem controlar dependência angular; confundir continuidade por componentes com casos escalares inadequados.

**Evidência de saída:** apresentar um exemplo de não existência por caminhos e um argumento válido de existência com estimativa independente do caminho.

### C7 - Derivadas parciais

**Objetivos:**

- calcular parciais de primeira e ordens superiores;
- interpretar cada parcial mantendo outras variáveis fixas;
- relacionar parciais a inclinações de traços;
- analisar unidades;
- usar igualdade de derivadas mistas sob hipóteses apropriadas;
- interpretar aplicações, inclusive modelos de produção quando úteis.

**Erros a vigiar:** diferenciar todas as variáveis ao mesmo tempo; perder variável mantida constante; confundir parcial com derivada total; omitir unidades ou significado.

**Evidência de saída:** calcular, interpretar e estimar parciais por fórmula, tabela e mapa de contorno.

### C8 - Plano tangente e aproximação linear

**Objetivos:**

- construir plano tangente a gráfico;
- compreender diferenciabilidade como boa aproximação linear;
- usar linearização e diferenciais;
- estimar propagação de erro;
- distinguir existência de parciais de diferenciabilidade.

**Erros a vigiar:** usar fórmula sem ponto-base; concluir diferenciabilidade apenas por existência de parciais; confundir plano tangente a gráfico com plano de nível; omitir deslocamentos nas variáveis.

**Evidência de saída:** construir aproximação linear, estimar valor próximo e explicar geometricamente o erro esperado.

### C9 - Regras de derivação em várias variáveis

**Objetivos:**

- aplicar regra da cadeia em árvores de dependência;
- calcular derivadas totais ao longo de trajetórias;
- usar diferenciação implícita em relações multivariadas;
- distinguir variáveis independentes, intermediárias e dependentes;
- verificar dimensões e casos reduzidos.

**Erros a vigiar:** omitir caminhos de dependência; misturar parciais e derivadas ordinárias; usar notação sem declarar relações; perder termos na regra da cadeia.

**Evidência de saída:** desenhar diagrama de dependências e resolver problemas com uma e múltiplas variáveis intermediárias.

### C10 - Derivadas direcionais e gradiente

**Pergunta orientadora:** como medir a taxa de variação em qualquer direção e encontrar a direção de crescimento mais rápido?

**Objetivos:**

- calcular derivada direcional com vetor unitário;
- interpretar gradiente como vetor de máxima taxa de crescimento;
- relacionar gradiente a curvas e superfícies de nível;
- construir planos tangentes a superfícies de nível;
- aplicar a contextos de temperatura, relevo e campos escalares.

**Erros a vigiar:** não normalizar direção; confundir direção com ponto; interpretar gradiente como tangente ao nível; calcular sem avaliar no ponto.

**Evidência de saída:** extrair direção e taxa máxima, encontrar direção de nenhuma variação e justificar ortogonalidade ao nível.

### C11 - Valores máximos e mínimos

**Objetivos:**

- encontrar pontos críticos;
- usar teste da segunda derivada e reconhecer casos inconclusivos;
- distinguir extremos locais, absolutos e pontos de sela;
- buscar extremos absolutos em regiões fechadas e limitadas, incluindo fronteira;
- interpretar soluções e restrições de domínio.

**Erros a vigiar:** ignorar fronteira; tratar determinante nulo como classificação; esquecer pontos onde derivadas não existem; confundir ponto crítico com extremo.

**Evidência de saída:** classificar pontos e resolver extremo absoluto em região com análise explícita do interior e fronteira.

### C12 - Multiplicadores de Lagrange

**Pergunta orientadora:** por que, em um extremo condicionado, o gradiente da função objetivo se alinha ao gradiente da restrição?

**Objetivos:**

- interpretar geometricamente a condição de Lagrange;
- formular sistema para uma restrição;
- tratar mais de uma restrição quando previsto;
- encontrar candidatos e compará-los;
- reconhecer falhas quando gradiente da restrição se anula ou a região exige análise adicional;
- conectar solução a unidades e contexto.

**Erros a vigiar:** resolver sistema sem verificar restrição; aceitar todos os candidatos como extremos; ignorar casos singulares; aplicar Lagrange quando parametrização ou fronteira direta é mais clara.

**Evidência de saída:** resolver um problema geométrico e um aplicado, justificar a condição de paralelismo e comparar candidatos.

### C13 - Síntese

Realizar um conjunto cumulativo com conversão entre representações, curva espacial, limite multivariado, linearização, regra da cadeia, gradiente e otimização. Incluir um problema que conecte Cálculo C a integrais múltiplas: interpretar uma região por curvas de nível ou coordenadas e prever qual sistema de coordenadas simplificará sua acumulação.

## Gates de progressão

Além dos itens específicos, cada gate de unidade exige pelo menos 85% em conjunto misto, nenhum erro conceitual crítico, dois problemas rotineiros e um de transferência resolvidos sem ajuda. Isso autoriza avanço provisório; os estados operacional e consolidado dependem das confirmações tardias de `fundamentos.md`.

### Gate C-Geometria e representações

- vetores, retas e planos operacionais;
- conversão cartesiana-paramétrica-polar;
- intervalo e orientação justificados;
- esboço coerente sem depender apenas de software.

### Gate C-Curvas vetoriais

- derivação e integração por componentes;
- interpretação geométrica de função vetorial e sua derivada;
- tangente, comprimento e curvatura conectados à geometria;
- produto escalar e norma usados corretamente.

### Gate C-Diferenciação multivariada

- limites analisados com lógica de caminhos correta;
- parciais interpretadas;
- diferenciabilidade distinguida de existência de parciais;
- regra da cadeia completa;
- gradiente interpretado geometricamente.

### Gate C-Otimização

- classificação local e análise de fronteira;
- extremos absolutos em região adequada;
- Lagrange formulado e interpretado;
- candidatos comparados e solução contextualizada.

## Avaliação recomendada

- avaliação 1: vetores, parametrização e polar;
- avaliação 2: funções vetoriais, comprimento e curvatura;
- avaliação 3: funções multivariadas, limites, parciais e linearização;
- avaliação 4: regra da cadeia, gradiente e otimização;
- final cumulativa com pelo menos uma tarefa de visualização, uma demonstração de não existência, uma aplicação e uma análise de erro.

Questões devem alternar fórmula, gráfico, mapa de contorno, descrição verbal e representação tridimensional. Avaliar separadamente visualização, montagem, cálculo e interpretação.

## Ritmo de referência

Em 18 semanas, usar aproximadamente:

- 2 semanas para C0 e recuperação;
- 3 semanas para C1 e C2;
- 3 semanas para C3 e C4;
- 2 semanas para C5 e C6;
- 4 semanas para C7 a C10;
- 2 semanas para C11 e C12;
- 2 semanas distribuídas em revisão, avaliações e síntese.

Se a geometria espacial estiver frágil, ampliar C0 e continuar revisões curtas ao longo do curso. Não comprimir limites multivariados, regra da cadeia ou gradiente: esses tópicos sustentam otimização e Cálculo D.

Se C+ for ativado, integrá-lo à revisão de C3 e C4 sem reduzir o tempo dedicado ao núcleo da ementa.

## Instruções específicas ao agente tutor

- Exigir desenhos, traços ou curvas de nível antes de fórmulas em problemas geométricos.
- Pedir que o estudante declare o sistema de coordenadas e justifique sua escolha.
- Usar software 3D para exploração e conferência, nunca como substituto de domínio ou argumento.
- Em limites, perguntar explicitamente o que um teste por caminho pode e não pode provar.
- Em parciais e gradiente, exigir interpretação em frase completa e unidade.
- Em regra da cadeia, usar diagramas de dependência até que nenhum termo seja perdido.
- Em otimização, separar geração de candidatos, classificação/comparação e interpretação.
- Intercalar problemas de uma variável quando uma dificuldade de A ou B reaparecer.

## Critério de conclusão e transição para Cálculo D

O estudante está pronto para Cálculo D quando consegue, em avaliações separadas:

- representar regiões e curvas em coordenadas adequadas;
- operar com vetores, curvas e superfícies;
- interpretar e calcular gradiente e derivadas direcionais;
- construir linearizações e aplicar regra da cadeia;
- resolver otimização livre e condicionada;
- usar integrais de uma variável e coordenadas polares sem lacunas estruturais;
- explicar orientação, domínio e geometria de uma montagem.

Se a técnica estiver correta, mas a visualização for frágil, iniciar D com regiões e somas duplas, mantendo exercícios de traços e coordenadas. Se gradiente, produto vetorial ou parametrização estiverem abaixo do nível operacional, recuperar antes de integrais de linha e superfície.
