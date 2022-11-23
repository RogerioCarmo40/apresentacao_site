# Correção da Atividade Prática da Semana 3

Este documento contém orientações sobre como deve ser a correção da atividade prática da semana 4. A atividade consiste no completamento do código CSS do arquivo "estilos.css". As respostas das propriedades CSS que devem ser definidas no arquivo "estilos.css" estão logo abaixo desse texto. Como a atividade tem valor de 30 pontos e como são 20 questões a serem completadas, cada questão vale 1,5 pontos.

## Respostas

```css
/* 1. Configurações CSS para telas de até 1280px */
@media screen and (max-width: 1280px) {

/* 2. Posicionamento estático */
position: static;
  
/* 3. Largura de 80% da largura área de visualização */
width: 80vw;

/* 4. Altura automática */
height: auto;

/* 5. Contêiner flexbox */
display: flex;
  
/* 6. Espaço de 1rem entre itens flexbox */
gap: 1rem;

/* 7. Contêiner flexbox */
display: flex;
  
/* 8. Espaço de 3vw entre itens flexbox */
gap: 3vw;

/* 9. Largura de 2.5% da largura área de visualização */
width: 2.5vw;
  
/* 10. Margem direita de 0.6% da largura área de visualização */
margin-right: .6vw;

/* 11. Tamanho de fonte de 2.5% da largura área de visualização */
font-size: 2.5vw;

/* 12. Alinhamento vertical superior */
vertical-align: top;
  
/* 13. Margens zeradas (forçar) */
margin: 0 !important;
  
/* 14. Ocultar elemento */
display: none;

/* 15. Mostrar elemento */
display: show;

/* 16. Posicionamento estático */
position: static;
  
/* 17. Margem interna superior de 0.5rem */
padding-top: .5rem;

/* 18. Grid de duas colunas iguais */
grid-template-columns: 1fr 1fr;

/* 19. Altura automática (forçar) */
height: auto !important;

/* 20. Largura de 50% do pai, menos 0.75rem */
width: calc(50% - 0.75rem);

```