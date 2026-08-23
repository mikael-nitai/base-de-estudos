# Plano de estudos de Física Matemática

## Missão da disciplina

Física Matemática organiza as estruturas e as linguagens matemáticas usadas para formular, analisar e comunicar modelos físicos. A disciplina não deve ser reduzida a uma lista de técnicas: cada ferramenta precisa ser ligada às hipóteses que a tornam válida, à representação que ela permite e ao tipo de fenômeno que ajuda a descrever.

O material atualmente catalogado inicia a disciplina pelo núcleo algébrico. Ele desenvolve a passagem de conjuntos numéricos para estruturas abstratas e termina com o corpo dos números complexos. Essa base é importante para amplitudes, fases, simetrias, operadores e representações usadas posteriormente em mecânica, ondas, eletromagnetismo e física quântica, mas não substitui um curso completo de álgebra linear, análise complexa, Fourier ou equações diferenciais parciais.

**sequência organizadora:**

**axiomas e operações → estruturas algébricas → exemplos e contraexemplos → ideais e quocientes → mapas entre estruturas → números complexos → aplicações e módulos futuros.**

O agente deve consultar o [catálogo de referências](../Referencias/catalogo.md) antes de indicar capítulo, seção ou exercício. Cada exercício deve registrar, sempre que possível, `material_id`, capítulo/seção, página impressa e número do problema.

## Material-base e escopo atual

**Material principal do módulo atual:** `FM-ALGEBRA1-JANESCH-TANEJA-2011`, *Álgebra I*, Oscar Ricardo Janesch e Inder Jeet Taneja, 2ª edição revisada, UFSC, Florianópolis, 2011.

O plano atual cobre os seis capítulos do material: anéis, domínios e corpos; anéis especiais; subanéis, elementos notáveis e divisibilidade; ideais e anéis quociente; homomorfismos e isomorfismos; corpo dos números complexos.

Os módulos posteriores da Física Matemática - álgebra linear, cálculo vetorial, análise complexa, séries e transformadas, EDPs, tensores e métodos variacionais - ficam explicitamente como transição e não podem ser marcados como concluídos com base neste único PDF.

## Resultado esperado do módulo algébrico

Ao concluir o módulo atual, o estudante deve ser capaz de:

- ler definições com quantificadores e separar axioma, propriedade, exemplo e consequência;
- verificar se um conjunto com operações é anel, domínio ou corpo;
- construir exemplos e contraexemplos em `Z`, `Q`, `R`, `C`, `Z_n`, anéis de funções, anéis de matrizes e produtos diretos;
- distinguir subanel, subdomínio e subcorpo e provar fechamento quando necessário;
- identificar unidades, divisores de zero, elementos nilpotentes, idempotentes e outros elementos notáveis apresentados no material;
- usar divisibilidade, elementos primos e irredutíveis com a definição correta para a estrutura em questão;
- definir e operar com ideais, ideais primos, ideais maximais e anéis quociente;
- analisar homomorfismos, núcleo, imagem e isomorfismos conforme as propriedades estudadas;
- trabalhar com conjugado, norma, forma trigonométrica, potências e raízes de números complexos;
- produzir demonstrações curtas e completas, apontando onde cada hipótese é usada;
- reconhecer quando uma afirmação é algébrica e quando exige ferramentas de álgebra linear, análise ou física matemática ainda não estudadas.

## Gate de entrada

Antes da sequência principal, exigir desempenho operacional em:

- conjuntos, subconjuntos, relações, funções, imagem e pré-imagem;
- lógica proposicional, quantificadores, implicação, equivalência e negação;
- técnicas de demonstração direta, contrapositiva, por absurdo e por indução;
- operações com inteiros, divisibilidade, congruências e aritmética modular;
- polinômios, fatoração, frações e manipulação de expressões;
- matrizes e números complexos em nível elementar, sem presumir domínio de álgebra linear;
- leitura cuidadosa de uma definição e produção de um contraexemplo.

