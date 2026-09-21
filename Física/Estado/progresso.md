# Física — Progresso atual

## Estado atual

A sessão de 2026-09-20 continuou a lista `ListaExercicio01-fis2.pdf` em ordem, depois da base construída em 2026-09-19. Em T0, houve resposta adequada sobre pressão hidrostática, unificação das leis terrestres e celestes e escolha da referência do potencial; atmosfera e uso do mercúrio exigiram correções e explicação. Em T1, a questão 2(a) foi resolvida corretamente, com dificuldade operacional em conversões, potências e raízes; a questão 2(c) teve montagem correta e interpretação correta do sinal, mas precisa ser corrigida numericamente usando `r_f=2,28×10^11 m` e explicitando `m_g=m_i`.

A sessão de 2026-09-21 fez uma triagem de T1 e iniciou T2. Em T1, houve resposta conceitual adequada sobre a variação de `U`, `K` e da energia mecânica quando a sonda se afasta, com correção da condição especial em que `K` tende a zero no escape mínimo. As leis de Kepler e os campos de uma casca esférica e de uma esfera maciça foram revisados, mas sem nova resolução independente. Em T2, densidade, pressão escalar, pressão hidrostática, experiência de Torricelli e elasticidade foram revisadas; as respostas conceituais foram em geral adequadas. No bloco submerso preso ao fundo, a equação `F_E-T-mg=0` foi montada corretamente, mas a aplicação numérica ainda não foi feita.

T1 ainda não deve ser considerado dominado. A questão 2(b) foi estudada anteriormente, mas não foi refeita; 2(d) e 2(e) continuam pendentes; o exercício independente de periélio/afélio e problemas de energia orbital também continuam pendentes. T2 foi iniciado conceitualmente, mas ainda não há evidência independente de aplicação matemática em empuxo, prensa hidráulica ou camadas fluidas.

Os registros permanentes anteriores tratam também de Física 3; eles permanecem separados e válidos.

## Último tópico trabalhado — sessão de 2026-09-21

- triagem de T1: conservação de energia em afastamento gravitacional, com `U` aumentando, ficando menos negativa, `K` diminuindo e `K+U` constante;
- revisão das leis de Kepler, distinguindo semieixo maior `a` de distância instantânea `r`;
- revisão do campo gravitacional de uma casca esférica e de uma esfera maciça uniforme, incluindo densidade superficial e volumétrica;
- início de T2 a partir da aula externa `Fisica02_Aula09_2026B.pdf`, sem `material_id` no catálogo: densidade, massa específica, densidade relativa, pressão, pressão hidrostática, Torricelli, elasticidade e módulos de Young, cisalhamento e compressibilidade;
- respostas conceituais sobre T2: pressão como escalar, força de pressão perpendicular, aumento da pressão com a profundidade e comportamento qualitativo da pressão em camadas terrestres;
- montagem do equilíbrio de um bloco totalmente submerso preso ao fundo: `F_E-T-mg=0`; a tensão foi identificada como descendente, mas o exercício numérico ficou pendente.

## Último tópico trabalhado — sessão de 2026-09-20

- questão 1(a): pressão hidrostática em atmosfera e oceano; densidade aproximadamente constante da água e compressibilidade do ar;
- questão 1(b): unificação newtoniana de fenômenos terrestres e celestes; fases de Vênus e movimento retrógrado como fenômenos geométricos/dinâmicos distintos;
- questão 1(c): arbitrariedade do zero do potencial e invariância da diferença de potencial;
- questão 1(d): retenção atmosférica por gravidade, temperatura, composição e processos de perda; campo magnético como fator auxiliar, não condição única;
- questão 1(e): uso do mercúrio para formar amálgama com ouro, com risco de toxicidade;
- questão 2(a): `a≈1,965×10^11 m` e `M_☉≈2×10^30 kg`, usando a terceira lei de Kepler e a hipótese de massa do asteroide desprezível;
- questão 2(c): `U=-GMm/r`, deslocamento para `1,52 UA`, sinal positivo de `ΔU` e equivalência `m_g=m_i`; o valor precisa ser recalculado com o raio final sem arredondamento excessivo.

## Último tópico trabalhado — sessão de 2026-09-19

- sistema, ambiente e fronteira na análise de um problema gravitacional;
- campo gravitacional e força gravitacional, com `g=GM/r²` e `F=mg`;
- energia potencial gravitacional `U=-GMm/r`, referência do zero de energia e conservação de `K+U`;
- órbita circular, `v_c=sqrt(GM/r)` e derivação de `T²=4π²r³/(GM)`;
- velocidade de escape `v_e=sqrt(2GM/r)` e relação `v_e=sqrt(2)v_c`;
- distinção entre o raio do corpo central e a distância inicial do objeto ao centro;
- momento angular `L=r×p`, torque gravitacional nulo e conservação de `L` em força central;
- derivação de `dA/dt=L/(2m)` e interpretação da segunda lei de Kepler;
- exercício autoral com planeta de `M=4,8×10²⁴ kg`, `R=6,0×10⁶ m`, altitude `h=2,0×10⁶ m` e sonda de `250 kg`: partes (a)–(d) corretas; a parte (e) foi concluída apenas com explicação posterior.

