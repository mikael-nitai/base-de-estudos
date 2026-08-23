# Física 2

## Missão da disciplina

Física 2 estende a Mecânica para gravitação e sistemas orbitais e conecta três níveis de descrição: comportamento microscópico, variáveis macroscópicas e princípios termodinâmicos. A sequência institucional também reúne fluidos, movimento periódico, ondas mecânicas, som, temperatura, teoria cinética e as duas leis da Termodinâmica.

A ideia organizadora é compreender como modelos locais e princípios de conservação se conectam:

**gravitação e campo → oscilador → onda e modos → descrição microscópica → temperatura e pressão → energia e entropia.**

**Base institucional:** FISI0261 – Física 2, Departamento de Física da Universidade Federal de Sergipe. O programa oficial inclui leis de Kepler e gravitação de Newton, energia potencial e velocidade de escape, fluidos, MHS, pêndulos, amortecimento, forçamento, ondas mecânicas, ondas estacionárias, batimentos, Doppler, temperatura, gases ideais, teoria cinética, primeira e segunda leis, máquinas térmicas e entropia.

**Base bibliográfica:** Sears, Zemansky, Young e Freedman, Física II, 12ª edição; Halliday, Resnick e Krane, Fundamentos de Física, volume 2; Alonso e Finn, volume 1; além de Tipler e Mosca e Nussenzveig, volume 2, conforme o programa oficial. Os PDFs disponíveis no repositório estão identificados em [Física/Referencias/catalogo.md](../Referencias/catalogo.md).

### Materiais enviados para Física 2

- `F2-TIPLER-MOSCA-V1-2009`: usar os capítulos 11, 13–20; os capítulos 1–10 pertencem ao escopo de Física 1 e não devem ser atribuídos automaticamente a esta disciplina.
- `F2-NUSSENZVEIG-V2-2002`: usar os capítulos 1–11 para o núcleo T2–T10; o capítulo 12 é aprofundamento de mecânica estatística.
- Ao propor exercícios, registrar o ID, capítulo/seção e problema. O catálogo é a fonte de associação entre PDF e disciplina.

## Resultado esperado

Ao concluir Física 2, o estudante deve ser capaz de:

- usar campo, energia e momento angular para analisar gravitação e órbitas;
- modelar pressão, empuxo e escoamento com sistema e regime definidos;
- construir e interpretar o modelo de oscilador harmônico;
- relacionar oscilações, energia, ondas, interferência e ressonância;
- interpretar temperatura e pressão como variáveis macroscópicas ligadas a movimento microscópico;
- aplicar a primeira lei como balanço de energia;
- distinguir processo, estado, calor e trabalho;
- interpretar a segunda lei, máquinas térmicas e entropia;
- verificar unidades, sinais, limites e hipóteses;
- transferir princípios para situações de ondas, fluidos e fenômenos astronômicos.

## Gate de entrada

Exigir desempenho operacional em:

- diagramas de sistema e conservação de Física 1;
- trabalho, energia potencial e momento angular;
- vetores, gráficos e trigonometria;
- derivadas e integrais elementares conforme o problema;
- leitura de gráficos e análise dimensional.

Para MHS, exponenciais de amortecimento e circuitos conceituais, uma EDO simples pode ser necessária. Se a lacuna for estrutural, apontar para Equações Diferenciais; não marcar uma dificuldade matemática como falha de Física.

## Arquitetura do curso