Se o bloqueio for de lógica, conjuntos ou aritmética, registrá-lo como pré-requisito. Não classificar uma demonstração como falha de Física Matemática quando o erro é apenas uma inferência lógica ou uma operação básica mal executada.

## Arquitetura do curso

| Unidade | Conteúdo central | Habilidade estável | Pré-requisitos principais |
|---|---|---|---|
| FM0 | Preparação, linguagem e diagnóstico | FM-definicao-demonstracao | conjuntos, lógica e aritmética |
| FM1 | Anéis, domínios e corpos | FM-estrutura-axiomatica | FM0 |
| FM2 | Anéis especiais e construções | FM-exemplo-contraexemplo | FM1 |
| FM3 | Subanéis, elementos e divisibilidade | FM-subestrutura-divisibilidade | FM1-FM2 |
| FM4 | Ideais e anéis quociente | FM-ideais-quocientes | FM3 |
| FM5 | Homomorfismos e isomorfismos | FM-mapas-estruturais | FM4 |
| FM6 | Corpo dos números complexos | FM-complexos-representacao | FM1; trigonometria |
| FM7 | Síntese e ponte para módulos futuros | FM-transferencia | FM0-FM6 |

## Unidades detalhadas

### FM0 - Preparação, linguagem e diagnóstico

**Pergunta orientadora:** como ler uma definição matemática de modo que cada hipótese possa ser usada em uma demonstração?

**Objetivos:**

- revisar conjunto, operação binária, função, relação e propriedade;
- distinguir “para todo”, “existe”, “se”, “somente se” e “se e somente se”;
- praticar demonstração direta, contrapositiva, absurdo e indução;
- reconhecer fechamento, associatividade, comutatividade, elemento neutro e inversos;
- transformar uma definição em uma lista de verificações;
- usar exemplos pequenos para testar uma conjectura antes de tentar prová-la.

**Representações essenciais:** tabela de operação, diagrama de inclusão, mapa de função, prova em linhas justificadas e tabela de casos.

**Erros a vigiar:** provar apenas exemplos; inverter implicação; usar uma propriedade sem demonstrá-la; confundir elemento com subconjunto; afirmar fechamento porque o conjunto “parece” estável; esconder uma divisão por zero.

**Evidência de saída:** negar corretamente três afirmações quantificadas, verificar uma operação em um conjunto finito e escrever uma demonstração curta com todas as hipóteses identificadas.

### FM1 - Anéis, domínios e corpos

**Fonte principal:** capítulo 1, seções 1.1-1.3.

**Pergunta orientadora:** quais propriedades mínimas das operações permitem transportar a aritmética para conjuntos que não são conjuntos numéricos usuais?

**Objetivos:**

- compreender a definição de anel conforme a convenção adotada no material;
- distinguir anel, anel com unidade, anel comutativo, domínio e corpo;
- verificar os axiomas em exemplos concretos;
- deduzir propriedades operacionais a partir dos axiomas, em vez de tratá-las como regras universais;
- comparar `Z`, `Q`, `R` e `C` com estruturas que falham em alguma propriedade;
- identificar a diferença entre estrutura abstrata e natureza dos elementos;
- explicar por que a linguagem de estruturas é útil para a física matemática.

**Representações essenciais:** tabela de axiomas, diagrama de implicações entre classes de estruturas, exemplos/contraexemplos e prova algébrica passo a passo.

**Erros a vigiar:** chamar todo conjunto com duas operações de anel; confundir anel comutativo com domínio; supor que todo anel possui inverso multiplicativo; usar cancelamento sem verificar hipóteses; confundir `0` e `1` estruturais com números particulares.

**Evidência de saída:** classificar estruturas novas, provar propriedades básicas a partir dos axiomas e construir um contraexemplo para cada implicação falsa do diagrama.

### FM2 - Anéis especiais e construções

**Fonte principal:** capítulo 2, seções 2.1-2.4.