## Próximo tópico

Concluir a aplicação numérica do bloco submerso, começando por `F_E=\rho_f gV` e depois encontrando `T`; em seguida resolver a questão 3, que inicia T2 com prensa hidráulica, empuxo, transbordamento, densidade e massa de água/areia. Depois retomar o exercício independente de periélio/afélio e as questões 2(c), 2(d) e 2(e) da lista.

## Revisões necessárias para Física 2

- manter a distinção entre massa central `M`, massa de prova `m`, raio do corpo `R` e distância de lançamento `r₀`;
- interpretar corretamente o sinal de `U`: ao aumentar `r`, a energia potencial fica menos negativa;
- distinguir velocidade orbital circular de velocidade em órbita elíptica;
- conferir raízes, potências de dez e unidades em cálculos gravitacionais;
- preservar algarismos significativos em diferenças de energias próximas; em 2(c), usar `1,52 UA=2,28×10^11 m` em vez de `2,2×10^11 m`;
- distinguir semieixo maior `a` de raio instantâneo `r`, e massa gravitacional `m_g` de massa inercial `m_i`, declarando `m_g=m_i` como hipótese newtoniana;
- explicar conservação de energia incluindo a energia potencial da interação, em vez de afirmar que a energia do objeto isolado se conserva sob força externa;
- relacionar conservação de momento angular, velocidade tangencial e áreas varridas;
- ainda verificar de forma independente o cálculo de `K_min` quando a massa da sonda muda.
- traduzir um diagrama de forças de T2 em equação de equilíbrio, distinguindo empuxo como resultante das forças de pressão, peso `mg` e tensão;
- manter a distinção entre pressão contínua e mudança de inclinação em interfaces de camadas fluidas;
- conferir a notação de pressão `P`, peso `mg` e empuxo `F_E`, além de unidades em aplicações de densidade e pressão.

## Pendências atuais de Física 2

- reformular independentemente os pontos corrigidos da questão 1(d) e a explicação da amálgama de mercúrio da 1(e), se forem usados como evidência de domínio;
- concluir numericamente a questão 2(c) com `r_f=2,28×10^11 m`;
- resolver 2(d) e 2(e) da lista; 2(b) foi estudada anteriormente e aguarda apenas conferência/registro nesta sequência;
- resolver o exercício de periélio/afélio usando `r_pv_p=r_av_a`;
- resolver problemas de energia orbital e comparação de massas sem método indicado;
- desenvolver T2 pela questão 3: pressão, densidade, prensa hidráulica, empuxo, transbordamento e camadas esféricas;
- concluir o exercício autoral de empuxo do bloco submerso: `V=2,0×10^{-3} m³`, `m=1,0 kg`, água com `\rho=1000 kg/m³` e `g=10 m/s²`, determinando `F_E` e `T`;
- estudar a aplicação seletiva de T8 sobre temperatura, movimento molecular e retenção atmosférica;
- revisar elasticidade e cisalhamento de Física 1 para a questão 4(e) da lista.

## Estado anterior documentado — Física 3

Física 3 foi iniciada pela unidade E0 e avançou na prática de E1. As sessões recentes abordaram cargas contínuas, fluxo elétrico e Lei de Gauss, mas a base conceitual e operacional ainda precisa ser recuperada antes de avançar de forma independente pelos exercícios dos capítulos 21–24.

Há evidência de compreensão inicial de vetores radiais, sentido do campo de uma carga positiva, força sobre uma carga de prova negativa e cancelamento por simetria. No exercício 26 do Capítulo 22, o estudante identificou corretamente que as componentes horizontais se anulam e que deve ser integrada a componente vertical. Ainda travou na passagem do arco inteiro para o elemento infinitesimal e na integral. O exercício 21 do Capítulo 21 foi acompanhado com derivação guiada, sem evidência de resolução independente. E0/E1, cargas contínuas, fluxo e Lei de Gauss não devem ser considerados dominados.

## Último tópico trabalhado — Física 3 (sessões anteriores)

