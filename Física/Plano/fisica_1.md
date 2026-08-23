# Física 1

## Missão da disciplina

Física 1 constrói a linguagem quantitativa da Mecânica Clássica. O estudante deve aprender a descrever movimento, explicar mudanças de movimento por interações, escolher entre dinâmica e princípios de conservação e analisar sistemas de partículas e corpos rígidos.

A meta não é resolver listas por reconhecimento de fórmula. Ao final, o estudante deve conseguir olhar para uma situação mecânica nova, definir o sistema, representar as interações, antecipar o comportamento e justificar uma estratégia de solução.

**Base institucional:** FISI0260 – Física 1, Departamento de Física da Universidade Federal de Sergipe. O programa oficial cobre cinemática, movimento em duas e três dimensões, dinâmica de partícula, movimento circular, trabalho e energia, momento linear, sistemas de partículas, corpo rígido, torque, momento de inércia, momento angular, trabalho e potência, equilíbrio e elasticidade.

**Base bibliográfica:** os programas oficiais indicam Sears, Zemansky, Young e Freedman, Física I, 12ª edição; Halliday, Resnick e Krane, Fundamentos de Física, volume 1; Alonso e Finn, Física: um curso universitário, volume 1; e, como complementares, Nussenzveig, Kittel e Tipler–Mosca. As referências são registradas sem inventar correspondência de capítulos entre edições.

## Resultado esperado

Ao concluir Física 1, o estudante deve ser capaz de:

- usar unidades, dimensões, vetores e gráficos para descrever movimento;
- distinguir posição, deslocamento, distância, velocidade, rapidez e aceleração;
- escolher referenciais e decompor movimentos em eixos convenientes;
- construir diagramas de corpo livre e identificar interações;
- aplicar as leis de Newton com sistema e hipóteses explícitos;
- decidir quando dinâmica, energia, momento linear ou momento angular é a estratégia mais eficiente;
- modelar atrito, tensão, normal, mola, gravidade e resistência de forma compatível com o problema;
- interpretar trabalho, energia, potência, impulso, colisão, torque e equilíbrio;
- analisar centro de massa e corpo rígido em rotação;
- verificar unidade, sinal, direção, ordem de grandeza, limite e conservação;
- transferir o raciocínio para situações não rotuladas.

## Gate de entrada

Aplicar o diagnóstico de Fundamentos de Física. Antes de M1, exigir desempenho operacional em:

- conversões e dimensões;
- componentes e soma vetorial;
- leitura de gráficos;
- álgebra e trigonometria necessárias;
- interpretação de inclinação e área em gráficos simples.

Lacunas de derivada ou integral podem ser recuperadas em paralelo enquanto a cinemática é construída, mas devem ser ativadas antes de trabalho variável, centro de massa contínuo e algumas análises de movimento geral. A unidade de Calculo correspondente deve ser apontada no Estado, não copiada para este arquivo.

## Arquitetura do curso

| Unidade | Conteúdo central | Habilidades estáveis | Pré-requisitos principais |
|---|---|---|---|
| M0 | Medição, vetores, modelos e movimento | F1-modelo-sistema; F1-vetores-eixos | PF1, PF2, PF4 |
| M1 | Posição, velocidade e aceleração | F1-cinematica-vetor-posicao | M0; funções e gráficos |
| M2 | Movimento em duas e três dimensões | F1-cinematica-referencial; F1-projetil; F1-circular | M1; trigonometria |
| M3 | Interações e leis de Newton | F1-dinamica-diagrama-forcas | M1; M0 |
| M4 | Forças comuns e dinâmica circular | F1-atrito-modelo; F1-circular-forca | M3 |
| M5 | Trabalho, energia e potência | F1-energia-escolha-sistema | M3; integrais em aplicações variáveis |
| M6 | Momento linear, impulso e colisões | F1-momento-impulso-colisao | M3; M5 |
| M7 | Sistemas de partículas e rotação | F1-centro-massa; F1-rotacao-torque-momento-inercia | M5, M6; integrais quando necessário |
| M8 | Equilíbrio, elasticidade e síntese | F1-equilibrio-estatico; F1-elasticidade | M7; M3 |
| M9 | Avaliação cumulativa e ponte para Física 2 | F1-transferencia-mecanica | M0–M8 |

A distribuição segue o programa oficial de Física 1. Gravitação e órbitas aparecem como núcleo de Física 2 na ementa institucional, portanto não serão deslocadas para M8 apenas por uma divisão tradicional de livros.

## Unidades detalhadas

### M0 — Medição, vetores e modelagem mecânica