| Unidade | Conteúdo central | Habilidades estáveis | Pré-requisitos principais |
|---|---|---|---|
| T0 | Ponte: conservação, campo, periódicos e temperatura | F2-modelo-estado-processo | Física 1; PF4–PF6 |
| T1 | Gravitação, Kepler e órbitas | F2-gravitacao-orbita-energia | F1-energia; F1-momento-angular |
| T2 | Fluidos em equilíbrio | F2-fluido-pressao-empuxo | forças, energia, densidade |
| T3 | Fluidos em movimento | F2-fluido-continuidade-bernoulli | T2; conservação |
| T4 | Oscilações e MHS | F2-oscilacoes-modelo-mhs | trigonometria; EDO simples |
| T5 | Amortecimento, forçamento e ressonância | F2-oscilacoes-ressonancia | T4 |
| T6 | Ondas mecânicas e energia | F2-ondas-equacao-parametros | T4; funções periódicas |
| T7 | Superposição, estacionárias, som e Doppler | F2-ondas-superposicao-doppler | T6 |
| T8 | Temperatura, teoria cinética e gases | F2-termodinamica-micro-macro | T6; álgebra e estatística básica |
| T9 | Calor, trabalho e primeira lei | F2-termodinamica-primeira-lei | T8; energia F1 |
| T10 | Segunda lei, Carnot e entropia | F2-termodinamica-entropia | T9 |
| T11 | Síntese e transição | F2-transferencia-termo-ondas | T0–T10 |

A ordem segue o programa oficial, mas usa oscilador e energia como ponte conceitual em vez de tratar os tópicos como capítulos independentes.

## Unidades detalhadas

### T0 — Ponte entre conservação, campo, oscilação e termodinâmica

**Pergunta orientadora:** que padrões permanecem úteis quando o sistema deixa de ser uma partícula simples?

**Objetivos:**

- recuperar sistema, fronteira e conservação;
- distinguir campo gravitacional de força gravitacional;
- reconhecer estado, processo e variável de estado;
- identificar periodicidade e equilíbrio estável;
- revisar energia, momento e unidades;
- separar previsão qualitativa de cálculo.

**Erros a vigiar:** tratar calor como substância; confundir campo com força; assumir que periodicidade implica MHS; usar conservação sem declarar sistema.

**Evidência de saída:** comparar uma órbita, um oscilador e um gás como sistemas modelados por variáveis e leis diferentes, apontando o que é conservado e sob quais hipóteses.

### T1 — Gravitação, leis de Kepler e órbitas

**Pergunta orientadora:** como uma lei de interação central produz órbitas, períodos e velocidades de escape?

**Objetivos:**

- interpretar a lei de gravitação de Newton;
- distinguir força, campo, potencial e energia potencial gravitacional;
- conectar simetria e interação central;
- interpretar qualitativamente as leis de Kepler;
- analisar órbitas circulares e elípticas em nível introdutório;
- usar conservação de energia e momento angular;
- calcular velocidade de escape e discutir referência de energia;
- estimar escalas astronômicas e limites de validade do modelo de dois corpos.

**Representações essenciais:** vetores radiais, campo, gráfico de potencial efetivo introdutório, órbita com áreas varridas, diagrama de energia e sistema corpo–fonte.

**Erros a vigiar:** confundir g local com G; tratar órbita como movimento circular sempre; escolher zero de energia sem declarar; usar terceira lei fora da hipótese de sistema adequado; confundir massa gravitacional e peso; esquecer que velocidade é tangencial em órbita circular.

**Evidência de saída:** resolver uma órbita circular e um problema de energia sem método indicado, explicar o papel do momento angular e estimar se uma hipótese de campo uniforme é plausível.

**Conexão com Astrofísica:** órbitas planetárias, satélites, massas estimadas e velocidades de escape.

### T2 — Fluidos em equilíbrio

**Pergunta orientadora:** como uma distribuição de matéria pode exercer pressão e empuxo sem ser tratada como um conjunto de partículas isoladas?

**Objetivos:**

- definir densidade e pressão;
- derivar qualitativamente a variação hidrostática;
- aplicar princípio de Pascal e empuxo de Arquimedes;
- distinguir força de pressão e pressão de força;
- determinar condições de flutuação, suspensão e afundamento;
- escolher sistema fluido–corpo quando a contabilidade de forças exigir;
- verificar unidades e ordem de grandeza.

**Representações essenciais:** elemento de fluido, superfície de controle, pressão em faces, diagrama de corpo livre e volume deslocado.

**Erros a vigiar:** dizer que pressão tem direção; usar pressão atmosférica duas vezes; igualar empuxo ao peso fora do equilíbrio; usar densidade do corpo no lugar da densidade do fluido; ignorar profundidade de referência.

**Evidência de saída:** explicar um objeto flutuante por forças e volume deslocado, montar a pressão em diferentes profundidades e analisar uma situação com fluido estratificado ou recipiente acelerado em nível adequado.

