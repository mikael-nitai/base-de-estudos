# Cálculo D

## Missão da disciplina

Cálculo D desenvolve integração em duas e três dimensões e cálculo vetorial. O curso conecta acumulação, geometria, campos e orientação, culminando nos teoremas de Green, Stokes e Divergente como diferentes manifestações de uma mesma relação entre comportamento no interior e na fronteira.

Este arquivo propõe uma continuação natural do plano A-C. Como ainda não há ementa institucional registrada para Cálculo D, o núcleo foi baseado nos capítulos restantes de cálculo multivariável do Stewart. O capítulo 17 aparece apenas como extensão e não deve ser marcado como requisito ou concluído sem confirmação da disciplina real.

**Base principal:** Stewart, *Cálculo*, 7ª edição, volume 2, capítulos 15 e 16.

**Extensão opcional:** capítulo 17, equações diferenciais de segunda ordem.

**Plano compartilhado:** aplicar `fundamentos.md`, com atenção especial à escolha de coordenadas, parametrização, gradiente, produto vetorial, orientação e interpretação de integrais.

## Resultado esperado

Ao concluir o núcleo de Cálculo D, o estudante deve ser capaz de:

- interpretar integrais múltiplas como acumulação e volume por somas;
- descrever regiões e escolher ordem e sistema de coordenadas eficientes;
- calcular e aplicar integrais duplas e triplas;
- usar coordenadas polares, cilíndricas e esféricas com jacobianos corretos;
- interpretar campos vetoriais, circulação, trabalho e fluxo;
- reconhecer campos conservativos e independência de caminho;
- parametrizar curvas e superfícies com orientação consistente;
- calcular integrais de linha e superfície;
- escolher e aplicar Green, Stokes e Divergente com hipóteses verificadas;
- explicar a relação entre derivadas locais de campos e integrais sobre regiões ou fronteiras.

## Gate de entrada

Antes de D1, verificar:

- integrais definidas, substituição e Teorema Fundamental do Cálculo;
- regiões no plano, coordenadas polares e áreas;
- funções de várias variáveis, domínio e curvas de nível;
- vetores, produtos escalar e vetorial;
- parametrização de curvas, orientação e comprimento de arco;
- derivadas parciais, gradiente e regra da cadeia;
- equações de retas, planos, superfícies e coordenadas espaciais.

Aplicar diagnóstico com cinco tarefas de pré-requisito, sem cobrar técnicas que serão ensinadas em D:

1. esboçar uma região dada por desigualdades;
2. calcular uma integral definida de uma variável contendo um parâmetro tratado como constante e interpretar suas unidades;
3. converter pontos e curvas elementares entre coordenadas cartesianas e polares;
4. parametrizar curva e calcular vetor tangente;
5. calcular gradiente, produto escalar e produto vetorial elementares e interpretar geometricamente.

Lacunas em regiões e integrais devem ser recuperadas antes de D2. Lacunas em vetores e parametrização podem ser tratadas em paralelo ao primeiro bloco de integrais múltiplas, mas devem estar resolvidas antes de D7.

## Arquitetura do curso

| Unidade | Conteúdo central | Referência Stewart |
|---|---|---|
| D0 | Recuperação geométrica e soma dupla | Pré-requisitos; revisão do cap. 14 |
| D1 | Integrais duplas sobre retângulos e iteradas | 15.1 e 15.2 |
| D2 | Regiões gerais e mudança de ordem | 15.3 |
| D3 | Integrais duplas em coordenadas polares | 15.4 |
| D4 | Aplicações e área de superfície | 15.5 e 15.6 |
| D5 | Integrais triplas e coordenadas cilíndricas/esféricas | 15.7 a 15.9 |
| D6 | Mudança de variáveis e jacobiano | 15.10 |
| D7 | Campos vetoriais | 16.1 |
| D8 | Integrais de linha e campos conservativos | 16.2 e 16.3 |
| D9 | Teorema de Green | 16.4 |
| D10 | Rotacional e divergente | 16.5 |
| D11 | Superfícies parametrizadas e áreas | 16.6 |
| D12 | Integrais de superfície e fluxo | 16.7 |
| D13 | Teoremas de Stokes e Divergente | 16.8 a 16.10 |
| D14 | Síntese e projeto integrador | Revisões dos caps. 15 e 16 |
| D+ | EDOs de segunda ordem, opcional | 17.1 a 17.4 |

## Unidades detalhadas

### D0 - Da soma simples à acumulação multivariada

**Pergunta orientadora:** como acumular uma grandeza distribuída sobre uma região quando cada contribuição depende de duas variáveis?

**Objetivos:**