**Pergunta orientadora:** como a mesma definição de anel se manifesta em funções, matrizes, aritmética modular e produtos de estruturas?

**Objetivos:**

- estudar anéis de funções e identificar operações ponto a ponto;
- analisar anéis de matrizes, incluindo a possibilidade de não comutatividade;
- operar em `Z_n` com classes de restos e módulo explicitamente indicado;
- compreender o anel produto direto e suas projeções;
- comparar propriedades que são preservadas e propriedades que mudam entre construções;
- usar exemplos pequenos para encontrar unidades, divisores de zero e falhas de cancelamento;
- separar “anel de matrizes” de um curso completo de álgebra linear.

**Representações essenciais:** tabela modular, produto de matrizes, função como elemento de um anel, pares ordenados e diagramas de projeção.

**Erros a vigiar:** tratar `Z_n` como conjunto de inteiros sem classes; reduzir expressões no módulo errado; supor que matrizes comutam; confundir produto direto com produto usual de números; transferir uma propriedade de um fator para o produto sem prova.

**Evidência de saída:** construir e classificar quatro anéis especiais, calcular operações em cada um e explicar uma propriedade que aparece em um exemplo mas falha em outro.

### FM3 - Subanéis, elementos notáveis e divisibilidade

**Fonte principal:** capítulo 3, seções 3.1-3.3.

**Pergunta orientadora:** como estudar uma estrutura menor sem perder as operações e quais elementos controlam sua aritmética interna?

**Objetivos:**

- verificar critérios de subanel, subdomínio e subcorpo;
- distinguir subconjunto fechado de subestrutura com todas as propriedades necessárias;
- identificar unidades, divisores de zero, nilpotentes, idempotentes e demais elementos notáveis definidos no capítulo;
- interpretar divisibilidade dentro do anel, sem importar automaticamente a aritmética de `Z`;
- distinguir elementos primos e irredutíveis;
- comparar fatoração e cancelamento em domínios e anéis com divisores de zero;
- produzir contraexemplos em anéis especiais e produtos diretos.

**Representações essenciais:** reticulado de subestruturas, tabela de unidades/divisores de zero, relações de divisibilidade e fatorações acompanhadas de hipóteses.

**Erros a vigiar:** provar apenas que o subconjunto é não vazio; confundir inverso aditivo com multiplicativo; usar “primo” como sinônimo de “irredutível”; cancelar um fator que pode ser divisor de zero; considerar apenas fatorações em `Z`.

**Evidência de saída:** decidir se um subconjunto é subanel, classificar elementos de um anel finito e demonstrar uma afirmação de divisibilidade com a definição apropriada.

### FM4 - Ideais e anéis quociente

**Fonte principal:** capítulo 4, seções 4.1-4.4.

**Pergunta orientadora:** como um subconjunto compatível com a multiplicação permite construir uma nova aritmética por classes de equivalência?

**Objetivos:**

- definir ideal e verificar o critério de ideal em exemplos;
- operar com soma, produto e aritmética de ideais;
- distinguir ideais principais, primos e maximais;
- construir classes laterais e compreender a ideia de anel quociente;
- verificar quando as operações no quociente são bem definidas;
- relacionar ideais a congruências e à perda controlada de informação;
- comparar o quociente com `Z_n` sem presumir que toda construção é igual.

**Representações essenciais:** diagrama de inclusão, classes de equivalência, tabela de operações no quociente, geradores de ideais e mapa de projeção.

**Erros a vigiar:** chamar qualquer subanel de ideal; esquecer a absorção pela multiplicação; operar com representantes sem provar independência da escolha; confundir ideal primo com elemento primo; assumir que todo quociente é um domínio ou corpo.

**Evidência de saída:** verificar um ideal, calcular operações no anel quociente e provar ou refutar que o quociente possui propriedades de domínio ou corpo.

### FM5 - Homomorfismos e isomorfismos

**Fonte principal:** capítulo 5, seções 5.1-5.3.