### T3 — Fluidos em movimento

**Pergunta orientadora:** como massa e energia atravessam uma região quando o fluido está escoando?

**Objetivos:**

- distinguir vazão, velocidade local e fluxo de massa;
- aplicar continuidade em regime e hipóteses declaradas;
- interpretar Bernoulli como balanço de energia em regime ideal;
- reconhecer pressão, energia cinética e potencial gravitacional por volume;
- tratar viscosidade, turbulência e perdas qualitativamente;
- decidir quando Bernoulli não pode ser usado;
- conectar pressão a velocidade sem transformar a relação em regra universal.

**Erros a vigiar:** assumir mesma velocidade em áreas diferentes; aplicar Bernoulli a escoamento com perdas sem correção; confundir vazão com velocidade; usar continuidade fora de regime adequado; esquecer altura e referência de pressão.

**Evidência de saída:** modelar um escoamento em tubo, justificar hipóteses, prever a variação de pressão e identificar uma situação em que a lei ideal falha.

### T4 — Movimento periódico e oscilador harmônico simples

**Pergunta orientadora:** por que uma força restauradora aproximadamente linear produz uma forma de movimento tão recorrente?

**Objetivos:**

- identificar equilíbrio estável e deslocamento;
- construir o modelo F = −kx e suas limitações;
- relacionar posição, velocidade, aceleração e fase;
- interpretar frequência, período, amplitude e energia;
- usar energia para verificar o modelo;
- comparar mola, pêndulo simples e pêndulo físico;
- distinguir frequência angular de frequência ordinária;
- usar EDO simples quando apropriado sem transformar a equação em resposta automática.

**Representações essenciais:** gráfico x-t, v-t e a-t; espaço de fase introdutório; energia cinética/potencial; diagrama de forças; círculo de fase como representação auxiliar.

**Erros a vigiar:** confundir amplitude com deslocamento instantâneo; dizer que a força é constante; usar período do pêndulo fora da aproximação de pequeno ângulo; perder fase; confundir ω com f; supor que toda oscilação é harmônica.

**Evidência de saída:** construir e verificar um modelo de MHS, prever velocidades em posições extremas e comparar mola e pêndulo por hipóteses e energia.

### T5 — Amortecimento, forçamento e ressonância

**Pergunta orientadora:** como perdas e excitação externa modificam um sistema que, idealmente, oscilaria para sempre?

**Objetivos:**

- distinguir oscilação livre, amortecida e forçada;
- interpretar energia perdida por ciclo;
- comparar subamortecido, criticamente amortecido e superamortecido;
- compreender frequência de força externa e frequência natural;
- interpretar ressonância por amplitude e fase;
- reconhecer dependência da resposta em parâmetros;
- relacionar modelo matemático a dados experimentais.

**Erros a vigiar:** chamar toda grande amplitude de ressonância; confundir frequência natural com frequência aplicada; interpretar amortecimento como mudança automática de equilíbrio; ignorar fase; usar solução ideal para sistema dissipativo.

**Evidência de saída:** interpretar uma curva de resposta, prever efeito de alterar amortecimento e justificar por que uma ponte, edifício ou circuito pode exigir análise de ressonância.

### T6 — Ondas mecânicas e energia

**Pergunta orientadora:** como uma perturbação transporta energia e informação sem transportar a matéria inteira junto?

**Objetivos:**

- distinguir pulso, onda, meio, frente e oscilador local;
- classificar ondas transversais e longitudinais;
- definir amplitude, comprimento de onda, frequência, período e velocidade;
- interpretar uma função de onda e sua dependência em x e t;
- relacionar tensão e densidade à velocidade em corda em regime apropriado;
- analisar potência e energia de onda;
- conectar osciladores locais à propagação.

**Representações essenciais:** instantâneos espaciais, história temporal de um ponto, diagrama de fase, onda em corda, gráfico de energia e função senoidal.

**Erros a vigiar:** confundir velocidade de oscilador com velocidade de propagação; dizer que matéria viaja com a onda; trocar frequência e comprimento de onda; usar sinal de fase sem interpretar; ignorar meio.