**Pergunta orientadora:** como transformar uma situação real em um modelo que preserve o que importa sem fingir que todas as complexidades desapareceram?

**Objetivos:**

- separar grandeza, valor, unidade, incerteza e significado;
- construir sistema, fronteira e ambiente;
- escolher eixos e origem;
- representar vetores por setas, componentes e módulo/direção;
- distinguir dado, incógnita, hipótese e resultado;
- estimar antes de calcular.

**Representações essenciais:** desenho da situação, eixos, vetor deslocamento, tabela de grandezas, gráfico simples e diagrama sistema–ambiente.

**Erros a vigiar:** usar número sem unidade; escolher eixos que escondem simetria; confundir objeto com sistema; aceitar idealização sem declarar; tratar vetor como lista de números sem orientação.

**Evidência de saída:** analisar uma situação mecânica curta, propor duas fronteiras possíveis, escolher uma, desenhar eixos e justificar quais efeitos serão desprezados.

### M1 — Posição, deslocamento, velocidade e aceleração

**Pergunta orientadora:** como descrever mudança de movimento sem ainda explicar sua causa?

**Objetivos:**

- distinguir posição, trajetória, distância e deslocamento;
- construir posição como função do tempo;
- interpretar velocidade média e instantânea como taxa de variação;
- interpretar aceleração como variação da velocidade;
- passar entre descrição verbal, tabela, gráfico e equação;
- relacionar inclinação e área nos gráficos posição-tempo, velocidade-tempo e aceleração-tempo;
- usar condições iniciais sem confundir estado com taxa.

**Conceitos centrais:** velocidade pode ser negativa sem que rapidez seja negativa; aceleração não é sinônimo de aumento de rapidez; movimento exige referência; uma mesma aceleração pode acompanhar aumento ou diminuição da rapidez dependendo da direção da velocidade.

**Erros a vigiar:** confundir distância com deslocamento; ler área no gráfico errado; dizer que aceleração zero implica repouso; usar fórmula de aceleração constante sem verificar hipótese; confundir posição com caminho percorrido.

**Evidência de saída:** reconstruir qualitativamente v e a a partir de um gráfico de posição, resolver um caso de aceleração constante e explicar o significado físico das unidades e dos sinais.

### M2 — Movimento em duas e três dimensões, referenciais e movimento circular

**Pergunta orientadora:** como separar componentes de um movimento sem criar movimentos físicos independentes que não existem?

**Objetivos:**

- decompor posição, velocidade e aceleração;
- tratar lançamento de projéteis com hipóteses explícitas;
- distinguir movimento relativo e mudança de referencial;
- representar trajetória, vetor velocidade e vetor aceleração;
- descrever movimento circular por velocidade tangente e aceleração centrípeta;
- separar aceleração que muda direção da que muda rapidez;
- usar simetria e eixos para simplificar.

**Representações essenciais:** vetor posição, componentes, trajetória, diagrama de velocidades, círculo com normal radial e gráfico de componentes no tempo.

**Erros a vigiar:** tratar gravidade como horizontal e vertical sem declarar eixos; confundir velocidade nula com aceleração nula no ponto mais alto; chamar força centrípeta de força nova; usar velocidade angular como velocidade linear; esquecer referencial.

**Evidência de saída:** resolver um lançamento ou movimento relativo sem método indicado, prever a direção da aceleração e comparar duas descrições em referenciais distintos.

### M3 — Interação, sistema e leis de Newton

**Pergunta orientadora:** como uma interação modifica o movimento de um sistema?

**Objetivos:**

- distinguir cinemática de dinâmica;
- identificar pares de interação sem misturar as forças em um mesmo diagrama;
- construir diagramas de corpo livre;
- aplicar a primeira, segunda e terceira leis com linguagem precisa;
- escolher sistema de partícula ou conjunto;
- modelar vínculos e tensões;
- reconhecer quando uma força resultante é zero sem concluir que não há forças.

**Protocolo de diagrama:** isolar o corpo, desenhar somente forças externas que atuam nele, nomear origem física, escolher eixos, declarar contato e vínculo e só então escrever a soma vetorial.

**Erros a vigiar:** ação e reação no mesmo corpo; força normal sempre igual ao peso; movimento exige força resultante; força resultante como força extra; incluir força que o corpo exerce em outro; ignorar a geometria do contato.

**Evidência de saída:** construir diagramas para três situações diferentes, resolver uma sem fórmula indicada e justificar por que uma força pertence ou não ao sistema escolhido.

### M4 — Forças comuns e dinâmica circular

**Pergunta orientadora:** como uma interação específica deve ser modelada sem confundir sua direção ou lei constitutiva?

