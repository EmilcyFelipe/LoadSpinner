# LoadSpinner

## Objetivo
  Desenvolver uma tela para aguardar o carregamento da página

## Tecnologias envolvidas
  Os recursos para a construção são simples, foram utilizados apenas html, css e javascript
  
## Funcionalidade
  O efeito de carregamento com elementos em centrifugação foi construído utilizando eixos no centro com pequenos elementos circulares à esquerda(as esferas que aparecem na tela), apesar de  não aparecerem em tela, esses eixos são fundamentais para realizar essa estrutura, já que são neles que será aplicado a ferramenta de rotação do css, "transform: rotateZ();", a relevância desses eixos está relacionada a necessidade de aplicar um ponto de origem deslocado das esferas, que será o raio de rotação.
