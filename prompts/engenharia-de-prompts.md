# Engenharia de Prompts e Cicatrizes

Esta seção documenta o processo de investigação realizado no
NotebookLM durante a elaboração do caderno temático sobre
**A Dança dos Dragões**, de George R. R. Martin.

O objetivo foi utilizar perguntas estratégicas para compreender
os acontecimentos da guerra, comparar informações entre diferentes
fontes e identificar possíveis divergências, inconsistências e
limitações dos materiais consultados.

---

## 1. Prompt inicial — Compreensão do tema

### Objetivo

Obter uma visão geral da Dança dos Dragões antes de aprofundar
a pesquisa.

### Prompt utilizado

> Explique de forma detalhada o que foi a Dança dos Dragões,
> apresentando o contexto histórico, as causas do conflito,
> as principais facções, os personagens envolvidos, o papel
> dos dragões, o desfecho da guerra e suas principais
> consequências para a Casa Targaryen.

### Resultado

O NotebookLM apresentou uma visão geral do conflito, destacando
a disputa sucessória entre Rhaenyra Targaryen e Aegon II
Targaryen, a divisão entre Verdes e Negros, o uso dos dragões
como principal elemento militar e o enfraquecimento da Casa
Targaryen após a guerra.

### Aprendizado

O primeiro resultado serviu como base para identificar quais
assuntos precisavam de uma investigação mais aprofundada.

---

## 2. Prompt de aprofundamento — Contexto e causa do conflito

### Objetivo

Compreender por que a sucessão de Viserys I gerou uma guerra
civil.

### Prompt utilizado

> Analise as causas da Dança dos Dragões. Explique a sucessão
> de Viserys I, a nomeação de Rhaenyra como herdeira, o
> nascimento dos filhos de Alicent Hightower e os argumentos
> utilizados pelos Verdes e pelos Negros para justificar suas
> reivindicações ao Trono de Ferro.

### Resultado

A análise destacou o conflito entre a nomeação oficial de
Rhaenyra como herdeira e os argumentos dos partidários de Aegon II,
que utilizavam precedentes sucessórios e a preferência por
herdeiros masculinos.

Também foi possível compreender que os dois lados possuíam
argumentos políticos diferentes para justificar suas
reivindicações.

---

## 3. Prompt de comparação entre fontes

### Objetivo

Identificar informações conflitantes entre as fontes disponíveis
no NotebookLM.

### Prompt utilizado

> Compare as informações apresentadas pelas fontes sobre a Dança
> dos Dragões. Identifique divergências cronológicas, numéricas
> ou narrativas. Para cada divergência, indique quais fontes
> apresentam cada versão e explique se é possível determinar
> qual versão é mais confiável.

### Resultado

O NotebookLM identificou diversas divergências, incluindo:

- Data de término da guerra;
- Data da Batalha da Goela;
- Circunstâncias da morte de Lyman Beesbury;
- Circunstâncias da morte de Syrax;
- Circunstâncias da morte de Daeron Targaryen;
- Número de soldados dos "Rapazes";
- Diferentes relatos sobre determinados acontecimentos da guerra.

### Aprendizado

Essa etapa demonstrou que nem toda informação encontrada em
fontes secundárias deve ser tratada automaticamente como fato
absoluto.

Foi necessário distinguir entre:

- informação explícita;
- interpretação;
- relato de cronista;
- rumor dentro da narrativa;
- possível erro de uma fonte secundária.

---

# 4. Prompt de análise crítica

### Objetivo

Separar fatos confirmados de informações que deveriam ser
tratadas com cautela.

### Prompt utilizado

> Para cada divergência encontrada, classifique a informação
> como fato explícito, interpretação, inferência, rumor ou
> informação não confirmada. Explique também por que as fontes
> podem apresentar versões diferentes do mesmo acontecimento.

### Resultado

A análise mostrou que alguns acontecimentos da Dança dos Dragões
são apresentados deliberadamente de maneira ambígua dentro da
própria narrativa de *Fogo & Sangue*.

Um exemplo importante são os diferentes relatos sobre a morte de
Lyman Beesbury.

Também foram identificadas divergências sobre as mortes de alguns
personagens e dragões.

### Aprendizado

A pesquisa mostrou que a própria estrutura narrativa de
*Fogo & Sangue* exige uma leitura crítica, pois os acontecimentos
são apresentados como relatos históricos de diferentes
testemunhas e cronistas.

---

# 5. Prompt de verificação cronológica

### Objetivo

Investigar as divergências relacionadas às datas dos eventos.

### Prompt utilizado

> Analise as divergências cronológicas encontradas nas fontes
> sobre a Dança dos Dragões. Liste as diferentes datas
> apresentadas, indique qual fonte apresenta cada uma e
> explique qual cronologia deve ser utilizada como referência
> principal.

### Resultado

Foram identificadas divergências relacionadas principalmente:

