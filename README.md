## Contextos e Objetivos

Este NotebookLM foi desenvolvido com foco no estudo de probabilidade, área fundamental para estatística e ciência de dados. O interesse pelo tema surgiu da sua importância na análise de incertezas e na construção de modelos preditivos.

O principal objetivo é consolidar conceitos teóricos, aplicar exemplos práticos e desenvolver uma base sólida que auxilie na resolução de problemas e na evolução contínua dos meus conhecimentos na área.

## Curadoria de Fontes

https://www.ime.usp.br/~leorolla/papers/probabilidade.pdf
https://www.ifb.edu.br/attachments/6243_Probabilidade%20e%20Estat%C3%ADstica%202.pdf
https://wp.ufpel.edu.br/clause/files/2020/09/Probalidade-e-Estatistica-para-Engenharia-e-Ciencias-Devore.pdf
https://pt.scribd.com/document/405610070/286735672-Barry-R-James-Probabilidade-um-curso-Intermediario-pdf-pdf?utm_source=chatgpt.com

## Engenharia de Prompts e "Cicatrizes"

Durante o estudo, utilizei prompts estruturados pedindo resumos em tópicos com exemplos (como nas propriedades da esperança) e também demonstrações passo a passo com indicação dos teoremas utilizados. 

Testei variações mais específicas, como exigir explicações detalhadas e aplicação prática, o que melhorou a qualidade das respostas. As respostas foram validadas com materiais teóricos para garantir consistência.

Como dificuldade, percebi que prompts genéricos geravam respostas superficiais, exigindo refinamento contínuo. O principal aprendizado foi que detalhar o formato da resposta (tópicos, exemplos e justificativas) melhora significativamente o resultado e evidencia o raciocínio por trás das soluções.

# Promps Usados

Vou citar dois promps usados e suas respostas

"Faça um breve resumo sobre as propriedades da esperança com cada propriedade em tópicos e com um pequeno exemplos em cada tópico"

Aqui está um resumo das principais propriedades da esperança matemática, conforme apresentadas nas fontes:
Esperança de uma Constante: A esperança de uma constante k é a própria constante, ou seja, E[k]=k
.
Exemplo: Se o prêmio de um jogo é fixo em R$ 10,00, o valor esperado desse ganho é 10
.
Linearidade: A esperança de uma combinação linear de variáveis é a combinação linear de suas esperanças, expressa como E[aX+b]=aE[X]+b e E[X+Y]=E[X]+E[Y]
.
Exemplo: No lançamento de dois dados independentes, a esperança da soma dos resultados é a soma das esperanças individuais (3,5+3,5=7)
.
Monotonicidade: Se uma variável aleatória X é quase certamente menor ou igual a Y (X≤Y), então E[X]≤E[Y]
.
Exemplo: Se um investimento Y sempre paga o mesmo valor que o investimento X mais um bônus positivo, a esperança de ganho em Y será maior ou igual à de X
.
Esperança do Produto (Independência): Se X e Y forem variáveis aleatórias independentes, a esperança do produto é o produto das esperanças: E[XY]=E[X]⋅E[Y]
.
Exemplo: Se você lança um dado e uma moeda independentemente, a esperança do produto dos resultados (atribuindo valores numéricos à moeda) é o produto dos valores esperados de cada um
.
Propriedade da Função Indicadora: A esperança da função indicadora de um evento A (que vale 1 se A ocorre e 0 caso contrário) é igual à probabilidade do próprio evento: E[1 
A
​
 ]=P(A)
.
Exemplo: Se X é uma variável que assume 1 para "cara" e 0 para "coroa" em uma moeda honesta, E[X]=P(cara)=0,5
.
Lei das Expectativas Iteradas: A esperança total de uma variável X pode ser calculada como a esperança da sua esperança condicional em relação a outra variável Y, ou seja, E[X]=E[E[X∣Y]]
.
Exemplo: Se um jogador lança um dado para definir quantas moedas vai jogar, a média total de "caras" obtidas é a média das médias parciais para cada resultado possível do dado
.
Desigualdade de Jensen: Para qualquer função convexa g, a esperança da função da variável é maior ou igual à função da esperança: E[g(X)]≥g(E[X])
.
Exemplo: O valor esperado do quadrado de uma variável é sempre maior ou igual ao quadrado do seu valor esperado (E[X 
2
 ]≥(E[X]) 
2
 )
