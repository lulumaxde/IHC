Interação Humano Computador

# Introdução 

O objetivo do trabalho é criar uma plataforma que facilite e otimize os processos de combinação entre as empresas que oferecem desafios e startups que buscam mercado e oportunidades. A plataforma será utilizada pelo intermediador entre essas empresas (Nexus) e tem o objetivo de auxiliar nas seguintes tarefas: filtragem de empresas e desafios, acompanhamento de desafios em andamento, visualização de dados relacionados aos desafios.

## Personas
Neste caso temos 3 partes envolvidas que podem estar diretamente ou indiretamente atuando na plataforma. São eles o Nexus, a Corporate, geralmente uma empresa de médio/grande porte, e a Startup que é uma empresa incubada no Nexus. Diante disso, criamos 3 personas diferentes: Julia, Ricardo e Matheus.

### 1. Julia
<img src="src\img\julia_persona.png" alt="Julia">

### 2. Ricardo
<img src="src\img\matheus_persona.png" alt="Ricardo">

### 3. Matheus
<img src="src\img\ricardo_persona.png" alt="Julia">


Note que temos mais informações sobre Julia, que no caso é o nosso principal usuário do projeto, durante a execução iremos nos atentar a ela. No entanto, achamos que seria importante desenvolver personas das outras partes envolvidas indiretamente, para manter uma visão das necessidades globalmente.

## Métodos de Pesquisa utilizados

No contexto do projeto, foram escolhidas duas técnicas para a etapa inicial de pesquisa e entendimento do problema. 
A primeira foi a de **entrevista**. Com esse método, conseguimos ter uma conversa aprofundada com a pessoa responsável pelo sistema, que conhece o processo do início ao fim, suas dificuldades e pôde nos ajudar a entender o problema. 
O processo se mostrou muito eficiente, pois conseguimos extrair muitas informações importantes e identificar problemas e pontos de melhorias.

O segundo método utilizado foi de o **análise de fluxo**. Ele permite que representemos o fluxo de informação e atividades durante todo o processo, nos ajudando a identificar pontos que apresentam problemas, assim como oportunidades de melhoria.
Essa análise de mostrou essencial para entendermos todo o processo, e os problemas que vamos poder tentar resolver. 

Esses dois métodos se complementaram muito bem pois, a partir das informações que conseguimos com a entrevista, foi possível aprimorar o fluxo que tínhamos feito inicialmente, e o fluxo nos ajudou muito durante esta fase inicial de entender o processo, encontrar pontos de melhoria, e propor soluções efetivas.

Também fizemos uma pesquisa, que seria enviada para empresas do Nexus, com o objetivo de coletar informações e feedback sobre o processo de desafio, mas não foi possível finanizá-la, pois não conseguimos o contato da empresas.

## Perguntas e Respostas Método entrevista

#### 1. Como os desafios são propostos para o nexus?
O nexus possui desafios distintos, existe o caso de desafios direto onde  uma empresa tem uma necessidade específica e o nexus indica uma startup que possa fornecer uma solução e desafios abertos (Inovação aberta) onde grandes empresas desejam incubar ideias inovadoras. As demandas chegam por email, por reuniões, através de parcerias e tem o caso de desafios abertos (Inovação aberta) que são demandas mais complexas onde é feito o contato direto com a empresa demandante através de email e outros.

#### 2. Os desafios são públicos para todas empresas? 
Os desafios são privados.

#### 3. Como funciona o sistema de armazenamento dos desafios?
No primeiro caso onde os desafios são diretos, ou seja, onde uma determinada empresa grande possui uma necessidade específica e o nexus faz uma conexão entre startups, esse tipo de desafio é armazenado em uma planilha de conexão.
Em grandes desafios onde as grandes empresas abrem uma chamada onde várias empresas participam e a premiação é a incubação da empresa no nexus, esses desafios também são armazenados em planilhas.

#### 4. Quais informações são necessárias para o match do desafio com as empresas menores?
A informação vai depender da empresa que cria o desafio, por exemplo, ela pode solicitar condições como maturidade da empresa, pode exigir que a empresa já tenha passado por uma rodada de investimento, que tenha um determinado faturamento anual, que seja de um determinado segmento etc… Existe uma planilha que armazena informações das empresas do nexus.

#### 5. Após as empresas passarem pela etapa de match, o nexus faz o acompanhamento do desafio?
No caso de grandes desafios o acompanhamento é realizado durante o decorrer do processo de incubação, já em desafios pontuais o acompanhamento é feito de maneira informal.

#### 6. Existe algum indicador/acompanhamento que mede as conexões?
Existe uma planilha geral que faz o controle das conexões que são feitas, essa planilha engloba todas empresas.

#### 7. O nexus possui uma identidade visual?
Existe uma página no site do nexus que tem informações sobre a identidade visual.

#### 8. Quais são os critérios para o match em desafios diretos?(Desafios diretos são aqueles onde uma empresa tem uma necessidade específica e uma startup é indicada para que possa fornecer uma solução)
Existem eixos para as startups serem selecionadas, dentre esses eixos podemos ter alguns alguns requisitos como Maturidade, Equipe, Faturamento, Capacidade de desenvolvimento tecnológico etc.

#### 9. Qual nomenclatura é utilizada para empresas contratada e contratante?
Geralmente é utilizado o nome da empresa, porém pode ser utilizado as seguintes nomenclaturas.
contratada - Startup
contratante - Corporate

## Diagrama de fluxo

<img src="src\img\fluxo1.png" alt="Fluxo 1">
<p style="text-align: center;"><i>Diagrama inicial do projeto.</i></p>

<img src="src\img\fluxo2.png" alt="Fluxo 2">
<p style="text-align: center;"><i>Diagrama do projeto após a entrevista.</i></p>

## Usos do Sistema

A partir desta etapa de pesquisa e entendimento do problema, conseguimos chegar à alguns usos para o sistema, que são:

1. Filtragem das startup cadastradas com base em suas principais características.
2. Visualização de informações das startups cadastradas em formato de dashboard. 
3. Monitoramento dos desafios ativos.
4. Consulta do histórico de desafios realizados ou cadastrados na plataforma.
5. Visualização de métricas geradas pelos desafios cadastrados.
6. Filtragem dos desafios com base em suas principais características. 
1. Uso do algoritmo de match que recomenda uma lista de empresas que combinam com um determinado desafio.