- ao período geral da guerra;
- à data da Batalha da Goela;
- a informações apresentadas em diferentes obras e fontes
  secundárias.

A pesquisa indicou que, para este projeto, a cronologia de
*Fogo & Sangue* deve receber prioridade quando houver conflito
com fontes secundárias.

### Aprendizado

Foi possível perceber a importância de estabelecer uma
hierarquia de confiabilidade entre as fontes utilizadas.

---

# 6. Prompt sobre os dragões

### Objetivo

Compreender a importância militar dos dragões e o impacto da
guerra sobre essas criaturas.

### Prompt utilizado

> Analise o papel dos dragões durante a Dança dos Dragões.
> Explique quais facções possuíam vantagem, quais foram os
> principais dragões envolvidos, quais batalhas foram decisivas
> e quais foram as consequências da guerra para a população
> de dragões de Westeros.

### Resultado

O NotebookLM destacou que os dragões foram o principal diferencial
militar da guerra, mas também foram algumas das maiores vítimas
do conflito.

A pesquisa mostrou que os combates entre dragões contribuíram
diretamente para a redução drástica da população dessas criaturas.

---

# 7. Prompt sobre as limitações das fontes

### Objetivo

Identificar quais fontes realmente apresentavam informações
históricas detalhadas e quais tinham apenas informações
bibliográficas ou introdutórias.

### Prompt utilizado

> Analise a contribuição de cada uma das fontes utilizadas.
> Indique quais fontes apresentam informações históricas
> detalhadas sobre a Dança dos Dragões e quais possuem apenas
> informações bibliográficas ou introdutórias.

### Resultado

Foi identificado que algumas fontes utilizadas no NotebookLM
possuíam informações detalhadas sobre a guerra, enquanto outras
serviam principalmente como referências bibliográficas ou
contextuais.

Isso evitou que informações ausentes fossem interpretadas como
informações contraditórias.

---

# 8. Cicatrizes e troubleshooting

Durante a pesquisa foram encontradas algumas dificuldades que
precisaram ser consideradas antes da elaboração do resultado final.

## Divergências entre fontes

Algumas fontes apresentaram informações diferentes sobre o mesmo
acontecimento.

Em vez de escolher automaticamente uma das versões, a estratégia
adotada foi registrar a divergência e verificar se existia uma
fonte mais próxima do material original.

## Erros ou inconsistências em fontes secundárias

Também foram encontradas inconsistências internas em fontes
secundárias.

Um exemplo identificado foi uma contradição relacionada ao apoio
de Borros Baratheon aos Verdes ou aos Negros.

Por isso, informações isoladas de wikis foram tratadas com
cautela.

## Diferença entre cânone literário e adaptação televisiva

Outro ponto de atenção foi evitar misturar acontecimentos de
*Fogo & Sangue* com acontecimentos apresentados na série
*A Casa do Dragão*.

Quando uma informação pertence especificamente à adaptação
televisiva, ela deve ser identificada como tal.

## Relatos conflitantes dentro de Fogo & Sangue

A própria estrutura de *Fogo & Sangue* apresenta diferentes
versões para determinados acontecimentos.

Por isso, não foi possível determinar uma resposta definitiva
para algumas questões.

Nesses casos, o resultado final apresenta a divergência em vez
de transformar uma hipótese em fato.

---

# 9. Principal aprendizado sobre engenharia de prompts

O processo demonstrou que perguntas mais específicas produzem
resultados mais úteis para uma pesquisa.

A evolução ocorreu aproximadamente da seguinte maneira:

**Pergunta ampla**
↓
**Aprofundamento por assunto**
↓
**Comparação entre fontes**
↓
**Identificação de divergências**
↓
**Análise de confiabilidade**
↓
**Síntese das informações**



# 10. Conclusão da Engenharia de Prompts

A engenharia de prompts foi fundamental para transformar uma
pesquisa inicial em uma investigação mais estruturada.

Os primeiros prompts foram utilizados para obter uma visão geral
do tema. Em seguida, as perguntas foram progressivamente
especializadas para investigar causas, personagens, dragões,
cronologia e divergências entre as fontes.

Um dos principais aprendizados foi perceber que uma resposta
detalhada da inteligência artificial não significa necessariamente
que todas as informações estejam corretas. Por isso, os prompts
posteriores passaram a solicitar comparação entre fontes,
identificação de contradições e classificação das informações
quanto ao seu grau de confiabilidade.

As "cicatrizes" do processo foram justamente as situações em que
uma resposta inicial precisou ser questionada ou confrontada com
outras fontes. Essas situações contribuíram para melhorar os
prompts e para desenvolver uma abordagem mais crítica na utilização
do NotebookLM.

Dessa forma, o NotebookLM foi utilizado não apenas para gerar
resumos, mas como uma ferramenta de apoio à investigação,
comparação e organização do conhecimento.