**Pergunta orientadora:** quando dois anéis têm descrições diferentes, como demonstrar que preservam a mesma estrutura algébrica?

**Objetivos:**

- verificar se uma função preserva soma, produto e unidade quando exigido;
- calcular e interpretar núcleo, imagem e pré-imagens;
- provar propriedades decorrentes de um homomorfismo;
- distinguir homomorfismo, monomorfismo, epimorfismo e isomorfismo conforme a terminologia adotada;
- reconhecer injetividade e sobrejetividade por critérios estruturais;
- usar isomorfismos para transportar propriedades e simplificar cálculos;
- relacionar mapas, ideais e quocientes em nível compatível com o material.

**Representações essenciais:** diagrama comutativo, tabela de preservação de operações, núcleo/imagem e comparação entre estruturas.

**Erros a vigiar:** provar apenas preservação da soma; esquecer a unidade quando ela faz parte da definição; confundir imagem com contradomínio; afirmar isomorfismo sem provar bijetividade; transportar propriedades que não são invariantes do mapa.

**Evidência de saída:** classificar funções entre anéis, calcular núcleo e imagem, provar um isomorfismo e explicar que informação estrutural é preservada.

### FM6 - Corpo dos números complexos

**Fonte principal:** capítulo 6, seções 6.1-6.5.

**Pergunta orientadora:** como o corpo `C` amplia a aritmética e oferece uma representação adequada para amplitude, fase e oscilações?

**Objetivos:**

- construir e operar com números complexos como elementos de um corpo;
- distinguir parte real, parte imaginária, conjugado e norma;
- usar forma cartesiana, polar e trigonométrica;
- calcular potências por forma trigonométrica e fórmula de De Moivre;
- encontrar e interpretar raízes n-ésimas complexas;
- identificar subdomínios de `C` e distinguir estrutura de representação geométrica;
- conectar complexos a rotações e oscilações sem transformar a conexão em uma aplicação física não demonstrada;
- verificar resultados por módulo, argumento e conjugação.

**Representações essenciais:** plano complexo, vetor, forma polar, círculo unitário, raízes igualmente espaçadas e tabela de conjugação/norma.

**Erros a vigiar:** somar módulos em vez de números; perder os múltiplos de `2π`; escolher uma única raiz n-ésima; confundir conjugado com inverso; usar argumento sem declarar ramo; aplicar regras de logaritmo real diretamente a complexos.

**Evidência de saída:** converter entre representações, calcular potências e todas as raízes, justificar a geometria da solução e verificar o resultado por conjugado e norma.

### FM7 - Síntese e ponte para a física matemática

**Pergunta orientadora:** como reconhecer a estrutura matemática de um problema físico e saber qual ferramenta ainda falta estudar?

**Objetivos:**

- integrar axiomas, construções, quocientes, mapas e complexos em um mapa conceitual;
- resolver problemas em que a estrutura não seja informada no enunciado;
- comunicar demonstrações e cálculos com hipótese, argumento e conclusão;
- usar complexos como linguagem de rotação e fase em situações introdutórias;
- distinguir o que é coberto pelo material de Álgebra I do que exige álgebra linear, análise ou EDPs;
- planejar os próximos módulos a partir das necessidades da Física Matemática.

**Composição recomendada:**

- um problema de classificação de estrutura;
- um exemplo/contraexemplo em anel especial;
- um problema de subanel ou divisibilidade;
- um ideal e um quociente;
- um homomorfismo com núcleo e imagem;
- uma questão de potências ou raízes complexas;
- uma reflexão sobre qual ferramenta adicional seria necessária para modelar um fenômeno físico.

**Evidência de saída:** resolver um conjunto misto sem receber a definição ou o método no título, justificar cada propriedade utilizada e indicar honestamente quais partes dependem de um módulo ainda não catalogado.

## Gates de progressão

### Gate FM-Definição e prova

- definições reescritas com quantificadores;
- exemplos e contraexemplos corretos;
- demonstração sem saltos lógicos relevantes;
- operações e hipóteses explicitamente verificadas.