- revisar regiões, superfícies e curvas de nível;
- revisar determinantes de ordem 2 e 3 e sua interpretação como escala orientada;
- construir somas duplas sobre partições retangulares;
- interpretar volume e acumulação;
- prever sinal, unidade e ordem de grandeza;
- conectar integral dupla ao processo iterado.

**Evidência de saída:** escrever uma soma aproximada e a integral correspondente, explicando unidades de cada fator.

### D1 - Integrais duplas e integrais iteradas

**Objetivos:**

- definir integral dupla sobre retângulo;
- aplicar Fubini em condições apropriadas;
- calcular integrais iteradas em ambas as ordens;
- interpretar valor médio;
- usar simetria quando válida;
- comparar cálculo iterado com significado geométrico.

**Erros a vigiar:** trocar limites internos e externos; tratar variável externa como variável de integração interna; perder unidade de área; usar simetria sem verificar domínio e integrando.

**Evidência de saída:** montar e calcular uma integral nas duas ordens e explicar qual ordem é mais eficiente.

### D2 - Regiões gerais e mudança de ordem

**Pergunta orientadora:** como a descrição da região determina os limites de integração?

**Objetivos:**

- descrever regiões do tipo I e II;
- desenhar antes de montar limites;
- dividir regiões quando uma única descrição não basta;
- inverter ordem de integração;
- avaliar integrais cuja ordem original é difícil;
- distinguir fronteira da região e região de integração.

**Erros a vigiar:** projetar sobre eixo errado; usar interseções sem verificar intervalo; esquecer de dividir região; manipular limites sem desenho; confundir ordem de escrita com ordem de integração.

**Evidência de saída:** converter entre desigualdades, desenho e integrais nas duas ordens para uma região não trivial.

### D3 - Coordenadas polares em integrais duplas

**Objetivos:**

- reconhecer simetria radial ou angular;
- transformar região e integrando;
- explicar geometricamente o fator `r`;
- escolher intervalos sem duplicação;
- calcular áreas e integrais em discos, anéis, setores e regiões delimitadas por curvas polares.

**Erros a vigiar:** esquecer o jacobiano `r`; converter integrando e não região; usar ângulo inadequado; integrar região duas vezes; tratar `r` como constante.

**Evidência de saída:** justificar por que polar simplifica um problema, montar limites e explicar a origem do elemento de área.

### D4 - Aplicações de integrais duplas

**Objetivos:**

- calcular massa com densidade variável;
- determinar momentos, centro de massa e momento de inércia;
- interpretar valores esperados em aplicações selecionadas;
- calcular área de superfície de gráfico;
- usar simetria física e geométrica com justificativa;
- verificar unidades em cada integral.

**Evidência de saída:** modelar uma lâmina não uniforme e interpretar centro de massa antes e depois do cálculo.

### D5 - Integrais triplas e coordenadas espaciais

**Objetivos:**

- descrever sólidos por desigualdades e superfícies;
- montar integrais triplas em diferentes ordens;
- calcular volume, massa e valor médio;
- usar coordenadas cilíndricas e esféricas;
- explicar elementos de volume `r` e `rho^2 sen(phi)` geometricamente;
- escolher coordenadas conforme simetria do sólido e do integrando.

**Erros a vigiar:** confundir ângulos esféricos; esquecer jacobiano; descrever projeção incorreta; escolher coordenadas por aparência da fórmula sem considerar a região; omitir limites radiais dependentes.

**Evidência de saída:** montar o mesmo sólido em dois sistemas e defender a escolha mais eficiente, com desenho de projeções e seções.

### D6 - Mudança de variáveis e jacobiano

**Pergunta orientadora:** como uma transformação deforma pequenas áreas ou volumes?

**Objetivos:**

- interpretar transformação e imagem de regiões;
- calcular matriz jacobiana e determinante;
- compreender valor absoluto e fator de escala local;
- escolher transformações alinhadas às fronteiras;
- determinar nova região e avaliar integral;
- verificar injetividade ou particionar quando necessário.

**Erros a vigiar:** usar jacobiano inverso; esquecer valor absoluto; transformar integrando e não limites; escolher transformação não injetiva; tratar jacobiano como regra decorada.

**Evidência de saída:** desenhar a região nos dois planos, explicar o fator de escala e completar uma mudança de variáveis.

### D7 - Campos vetoriais

**Objetivos:**

- interpretar campo como vetor associado a cada ponto;
- esboçar campos e identificar padrões;
- reconhecer campos gradiente;
- relacionar campo a fluxo, força ou velocidade;
- calcular gradiente de potencial;
- antecipar circulação e divergência por visualização.

**Erros a vigiar:** confundir campo com curva; desenhar vetores sem respeitar posição; concluir conservatividade apenas pela aparência; ignorar domínio.