- vetor radial e vetor radial unitário;
- vetor radial como deslocamento da carga-fonte até o ponto de observação;
- cálculo de `r = |r⃗|` e `r̂ = r⃗/r`;
- exemplo `P = (3,4)`, com `r̂ = (3/5)î + (4/5)ĵ`;
- passagem da forma escalar para a forma vetorial da lei de Coulomb;
- sequência conceitual `q → E → F`.
- densidades linear, superficial e volumétrica: `dq=λ dl`, `dq=σ dA` e `dq=ρ dτ`;
- construção geométrica de elementos diferenciais: anel `dA=2πs ds` e casca esférica `dτ=4πr² dr`;
- ideia de substituir uma distribuição por elementos simples e somar por integral, incluindo anel → disco;
- aplicação conceitual inicial da superposição no exercício 20 do Cap. 21: forças devidas a B e C, distâncias `AB=d` e `AC=2d`, e cancelamento na curva 1 para `θ=0`;
- dois exercícios em coordenadas: `q = +3 nC`, com `r⃗ = 4î + 3ĵ`, e `q = +4 nC`, com `r⃗ = -3î + 4ĵ`;
- interpretação do sinal das componentes e da força sobre `q₀ < 0`.
- definição de fluxo elétrico, vetor área, normal à superfície e orientação de uma superfície fechada;
- forma integral e interpretação conceitual da Lei de Gauss, incluindo carga encerrada, simetria e distinção entre campo local e fluxo líquido;
- `F3-HALLIDAY-V3-2016` → Capítulo 21, seção **A Lei de Coulomb** → exercício **21**, com `ρ=b/r`: montagem guiada de `dq=ρ\,dτ`, `dτ=4πr²dr` e integração entre os raios da casca;
- `F3-HALLIDAY-V3-2016` → Capítulo 22, seção **Campos elétricos** → exercício **26**: simetria da semicircunferência, densidade linear e componente vertical; a montagem foi iniciada, mas a integral não foi concluída pelo estudante.

## Próximo tópico anterior — Física 3

Retomar a base conceitual de eletrostática: fonte, campo, força, vetor radial, densidade de carga, elemento diferencial, simetria e componentes. Depois refazer uma distribuição contínua simples e concluir o exercício 26 do Capítulo 22 com orientação reduzida. Em seguida, revisar fluxo e Lei de Gauss com exemplos simples antes de retomar os exercícios 20 e 21 do Capítulo 21. A superposição em coordenadas de duas e três cargas pontuais continua como recuperação necessária.

## Revisões necessárias — Física 3

- distinguir campo elétrico de força elétrica e lembrar que `F⃗ = q₀E⃗`;
- construir `r⃗ = posição do ponto − posição da carga-fonte`;
- normalizar corretamente o vetor radial e interpretar seus sinais nas componentes;
- conferir a subtração, `r²`, sinais e presença das componentes na resposta final;
- escolher o elemento diferencial adequado à geometria, determinar seus limites e escrever `dq` antes de integrar;
- distinguir o comprimento total de uma parte da distribuição do elemento infinitesimal `dl`, `dA` ou `dτ`;
- relacionar o ângulo geométrico à componente correta do campo e justificar o intervalo de integração;
- consolidar fluxo elétrico, vetor normal, superfície fechada, carga encerrada e escolha de superfície gaussiana;
- separar a validade geral da Lei de Gauss de sua utilidade para determinar o campo, que depende de simetria;
- distinguir sinais das cargas de direções dos vetores de força no Ex. 20, especialmente quando as forças se somam ou se cancelam;
- traduzir a distância `AC=2d` em uma força quatro vezes menor para cargas de mesmo módulo, antes de comparar as curvas;
- ler valores nos extremos de um gráfico de força e relacioná-los à soma ou diferença de módulos;
- não inferir que existe campo não nulo em todo ponto sem carga local: cargas distantes podem produzir campo, mas também pode haver cancelamento e `E⃗ = 0`;
- separar força resultante nula de estabilidade: o ponto médio do exemplo simétrico é um equilíbrio instável para uma carga deslocável ao longo da linha das fontes.

## Orientação pedagógica

Nas próximas sessões, fundamentar a teoria antes da álgebra, definir cada símbolo e cada elemento das fórmulas e desenvolver a matemática passo a passo. Evitar introduzir uma forma vetorial sem explicar previamente a origem do vetor, seu módulo, sua direção e sua normalização.

## Pendências — Física 3

- resolver exercícios de lei de Coulomb vetorial e superposição em coordenadas;
- concluir independentemente o `F3-HALLIDAY-V3-2016 → Capítulo 21, seção A Lei de Coulomb → exercício 20`;
- resolver o `F3-HALLIDAY-V3-2016 → Capítulo 21, seção A Lei de Coulomb → exercício 21` como primeiro problema completo de densidade volumétrica variável;
- refazer com menor ajuda o `F3-HALLIDAY-V3-2016 → Capítulo 22, seção Campos elétricos → exercício 26`, especialmente `dl=r\,d\theta`, a componente vertical e os limites;
- obter evidência independente de compreensão de fluxo e Lei de Gauss em um problema simples antes dos exercícios 10, 11, 24, 28 e 32 do Capítulo 23;
- obter evidência independente de domínio em um problema sem pista forte;
- os demais exercícios prioritários dos capítulos 21–24 foram apenas lidos e separados para prática, não concluídos nesta sessão.
