# Física 3

## Missão da disciplina

Física 3 constrói uma visão unificada do eletromagnetismo introdutório. O estudante deve passar de interações elétricas e magnéticas descritas como forças para campos, potencial, energia, circuitos, fluxo e leis integrais.

A sequência conceitual principal é:

**carga e força → campo → simetria e fluxo → potencial e energia → materiais e circuitos → campo magnético → indução → unificação de Maxwell e ondas eletromagnéticas.**

**Base institucional:** FISI0262 – Física 3, Departamento de Física da Universidade Federal de Sergipe. O programa oficial cobre carga, lei de Coulomb, campo e fluxo elétrico, lei de Gauss, potencial, capacitores e dielétricos, corrente, resistência, força eletromotriz, circuitos DC e RC, campo magnético, força de Lorentz, Biot–Savart, Ampère, torque magnético, Faraday, Lenz, indutância, circuitos RL e RLC, propriedades magnéticas da matéria e correntes alternadas.

**Base bibliográfica:** Sears, Zemansky, Young e Freedman, Física III, 12ª edição; Halliday, Resnick e Krane, Fundamentos de Física, volume 3; Alonso e Finn, volume 2; Nussenzveig, Tipler–Mosca e Serway–Jewett, conforme o programa oficial. Os materiais enviados estão identificados em [Física/Referencias/catalogo.md](../Referencias/catalogo.md).

### Materiais enviados para Física 3

- `F3-HALLIDAY-V3-2016`: livro-texto de apoio, capítulos 21–32, alinhados a E1–E11.
- `F3-HALLIDAY-MANUAL-SOLUCOES-2016`: manual suplementar do Halliday; usar apenas depois da tentativa independente, para comparar solução, classificar erro e refazer o problema.
- Ao propor exercícios, registrar o ID, capítulo/seção e problema. O manual não substitui a leitura conceitual nem constitui evidência independente de domínio.

## Resultado esperado

Ao concluir Física 3, o estudante deve ser capaz de:

- distinguir força elétrica, campo elétrico, potencial e energia potencial;
- usar superposição e simetria para modelar distribuições de carga;
- decidir quando a lei de Gauss é realmente útil;
- interpretar fluxo e superfícies gaussianas;
- relacionar campo, potencial e energia;
- modelar condutores, capacitores e dielétricos;
- analisar corrente, resistência, força eletromotriz e circuitos;
- escolher entre análise local de circuito e leis de Kirchhoff;
- distinguir campo magnético de força magnética;
- selecionar Biot–Savart ou Ampère conforme a simetria;
- explicar indução, sinal de Lenz, indutância e energia magnética;
- analisar circuitos RC, RL, RLC e AC no nível previsto;
- interpretar propriedades magnéticas da matéria;
- verificar direção, sinal, unidade, simetria, limite e conservação de energia.

## Gate de entrada

Exigir desempenho operacional em:

- vetores, produto escalar, produto vetorial e componentes;
- energia, trabalho e conservação de Física 1;
- derivadas e integrais elementares;
- gráficos e funções;
- noção de fluxo e superfícies quando avançar para Gauss;
- EDOs simples e exponenciais para RC/RL; números complexos/fasores quando AC exigir.

Física 2 não é um pré-requisito conceitual integral para iniciar eletrostática, mas a linguagem de energia, campo e ondas deve ser recuperada quando aparecer. Lacunas matemáticas estruturais devem apontar para Calculo C/D ou Equações Diferenciais.

## Arquitetura do curso