**Evidência de saída:** comparar campo, potencial e curvas de nível, explicando a ortogonalidade relevante.

### D8 - Integrais de linha e campos conservativos

**Objetivos:**

- parametrizar curva com orientação e intervalo;
- calcular integrais de linha escalares;
- calcular trabalho de campo vetorial;
- compreender independência de caminho;
- aplicar o Teorema Fundamental das Integrais de Linha;
- encontrar potencial e verificar domínio;
- relacionar conservação de energia a campos conservativos.

**Erros a vigiar:** esquecer elemento de comprimento em integral escalar; trocar orientação sem alterar sinal; confundir `ds` com `dr`; procurar potencial sem verificar compatibilidade; usar independência de caminho em domínio com obstáculo sem análise.

**Evidência de saída:** calcular trabalho diretamente e por potencial, explicar a diferença de custo e justificar as hipóteses.

### D9 - Teorema de Green

**Pergunta orientadora:** como uma integral ao longo da fronteira se relaciona ao comportamento do campo em toda a região plana?

**Objetivos:**

- orientar positivamente fronteiras;
- aplicar formas de circulação e fluxo;
- converter integral de linha em dupla e vice-versa;
- lidar com regiões simples e com furos quando incluídas;
- escolher o lado mais eficiente;
- usar Green para áreas em casos apropriados.

**Erros a vigiar:** orientação invertida; troca entre derivadas da forma de circulação; aplicar em região/domínio que viola hipóteses sem ajuste; ignorar componentes de fronteira.

**Evidência de saída:** resolver o mesmo problema pelos dois lados do teorema e explicar a equivalência geométrica.

### D10 - Rotacional e divergente

**Objetivos:**

- calcular e interpretar rotacional e divergente;
- relacionar rotacional a circulação local;
- relacionar divergente a fonte ou sumidouro local;
- reconhecer identidades vetoriais fundamentais quando hipóteses permitem;
- conectar as formas vetoriais de Green aos teoremas posteriores.

**Erros a vigiar:** decorar determinante sem interpretação; confundir rotacional escalar planar com vetor tridimensional; interpretar divergente como direção; ignorar domínio e regularidade.

**Evidência de saída:** prever sinais por esboço, calcular e reconciliar cálculo com interpretação física.

### D11 - Superfícies parametrizadas

**Objetivos:**

- construir parametrizações para planos, gráficos, cilindros, esferas e superfícies de revolução;
- identificar domínio de parâmetros;
- obter vetores tangentes e normal por produto vetorial;
- escolher orientação;
- calcular área de superfície;
- reconhecer parametrizações que cobrem a superfície múltiplas vezes.

**Erros a vigiar:** usar parâmetros dependentes; escolher domínio que duplica superfície; normalizar quando não deve ou deixar de normalizar quando deve; perder orientação no produto vetorial.

**Evidência de saída:** parametrizar uma superfície, justificar domínio e orientação e calcular/interpretar seu elemento de área.

### D12 - Integrais de superfície e fluxo

**Objetivos:**

- integrar funções escalares sobre superfícies;
- calcular fluxo de campos por superfícies orientadas;
- alternar entre parametrização e fórmula para gráficos;
- interpretar sinal e unidade de fluxo;
- tratar superfícies fechadas e orientação exterior;
- verificar resultados por simetria e comportamento do campo.

**Erros a vigiar:** confundir área de superfície com fluxo; usar normal unitária junto ao elemento vetorial incorreto; inverter orientação; esquecer partes de superfície fechada.

**Evidência de saída:** montar um fluxo com orientação explícita e justificar o sinal esperado antes de calcular.

### D13 - Stokes, Divergente e visão unificada

**Objetivos:**

- aplicar Stokes relacionando circulação na fronteira ao rotacional na superfície;
- aplicar Divergente relacionando fluxo fechado à divergência no volume;
- escolher superfícies ou volumes convenientes;
- verificar orientação pela regra da mão direita;
- comparar FTC de uma variável, FTC de integrais de linha, Green, Stokes e Divergente;
- reconhecer hipóteses, fronteiras e dimensões de cada teorema.

**Erros a vigiar:** usar Stokes em curva não fechada; esquecer que Divergente exige superfície fechada; incompatibilidade de orientação; trocar rotacional por divergente; escolher teorema pelo nome da seção, não pela estrutura.

**Evidência de saída:** receber problemas mistos e escolher entre cálculo direto, Green, Stokes, Divergente ou potencial, justificando a escolha e as hipóteses.

### D14 - Projeto integrador

Construir um projeto ou conjunto de problemas que conecte:

- representação de região/superfície;
- escolha de coordenadas;
- integral múltipla de uma grandeza física;
- campo vetorial;
- circulação ou fluxo;
- comparação entre cálculo direto e teorema integral;
- interpretação de unidades e orientação;
- verificação numérica ou visual sem substituir a solução analítica.