### Gate FM-Estruturas

- anéis, domínios e corpos classificados;
- anéis especiais comparados;
- propriedades não transferidas sem prova;
- subestruturas reconhecidas por critérios adequados.

### Gate FM-Ideais e mapas

- ideal e quociente construídos corretamente;
- primalidade/maximalidade distinguidas;
- homomorfismo verificado em todas as operações necessárias;
- núcleo, imagem e isomorfismo interpretados.

### Gate FM-Complexos

- formas cartesiana, polar e trigonométrica convertidas;
- conjugado e norma usados como verificações;
- potências e raízes completas;
- argumento e periodicidade tratados corretamente.

### Gate FM-Transferência

- problema inédito resolvido sem indicação da técnica;
- prova ou cálculo auditável;
- contraexemplo usado quando uma afirmação falha;
- fronteira entre álgebra, física e módulos futuros explicitada;
- retenção confirmada em revisão espaçada.

## Avaliação recomendada

- diagnóstico: lógica, conjuntos, operações e demonstrações;
- avaliação 1: anéis, domínios, corpos e anéis especiais;
- avaliação 2: subanéis, elementos notáveis e divisibilidade;
- avaliação 3: ideais e anéis quociente;
- avaliação 4: homomorfismos e isomorfismos;
- avaliação 5: números complexos e síntese;
- avaliação final cumulativa, com pelo menos 30% de demonstração, contraexemplo, classificação e interpretação.

Toda avaliação deve conter pelo menos uma questão em que a estrutura não seja nomeada e uma questão em que o estudante precise refutar uma afirmação falsa.

## Ritmo de referência

Em aproximadamente 12-14 semanas para o módulo atual:

- 1 semana: FM0;
- 2 semanas: FM1;
- 2 semanas: FM2;
- 2 semanas: FM3;
- 2 semanas: FM4;
- 2 semanas: FM5;
- 2 semanas: FM6;
- 1 semana: FM7 e síntese.

O tempo não é critério de domínio. Se a linguagem de prova ou a aritmética modular forem bloqueadoras, ativar uma recuperação específica sem avançar por memorização de definições.

## Instruções específicas ao agente tutor

- Antes de uma demonstração, pedir a definição exata e as hipóteses disponíveis.
- Em qualquer estrutura, testar primeiro as operações e o elemento neutro; não inferir propriedades pela aparência dos elementos.
- Em anéis de matrizes, perguntar explicitamente se a multiplicação é comutativa e se há unidade.
- Em `Z_n`, manter o módulo visível em todas as operações.
- Ao propor um contraexemplo, explicar qual hipótese falha e qual conclusão deixa de valer.
- Em ideais e quocientes, verificar absorção e boa definição das operações antes de calcular.
- Em homomorfismos, pedir preservação, núcleo, imagem e bijetividade separadamente.
- Em complexos, pedir uma verificação por conjugado, norma, módulo ou argumento.
- Usar o material catalogado como livro de teoria e exercícios; registrar ID, capítulo/seção e problema.
- Não atribuir ao PDF conteúdos de álgebra linear completa, cálculo vetorial, análise complexa ou EDPs.
- Não marcar uma unidade como dominada apenas porque o estudante repetiu uma definição; exigir classificação, prova, contraexemplo e transferência.

## Critério de conclusão e transição

O estudante conclui o módulo atual quando consegue trabalhar com estruturas algébricas e números complexos sem depender de reconhecimento superficial de fórmulas. A próxima etapa deve ser definida conforme a ementa institucional e novos materiais: álgebra linear e espaços vetoriais, cálculo vetorial, análise complexa, séries e transformadas, equações diferenciais parciais, tensores ou métodos variacionais. Esses tópicos não estão cobertos pelo arquivo `FM-ALGEBRA1-JANESCH-TANEJA-2011` e só devem ser incorporados ao plano com referências correspondentes.