**Objetivos:**

- distinguir peso e massa;
- modelar normal, tensão, atrito estático e cinético, mola e arrasto em regimes adequados;
- reconhecer que atrito estático se ajusta até um limite;
- relacionar força radial ao movimento circular;
- analisar curvas, pêndulos mecânicos e sistemas conectados;
- identificar hipóteses de resistência desprezível, fio ideal, polia ideal ou mola linear.

**Erros a vigiar:** definir atrito sempre como máximo; usar normal igual ao peso em plano inclinado; inserir força centrípeta além das forças reais; tratar arrasto como constante em qualquer regime; ignorar o sistema inteiro em cordas e polias.

**Evidência de saída:** resolver dois problemas de forças comuns de estruturas diferentes, prever efeito de variar um parâmetro e comparar uma solução Newtoniana com uma solução energética quando possível.

### M5 — Trabalho, energia cinética, potencial e potência

**Pergunta orientadora:** quando é mais eficiente acompanhar a transferência de energia do que a força em cada instante?

**Objetivos:**

- interpretar trabalho como transferência associada a força e deslocamento;
- distinguir trabalho de uma força de energia do sistema;
- usar teorema trabalho–energia;
- classificar forças conservativas e não conservativas;
- escolher sistema para energia potencial;
- aplicar conservação da energia com perdas, calor e trabalho externo;
- interpretar potência média e instantânea;
- montar integrais para força variável quando necessário.

**Representações essenciais:** diagrama sistema–ambiente, gráfico força-deslocamento, tabela de energias e fluxo de energia.

**Erros a vigiar:** dizer que força perpendicular nunca importa sem especificar trabalho; confundir energia potencial com força; conservar energia mecânica com atrito sem contabilizar transferência; contar a mesma energia duas vezes; usar mgh fora da hipótese gravitacional local sem avaliar escala.

**Evidência de saída:** resolver um problema em que energia é superior a Newton, um em que Newton é mais transparente e um em que as duas estratégias são comparadas; interpretar unidade e sinal do trabalho.

### M6 — Momento linear, impulso e colisões

**Pergunta orientadora:** que grandeza permanece útil quando a interação é intensa, curta e difícil de acompanhar no tempo?

**Objetivos:**

- definir momento linear e impulso;
- interpretar área sob gráfico força-tempo;
- distinguir conservação do momento do sistema de conservação de energia mecânica;
- identificar sistema isolado e forças externas;
- analisar colisões elásticas, inelásticas e explosões;
- usar centro de massa qualitativamente;
- resolver problemas em uma e duas dimensões.

**Erros a vigiar:** conservar momento de um único corpo com força externa relevante; assumir que toda colisão conserva energia cinética; confundir impulso com força; esquecer que momento é vetor; misturar velocidades relativas sem referencial.

**Evidência de saída:** escolher sistema, justificar isolamento, resolver colisão sem rótulo e analisar uma solução que conserva a grandeza errada.

### M7 — Sistemas de partículas, rotação e momento angular

**Pergunta orientadora:** como estender as ideias de força, energia e momento a um corpo que não pode ser tratado como ponto?

**Objetivos:**

- localizar e interpretar centro de massa;
- relacionar força externa à aceleração do centro de massa;
- descrever posição, velocidade e aceleração angulares;
- distinguir torque, braço de alavanca e força;
- calcular momento de inércia por soma, integral ou teorema apropriado;
- aplicar energia de rotação;
- analisar rolamento sem escorregamento;
- definir momento angular e reconhecer conservação;
- comparar eixo fixo, corpo rígido e partícula.

**Representações essenciais:** eixo de rotação, braço perpendicular, diagrama de torques, distribuição de massa, energia translacional e rotacional.

**Erros a vigiar:** usar torque da força errada; confundir raio com braço perpendicular; assumir mesmo momento de inércia em eixos diferentes; conservar momento angular sem declarar torque externo; impor v = ωR em rolamento com escorregamento.

**Evidência de saída:** analisar um corpo em rotação, escolher entre dinâmica de torque e energia, calcular um momento de inércia simples e interpretar a condição de rolamento.

### M8 — Equilíbrio, elasticidade e síntese mecânica

**Pergunta orientadora:** como um sistema pode permanecer em repouso ou em movimento rígido sem que as forças e torques desapareçam?

**Objetivos:**

- distinguir equilíbrio translacional e rotacional;
- escolher ponto de referência para torques;
- tratar centro de gravidade;
- resolver vigas, apoios e estruturas simples;
- interpretar tensão, deformação e módulos elásticos em regime linear;
- reconhecer limites do modelo elástico;
- combinar força, torque, energia e condições de vínculo.