| Unidade | Conteúdo central | Habilidades estáveis | Pré-requisitos principais |
|---|---|---|---|
| E0 | Linguagem de campos, carga e fluxo | F3-campo-representacao; F3-fluxo-superficie | PF1–PF5; vetores |
| E1 | Carga, Coulomb e campo elétrico | F3-campo-eletrico-superposicao | F1-vetores; energia |
| E2 | Fluxo, simetria e lei de Gauss | F3-gauss-escolha-simetria | E1; superfícies |
| E3 | Potencial, energia e equipotenciais | F3-potencial-campo-energia | E1–E2; integrais |
| E4 | Condutores, capacitância e dielétricos | F3-capacitor-dieletrico-energia | E2–E3 |
| E5 | Corrente, resistência e força eletromotriz | F3-corrente-resistencia-modelo | energia; circuitos |
| E6 | Circuitos DC, Kirchhoff, RC | F3-circuitos-kirchhoff; F3-circuito-rc | E5; EDO simples |
| E7 | Campo magnético e força de Lorentz | F3-magnetico-forca-movimento | vetores; carga |
| E8 | Fontes de campo: Biot–Savart e Ampère | F3-biotsavart-ampere-simetria | E7; cálculo vetorial focal |
| E9 | Matéria magnética, fluxo e torque | F3-magnetismo-materia | E7–E8 |
| E10 | Faraday, Lenz e indutância | F3-faraday-sinal-lenz | fluxo; conservação |
| E11 | RL, RLC, AC e unificação | F3-rlc-fasor; F3-maxwell-onda | E10; EDO e complexos |
| E12 | Síntese e transferência | F3-transferencia-eletromagnetica | E0–E11 |

A organização preserva a divisão oficial: indução e circuitos RLC pertencem ao núcleo de Física 3; Física 4 parte da ponte de ondas e entra em óptica, relatividade e fundamentos quânticos.

## Unidades detalhadas

### E0 — Sistemas de campo, representação e fluxo

**Pergunta orientadora:** como descrever uma interação que não deve ser tratada apenas como uma força instantânea entre dois objetos?

**Objetivos:**

- distinguir fonte, campo, carga de prova e força;
- representar campo por vetores, linhas e mapas;
- definir superfície orientada e normal;
- interpretar fluxo como medida de passagem através de uma superfície;
- separar informação local de informação integrada;
- revisar unidades e simetria.

**Representações essenciais:** linhas de campo, vetores em pontos, superfície com normal, distribuição de carga, curva equipotencial e tabela de unidades.

**Erros a vigiar:** desenhar linhas como trajetórias obrigatórias; confundir campo com força; contar linhas como valor absoluto; usar normal sem orientação; tratar fluxo como campo escalar sem superfície.

**Evidência de saída:** interpretar dois campos por representação e prever o sinal do fluxo em uma superfície orientada.

### E1 — Carga, lei de Coulomb e campo elétrico

**Pergunta orientadora:** como uma distribuição de cargas modifica o espaço e como uma carga de prova responde a essa modificação?

**Objetivos:**

- usar conservação e quantização de carga em nível adequado;
- aplicar lei de Coulomb vetorialmente;
- construir campo de cargas pontuais por superposição;
- passar de força sobre carga de prova para campo;
- estimar direção, sinal e ordem de grandeza;
- modelar distribuições contínuas simples quando a integral for necessária;
- comparar campo resultante com força em uma carga específica.

**Erros a vigiar:** somar módulos em vez de vetores; usar sinal da carga de prova para definir o campo; desenhar linhas que se cruzam; tratar campo uniforme como regra universal; esquecer simetria ou domínio.

**Evidência de saída:** construir campo de uma configuração discreta, justificar cancelamento ou reforço por simetria e interpretar a força sobre uma carga de sinal diferente.

### E2 — Fluxo, simetria e lei de Gauss

**Pergunta orientadora:** quando uma informação global sobre o fluxo permite determinar o campo local sem integrar ponto a ponto?

**Objetivos:**

- definir fluxo elétrico com normal e orientação;
- aplicar lei de Gauss;
- reconhecer simetria esférica, cilíndrica e planar;
- escolher superfície gaussiana coerente com a simetria;
- separar carga encerrada de carga externa;
- distinguir cálculo de fluxo de determinação de campo;
- tratar condutores em equilíbrio eletrostático.

**Representações essenciais:** superfícies gaussianas, vetores normais, regiões de campo, carga encerrada e gráficos por distância.

**Erros a vigiar:** aplicar Gauss porque há uma superfície fechada, sem simetria suficiente; confundir carga dentro da superfície com campo apenas local; assumir campo constante em qualquer superfície; esquecer contribuição de carga externa ao campo, embora não ao fluxo líquido.

**Evidência de saída:** para três distribuições, decidir se Gauss determina o campo, escolher a superfície ou justificar por que outro método é necessário.

### E3 — Potencial, energia e superfícies equipotenciais

**Pergunta orientadora:** como substituir uma descrição vetorial de força por uma função escalar de energia sem perder a física?