O produto deve incluir uma explicação curta de por que cada representação e teorema foi escolhido.

### D+ - Extensão opcional: equações diferenciais de segunda ordem

Ativar somente se a ementa institucional, objetivo pessoal ou aplicação justificar.

**Conteúdo:** equações lineares homogêneas e não homogêneas, coeficientes indeterminados, variação de parâmetros, vibrações, circuitos e soluções em séries.

**Pré-requisitos:** extensão B+ de EDOs de primeira ordem, álgebra de números complexos quando necessária, séries de B8 e interpretação física de condições iniciais.

## Gates de progressão

Além dos itens específicos, cada gate de unidade exige pelo menos 85% em conjunto misto, nenhum erro conceitual crítico, dois problemas rotineiros e um de transferência resolvidos sem ajuda. Isso autoriza avanço provisório; os estados operacional e consolidado dependem das confirmações tardias de `fundamentos.md`.

### Gate D-Integrais múltiplas

- região desenhada e descrita por desigualdades;
- ordem de integração escolhida conscientemente;
- integral dupla/tripla montada sem rótulo;
- unidades e sinal interpretados;
- mudança de ordem realizada em exemplo não trivial.

### Gate D-Coordenadas e jacobianos

- polar, cilíndrica e esférica escolhidas por simetria;
- região e integrando transformados;
- jacobiano explicado como fator de escala;
- limites sem duplicação;
- comparação com sistema alternativo.

### Gate D-Integrais de linha

- parametrização e orientação corretas;
- distinção entre integral escalar e trabalho;
- potencial encontrado e domínio verificado;
- independência de caminho justificada;
- Green aplicado com orientação correta.

### Gate D-Superfícies e teoremas

- parametrização e normal coerentes;
- fluxo interpretado;
- Stokes e Divergente aplicados com hipóteses explícitas;
- escolha entre teoremas em conjunto misto;
- visão unificada interior-fronteira explicada verbalmente.

## Avaliação recomendada

- avaliação 1: integrais duplas, regiões e polar;
- avaliação 2: integrais triplas, coordenadas e jacobiano;
- avaliação 3: campos, integrais de linha, conservatividade e Green;
- avaliação 4: superfícies, fluxo, Stokes e Divergente;
- projeto ou final cumulativa com seleção de representação e teorema.

Pelo menos metade das questões avaliativas deve exigir montagem, escolha ou interpretação, não apenas cálculo de integral já fornecida. Incluir tarefas de desenho, orientação, análise de hipóteses e solução incorreta.

## Ritmo de referência

Em 18 semanas, usar aproximadamente:

- 1 semana para D0;
- 4 semanas para D1 a D4;
- 3 semanas para D5 e D6;
- 3 semanas para D7 a D10;
- 4 semanas para D11 a D13;
- 3 semanas distribuídas em revisão, recuperação, avaliações e projeto.

Se houver dificuldade de visualização, reduzir o número de integrais repetitivas e aumentar atividades de desenho, seções, projeções e mudança de representação. Não comprimir orientação, parametrização ou escolha de teorema, pois erros nesses pontos contaminam todo o cálculo vetorial.

## Instruções específicas ao agente tutor

- Exigir desenho ou descrição geométrica antes de limites de integração.
- Perguntar “qual é a pequena contribuição?” e “qual é a fronteira?” em todo novo tipo de integral.
- Fazer previsão de sinal, unidade e ordem de grandeza antes do cálculo.
- Em mudança de coordenadas, transformar separadamente região, integrando e elemento diferencial.
- Em linha e superfície, declarar orientação antes de parametrizar.
- Ensinar Green, Stokes e Divergente por comparação estrutural, não como três fórmulas isoladas.
- Usar conjuntos mistos para treinar escolha entre cálculo direto, potencial e teoremas integrais.
- Usar visualização computacional para explorar regiões e campos, mantendo montagem e justificativa humanas.

## Critério de conclusão

Cálculo D está concluído quando o estudante demonstra, em ocasiões diferentes:

- montagem independente de integrais múltiplas;
- escolha eficiente de coordenadas e jacobiano correto;
- cálculo e interpretação de trabalho, circulação e fluxo;
- parametrização e orientação de curvas e superfícies;
- uso justificado de Green, Stokes e Divergente;
- capacidade de comparar os teoremas e explicar a relação entre interior e fronteira;
- retenção em avaliação cumulativa sem indicação do método.

O capítulo 17 só deve constar como concluído se tiver sido explicitamente estudado e avaliado. Sua presença como extensão não altera a conclusão do núcleo de Cálculo D.