**Evidência de saída:** passar entre gráfico espacial, gráfico temporal e equação, prever efeito de mudar frequência ou tensão e verificar dimensões da velocidade.

### T7 — Superposição, ondas estacionárias, som e Doppler

**Pergunta orientadora:** como duas ondas podem se combinar para produzir reforço, cancelamento, modos e mudança de frequência observada?

**Objetivos:**

- aplicar superposição linear em situações adequadas;
- distinguir interferência construtiva e destrutiva;
- construir ondas estacionárias e nós/ventres;
- relacionar condições de contorno a modos permitidos;
- calcular batimentos e interpretar envelope;
- modelar som, intensidade, nível e velocidade;
- explicar efeito Doppler por movimento relativo da fonte e observador;
- reconhecer limites do modelo clássico simplificado.

**Erros a vigiar:** somar amplitudes como energias; contar nós incorretamente; usar comprimento de onda errado em tubo; confundir batimento com Doppler; aplicar fórmula de Doppler sem identificar quem se move.

**Evidência de saída:** desenhar modos, resolver uma situação de superposição, explicar um gráfico de batimentos e prever o sinal do deslocamento Doppler antes da equação.

**Conexão com Astrofísica:** espectroscopia e velocidade radial como aplicação futura do princípio Doppler.

### T8 — Temperatura, teoria cinética e gases

**Pergunta orientadora:** como variáveis macroscópicas emergem do movimento coletivo de muitas partículas?

**Objetivos:**

- diferenciar temperatura, calor e energia interna;
- usar equação de estado de gás ideal com hipóteses;
- interpretar pressão como transferência de momento;
- conectar temperatura à energia cinética média;
- discutir distribuição de velocidades e equipartição em nível adequado;
- analisar escalas absolutas e conversões;
- distinguir modelo microscópico de descrição termodinâmica.

**Representações essenciais:** diagrama de partículas, histograma de velocidades, gráfico P–V, mapa de estado e fluxos de energia.

**Erros a vigiar:** tratar temperatura como energia total; usar Celsius em lei de gás; afirmar que toda partícula tem mesma velocidade; confundir pressão com força total; aplicar gás ideal em regime incompatível sem discutir.

**Evidência de saída:** explicar qualitativamente uma mudança de pressão ou temperatura, resolver um estado de gás e verificar a resposta por limite ou proporção.

### T9 — Calor, trabalho e primeira lei

**Pergunta orientadora:** como acompanhar quantitativamente a transferência e transformação de energia em um processo?

**Objetivos:**

- distinguir funções de estado de grandezas dependentes do processo;
- definir calor, trabalho e energia interna;
- aplicar a primeira lei com convenção de sinais explícita;
- interpretar trabalho como área em diagrama P–V;
- analisar processos isocórico, isobárico, isotérmico e adiabático em nível adequado;
- tratar capacidade térmica, calor específico e mudanças de fase;
- modelar máquinas e transferências térmicas;
- comparar processo reversível e irreversível qualitativamente.

**Erros a vigiar:** dizer que calor está contido no corpo; trocar sinal de trabalho; usar ΔU = Q sem trabalho; confundir temperatura final com energia transferida; contar mudança de fase como simples aquecimento.

**Evidência de saída:** montar balanço energético para processo em P–V, justificar sinais e interpretar energia interna em gás ideal.

### T10 — Segunda lei, Carnot e entropia

**Pergunta orientadora:** por que conservação de energia não determina sozinha quais processos podem acontecer?

**Objetivos:**

- enunciar segunda lei em formas de Kelvin e Clausius;
- distinguir reversibilidade e irreversibilidade;
- analisar máquinas térmicas, refrigeradores e eficiência;
- compreender ciclo de Carnot como limite ideal;
- interpretar entropia como função de estado e direção de processos;
- calcular variações em casos previstos pela disciplina;
- relacionar microestados e desordem com cuidado conceitual;
- verificar se um processo viola eficiência ou direção física.

**Erros a vigiar:** afirmar que entropia sempre é zero em ciclo; tratar eficiência como 100% possível; confundir calor com entropia; usar ΔS do sistema sem considerar ambiente; aplicar igualdade de Carnot a máquina real.