**Objetivos:**

- definir potencial e energia potencial elétrica;
- relacionar trabalho, campo e diferença de potencial;
- usar superposição para potenciais;
- interpretar equipotenciais e sua ortogonalidade com campo;
- relacionar campo a gradiente de potencial em nível apropriado;
- tratar condutores e referências de potencial;
- analisar movimento de carga por energia.

**Erros a vigiar:** confundir potencial com energia potencial; tratar potencial como vetor; afirmar que campo zero implica potencial zero; esquecer carga ao converter energia; usar sinal de ΔV sem declarar percurso.

**Evidência de saída:** passar entre gráfico de potencial, campo e energia, resolver movimento de carga por energia e comparar com abordagem de força.

### E4 — Condutores, capacitores e dielétricos

**Pergunta orientadora:** como uma geometria e um material armazenam energia elétrica e controlam diferença de potencial?

**Objetivos:**

- explicar campo no interior de condutor em equilíbrio;
- relacionar carga, potencial e capacitância;
- analisar capacitores em série e paralelo por variáveis comuns;
- calcular energia armazenada por diferentes representações;
- interpretar campo entre placas e efeitos de borda;
- distinguir inserção de dielétrico com carga ou tensão mantida;
- conectar visão macroscópica a polarização microscópica.

**Representações essenciais:** placas, linhas de campo, circuito equivalente, tabela de carga/tensão/energia e material polarizado.

**Erros a vigiar:** somar capacitâncias pelo hábito; confundir Q constante com V constante; usar campo uniforme fora da aproximação; contar energia como carga armazenada; ignorar trabalho da fonte.

**Evidência de saída:** analisar uma mudança de configuração, declarar qual variável é mantida, prever a energia e verificar por unidades e balanço com a fonte.

### E5 — Corrente, resistência, resistividade e força eletromotriz

**Pergunta orientadora:** como a energia elétrica é transferida por um circuito e por que carga não é simplesmente consumida?

**Objetivos:**

- definir corrente como taxa de carga;
- distinguir corrente convencional e movimento microscópico;
- relacionar resistência, resistividade, geometria e temperatura em modelos adequados;
- interpretar lei de Ohm como modelo de material, não lei universal;
- distinguir diferença de potencial, força eletromotriz e energia por carga;
- acompanhar potência e transferência de energia;
- modelar resistores em série e paralelo com justificativa.

**Erros a vigiar:** corrente como algo que desaparece; diferença de potencial como força; usar V = IR em dispositivo não ôhmico; somar resistências por posição visual; ignorar resistência interna.

**Evidência de saída:** explicar o fluxo de energia em circuito, calcular uma resistência equivalente e prever efeito de alterar material, comprimento ou área.

### E6 — Circuitos DC, Kirchhoff e RC

**Pergunta orientadora:** como leis locais de conservação organizam um circuito com múltiplos caminhos e evolução temporal?

**Objetivos:**

- aplicar conservação de carga em nós;
- aplicar conservação de energia em malhas;
- escolher nós, malhas e sentidos de corrente;
- resolver circuitos com fontes e resistores;
- interpretar instrumentos de medição;
- construir o modelo de carga e descarga de capacitor;
- reconhecer tempo característico;
- comparar comportamento inicial e final;
- verificar continuidade de tensão ou corrente conforme o componente e modelo.

**Erros a vigiar:** exigir corrente igual em todos os ramos; aplicar segunda lei sem orientação; trocar sinal de fonte; tratar capacitor como resistor permanente; usar regime estacionário em instante inicial; esquecer condição inicial.

**Evidência de saída:** resolver circuito de duas malhas, explicar sinais de uma corrente negativa e modelar uma carga RC por balanço e condição inicial.

### E7 — Campo magnético e força de Lorentz

**Pergunta orientadora:** como uma carga em movimento pode experimentar uma força perpendicular ao seu movimento sem que o campo magnético realize trabalho?

**Objetivos:**

- representar campo magnético e orientação;
- aplicar força de Lorentz;
- usar regra da mão direita com explicação vetorial;
- analisar movimento circular/helicoidal de cargas;
- distinguir força magnética, velocidade e raio;
- calcular força sobre fio com corrente;
- interpretar torque em espira e dipolo magnético;
- discutir efeito Hall como evidência de portadores.