**Erros a vigiar:** usar somente soma de forças; escolher torque em torno de ponto inadequado; esquecer reação de apoio; tratar tensão como força; extrapolar lei de Hooke além do regime.

**Evidência de saída:** resolver uma estrutura em equilíbrio com mais de uma reação, explicar a escolha do ponto de torque e analisar a plausibilidade de uma deformação.

### M9 — Síntese e ponte para Física 2

A avaliação cumulativa deve combinar:

- gráfico e vetor de cinemática;
- diagrama de corpo livre;
- escolha entre Newton e energia;
- colisão ou sistema de partículas;
- torque/rotação ou equilíbrio;
- problema de transferência com método não indicado;
- análise de solução incorreta;
- verificação dimensional, de sinal e de conservação.

Gravitação e órbitas serão iniciadas em Física 2, mas o estudante deve sair capaz de interpretar campo, energia e momento como linguagens que voltarão nesses contextos.

## Gates de progressão

### Gate M-Cinemática

- leitura de gráficos de posição, velocidade e aceleração;
- componentes e referenciais;
- movimento em duas dimensões;
- previsão de direção e sinal;
- validação por unidades e casos limites.

### Gate M-Dinâmica

- diagrama de corpo livre completo;
- sistema e forças externas explicitados;
- aplicação de Newton sem método indicado;
- distinção entre força resultante e forças individuais;
- transferência para situação nova.

### Gate M-Energia e momento

- escolha justificada entre Newton, energia e momento;
- sistemas isolados declarados;
- interpretação de trabalho, energia e impulso;
- colisão ou explosão com conservação adequada;
- análise de uma solução errada.

### Gate M-Rotação e equilíbrio

- torque com braço correto;
- momento de inércia e energia rotacional;
- momento angular e orientação;
- equilíbrio translacional e rotacional;
- problemas mistos com verificação.

Cada gate exige conjunto misto, pelo menos 85% em itens essenciais, nenhum erro conceitual crítico, dois problemas rotineiros e um de transferência sem pistas fortes. A conclusão provisória deve ser confirmada após revisão de 48 horas e consolidada em conjunto misto posterior.

## Avaliação recomendada

- diagnóstico PF1–PF6;
- verificação 1: M0–M2;
- avaliação intermediária: dinâmica e forças;
- avaliação de energia e momento;
- avaliação de rotação, equilíbrio e elasticidade;
- final cumulativa com pelo menos 30% de representação, escolha e interpretação.

Corrigir separadamente modelagem, princípio, matemática, unidade e interpretação. Toda recuperação deve incluir um problema novo, não somente a repetição da questão errada.

## Ritmo de referência

Em aproximadamente 16 semanas:

- 1 semana: M0 e diagnóstico focal;
- 3 semanas: M1–M2;
- 3 semanas: M3–M4;
- 3 semanas: M5;
- 2 semanas: M6;
- 3 semanas: M7–M8;
- 1 semana: M9, revisão e avaliação.

O tempo é referência. Se a definição de sistema ou diagramas estiver frágil, reduzir exercícios repetitivos e preservar prática independente e revisão.

## Instruções específicas ao agente tutor

- Perguntar “qual é o sistema?” antes de “qual fórmula usar?”.
- Pedir previsão qualitativa antes de qualquer conta importante.
- Exigir diagrama de corpo livre antes de Newton, quando o problema envolver forças.
- Em conservação, perguntar o que entra e sai do sistema.
- Trabalhar simbolicamente antes de números quando isso revelar dependências.
- Comparar Newton, energia e momento em problemas que admitem mais de uma estratégia.
- Usar unidades e limites como ferramentas de raciocínio.
- Não aceitar apenas “a resposta é” sem interpretação física.
- Conectar gravitação futura à linguagem de energia, momento angular e referenciais.

## Critério de conclusão e transição para Física 2

O estudante está pronto para Física 2 quando, em ocasiões diferentes:

- interpreta gráficos e movimentos em duas dimensões;
- constrói diagramas de corpo livre sem omissões sistemáticas;
- escolhe entre Newton, energia e momento;
- resolve uma situação de rotação ou equilíbrio;
- explica hipóteses e verifica resultado;
- transfere o raciocínio para problema sem rótulo.

Se a matemática de integrais for a única lacuna, ativar Calculo B sem rebaixar o domínio mecânico. Se a noção de sistema ou conservação estiver no nível 0–1, manter recuperação antes de avançar para gravitação e termodinâmica.