**Evidência de saída:** comparar duas máquinas, justificar impossibilidade de um processo e calcular/interpretar variação de entropia em um caso controlado.

### T11 — Síntese de gravitação, ondas e termodinâmica

A avaliação deve misturar:

- órbita e energia;
- pressão/empuxo ou Bernoulli;
- MHS e energia;
- onda estacionária ou Doppler;
- gás e primeira lei;
- segunda lei e máquina térmica;
- previsão qualitativa, análise de unidade e solução incorreta.

Pelo menos dois problemas devem omitir o método. Um deve conectar Física 2 a fenômeno astronômico, como órbita, espectro Doppler, atmosfera ou equilíbrio térmico, sem transformar a disciplina em Astrofísica.

## Gates de progressão

### Gate T-Gravitação e fluidos

- força, campo e potencial diferenciados;
- órbita analisada por energia e momento angular;
- empuxo e pressão modelados pelo sistema correto;
- continuidade/Bernoulli usados com hipóteses;
- limite ou estimativa verificados.

### Gate T-Oscilações e ondas

- modelo de MHS construído;
- fase, frequência, energia e velocidade interpretadas;
- onda descrita em mais de uma representação;
- superposição e estacionárias explicadas;
- ressonância e Doppler aplicados sem rótulo.

### Gate T-Termodinâmica

- estado e processo distinguidos;
- primeira lei com sinais coerentes;
- gás ideal e teoria cinética interpretados;
- segunda lei aplicada a máquina ou processo;
- entropia interpretada, não apenas calculada.

### Gate T-Transferência

- problema misto sem método indicado;
- hipótese física defendida;
- solução quantitativa e qualitativa coerentes;
- conexão entre microscópico e macroscópico;
- retenção confirmada após revisão espaçada.

## Avaliação recomendada

- diagnóstico de entrada;
- avaliação 1: gravitação e fluidos;
- avaliação 2: osciladores e ondas;
- avaliação 3: temperatura, teoria cinética e primeira lei;
- avaliação 4: segunda lei e entropia;
- final cumulativa com pelo menos 30% de interpretação/modelagem e uma questão de transferência.

Incluir gráficos, diagramas, previsões, análise dimensional e casos em que a lei escolhida não se aplica.

## Ritmo de referência

Em aproximadamente 16–18 semanas:

- 2 semanas: T0–T1;
- 2 semanas: T2–T3;
- 3 semanas: T4–T5;
- 3 semanas: T6–T7;
- 3 semanas: T8–T9;
- 2 semanas: T10;
- 1–3 semanas: revisão, recuperação e síntese.

O tempo não é critério de domínio. Se EDO ou cálculo forem bloqueadores, ativar a recuperação correspondente sem abandonar a previsão qualitativa e a prática independente.

## Instruções específicas ao agente tutor

- Antes de uma equação de Bernoulli, pedir sistema, linha de corrente e perdas consideradas.
- Em órbitas, pedir desenho radial e referência da energia.
- Em MHS, começar por equilíbrio e força restauradora.
- Em ondas, distinguir sempre gráfico espacial de história temporal.
- Em termodinâmica, fixar convenção de sinais antes da primeira lei.
- Pedir previsão de eficiência e direção antes da segunda lei.
- Usar exemplos de Astrofísica como transferência, especialmente órbitas e Doppler.
- Não transformar o programa oficial em uma sequência de exercícios etiquetados por capítulo.

## Critério de conclusão e transição para Física 3

O estudante está pronto para Física 3 quando consegue:

- usar energia e momento angular em gravitação;
- modelar fluidos com hipóteses;
- explicar MHS, ondas e ressonância;
- aplicar primeira e segunda leis com sinais;
- interpretar entropia e eficiência;
- verificar resultado por unidade, limite e ordem de grandeza;
- transferir o raciocínio para um problema misto.

A matemática necessária para integrais, derivadas e EDO deve estar no nível operacional correspondente. Se a falha for matemática, apontar a recuperação sem classificar a termodinâmica como não compreendida.
