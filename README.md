## GRID
- Bidimensional
- Divisão de toda a página em linhas e colunas
- Colocar elementos onde quiser nessa divisão

### CONTAINER
- display: grid;
- grid-template-columns;
- grid-template-rows;
- grid-gap;
    - grid-row-gap;
    - grid-column-gap;
- grid-template-areas;

### ITEMS
- grid-column
    - grid-column-start
    - grid-column-end
- grid-row
    - grid-row-start
    - grid-row-end
- grid-area

# ALINHAMENTOS

Existem 6 propriedades para alinhamento:
1. `justify-content`
2. `align-content`
3. `justify-items`
4. `align-items`
5. `justify-self`
6. `align-self`

2 grupos
1. `justify` e `align`
2. `content`, `items` e `self`

## Justify e Align

Grid é bidimensional, tem os eixos x e y.

o **eixo x** é o posicionamento horizontal. (justify)
o **eixo y** é o posicionamento vertical. (align)

## Content, Items e Self

### Content

`justify-content` e `align-content` permite alinhar o próprio grid, relativo ao espaço fora do grid.

Podemos usar **7 valores**:
1. start
2. end
3. center
4. stretch
5. space-between
6. space-around
7. space-evenly

### Items

`justify-items` e `align-items` vai permitir alinhar os items do grid, em qualquer espaço disponível na célula que ele habitar.

Podemos usar **4 valores**:
1. start
2. end
3. center
4. stretch


### Self

`justify-self` e `align-self` alinha o item em si

Faz o mesmo que o `justify-items` e `align-items`. porém aplicado diretamente no item de um grid.