**Erros a vigiar:** força paralela à velocidade; dizer que campo magnético sempre aumenta rapidez; esquecer sinal da carga; confundir direção de corrente com movimento de elétrons; usar força sobre fio sem elemento geométrico.

**Evidência de saída:** prever trajetória de carga, resolver movimento em campo uniforme e explicar por que a energia cinética não muda em um caso puramente magnético.

### E8 — Biot–Savart, Ampère e escolha por simetria

**Pergunta orientadora:** como fontes de corrente produzem campo magnético e quando a simetria torna uma lei integral eficiente?

**Objetivos:**

- relacionar corrente a fonte de campo magnético;
- aplicar Biot–Savart em geometrias simples;
- reconhecer quando Ampère é superior;
- escolher caminho amperiano;
- distinguir campo dentro e fora de condutor idealizado;
- prever direção por elementos de corrente e regra da mão direita;
- verificar dimensões e limites.

**Erros a vigiar:** aplicar Ampère sem simetria; confundir caminho de integração com trajetória de carga; usar Biot–Savart como soma escalar; perder orientação; ignorar regiões distintas do espaço.

**Evidência de saída:** comparar dois métodos para uma geometria, justificar a escolha e explicar por que uma superfície gaussiana não substitui automaticamente um caminho amperiano.

### E9 — Fluxo magnético e propriedades da matéria

**Pergunta orientadora:** como materiais alteram a resposta magnética e como descrever o fluxo através de uma área?

**Objetivos:**

- definir fluxo magnético e orientação;
- distinguir dipolo magnético, magnetização e campo aplicado;
- descrever diamagnetismo, paramagnetismo e ferromagnetismo em nível introdutório;
- aplicar lei de Gauss para magnetismo como restrição de linhas;
- interpretar torque e energia de dipolo;
- usar simetria e limites para verificar resultados.

**Erros a vigiar:** tratar polos magnéticos isolados como cargas elétricas; confundir B e H sem necessidade; esquecer vetor área; inverter torque; declarar material ferromagnético por qualquer resposta magnética.

**Evidência de saída:** prever fluxo e torque, comparar materiais e justificar o significado de fluxo magnético nulo em uma superfície fechada.

### E10 — Faraday, Lenz e indutância

**Pergunta orientadora:** como uma mudança de fluxo produz uma força eletromotriz e por que o sentido induzido se opõe à mudança?

**Objetivos:**

- calcular e interpretar fluxo magnético variável;
- aplicar lei de Faraday com orientação;
- usar lei de Lenz como conservação de energia, não como regra de sinal isolada;
- distinguir movimento de circuito, campo variável e área variável;
- modelar força eletromotriz induzida;
- definir autoindutância e energia magnética;
- comparar transformador ideal e real em nível adequado.

**Erros a vigiar:** escolher sentido pelo desenho sem identificar mudança; dizer que Lenz se opõe ao campo em vez da mudança de fluxo; esquecer número de espiras; confundir fluxo com campo; ignorar energia entregue à corrente induzida.

**Evidência de saída:** prever o sentido da corrente em três mudanças diferentes de fluxo, depois confirmar por equação e interpretar a energia.

### E11 — RL, RLC, corrente alternada e unificação

**Pergunta orientadora:** como resistência, capacitância e indutância determinam transientes e respostas oscilatórias?

**Objetivos:**

- construir equações de RL e interpretar constante de tempo;
- analisar RLC como oscilador elétrico;
- distinguir resposta livre, amortecida e forçada;
- usar fasores quando a representação facilitar a análise de AC;
- interpretar impedância em nível adequado;
- acompanhar potência média e fase;
- reconhecer Maxwell como unificação local das leis de eletricidade e magnetismo;
- compreender a ideia de onda eletromagnética e sua velocidade no vácuo.

**Erros a vigiar:** tratar indutor como fio ideal em qualquer instante; confundir impedância com resistência; perder fase; aplicar regime permanente no transiente; escrever Maxwell como lista sem interpretar fontes, circulação e variação temporal.

**Evidência de saída:** comparar circuito RC/RL/RLC, selecionar representação temporal ou fasorial e explicar como uma variação de campo produz outro campo.

### E12 — Síntese eletromagnética

A avaliação deve misturar:

- campo de distribuição de carga;
- escolha de superfície gaussiana;
- potencial e energia;
- capacitor/dielétrico;
- circuito de malhas ou RC;
- força magnética e trajetória;
- escolha entre Biot–Savart e Ampère;
- Faraday/Lenz;
- AC ou visão de Maxwell;
- análise de sinais, orientação, unidade e solução incorreta.

Pelo menos dois problemas devem exigir escolha sem rótulo e um deve conectar campo/potencial/circuito a fenômeno experimental ou astronômico.

## Gates de progressão

### Gate E-Campo elétrico

- soma vetorial e representação de campo;
- fluxo com orientação;
- simetria identificada;
- Gauss aplicado somente quando útil;
- potencial e energia distinguidos.

### Gate E-Circuitos

- corrente, tensão, resistência e potência diferenciadas;
- Kirchhoff com sentidos declarados;
- capacitores e condições iniciais;
- RC interpretado temporalmente;
- conservação de energia verificada.

### Gate E-Campo magnético

- força de Lorentz e regra da mão direita;
- trajetória e trabalho magnético;
- Biot–Savart/Ampère escolhidos por simetria;
- torque e fluxo magnético interpretados;
- propriedades da matéria não confundidas com cargas elétricas.

### Gate E-Indução e unificação

- sentido de Lenz previsto antes do cálculo;
- indutância e energia;
- RL/RLC ou AC em nível operacional;
- Maxwell interpretado estruturalmente;
- transferência para problema misto.

Cada gate exige pelo menos 85% em itens essenciais, nenhum erro conceitual crítico, representação adequada, dois problemas rotineiros e um de transferência sem pista forte. O estado operacional depende da revisão tardia.

## Avaliação recomendada

- diagnóstico de vetores, energia e matemática;
- avaliação 1: eletrostática, Gauss e potencial;
- avaliação 2: capacitores, corrente e Kirchhoff;
- avaliação 3: magnetismo, Biot–Savart e Ampère;
- avaliação 4: indução, RL/RLC e AC;
- final cumulativa com seleção de método e interpretação experimental.

Avaliar separadamente modelo, direção/sinal, matemática, unidade, interpretação e validade da lei escolhida.

## Ritmo de referência

Em aproximadamente 16–18 semanas:

- 2 semanas: E0–E1;
- 2 semanas: E2–E3;
- 2 semanas: E4;
- 3 semanas: E5–E6;
- 3 semanas: E7–E8;
- 2 semanas: E9–E10;
- 2 semanas: E11;
- 2 semanas: revisão, recuperação e síntese.

Se cálculo vetorial for bloqueador, ativar a recuperação correspondente e começar com simetria, gráficos e modelos discretos. Não substituir entendimento de campo por memorização de integrais.

## Instruções específicas ao agente tutor

- Perguntar “qual é a fonte do campo?” antes da integral.
- Em Gauss, pedir primeiro a simetria e a superfície; só então escrever o fluxo.
- Em potencial, exigir a distinção entre V e U.
- Em circuitos, acompanhar energia e carga, não apenas setas de corrente.
- Em magnetismo, usar desenho e regra vetorial antes da regra da mão direita.
- Em indução, pedir previsão da mudança de fluxo e do sentido antes da fórmula.
- Usar orientações explícitas em superfícies e circuitos.
- Comparar métodos diretos e leis integrais.
- Não introduzir Maxwell como quatro fórmulas descontextualizadas.
- Conectar radiação, espectro e campo a Astrofísica somente como transferência.

## Critério de conclusão e transição para Física 4

O estudante está pronto para Física 4 quando consegue:

- passar entre carga, campo, potencial e energia;
- usar Gauss por simetria;
- resolver circuitos DC e transientes básicos;
- interpretar força magnética, fluxo e campo de correntes;
- aplicar Faraday e Lenz com orientação;
- analisar RLC/AC ou justificar recuperação matemática;
- explicar a arquitetura de Maxwell e ondas EM;
- verificar unidade, sinal e conservação.

Se a técnica de cálculo estiver correta mas a direção e o modelo forem frágeis, manter problemas qualitativos e de representação. Se a lacuna de EDO ou complexos for estrutural, ativar a recuperação correspondente antes de avançar em RLC.
