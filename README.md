# Flexbox Grid

Um sistema de grid constrúido com base no Flexbox e inspirado no Bootstrap 4, porém
mais puro, contendo só o grid e nada além.

## Breakpoints

|               |     Extra small      |  Small  | Medium  |  Large  | Extra large |
| :-----------: | :------------------: | :-----: | :-----: | :-----: | :---------: |
|    Prefix     |        .col-         | .col-sm | .col-md | .col-lg |   .col-xl   |
|  Breakpoint   |        <576px        | ≥576px  | ≥768px  | ≥992px  |   ≥1200px   |
|   Container   |         auto         |  540px  |  720px  |  960px  |   1140px    |
| N° of columns |          12          |         |         |         |             |
|    Gutter     | 30px(15px each side) |         |         |         |             |

## Funcionamento

- Há uma classe de **container**, que engloba os elementos e contém **15px** de padding em cada lado. Este .container é **suscetível aos breakpoints**, caso queira um container não influenciado pelos breakpoints, utilize o **.container-fluid**

- Cada coluna possui 15px de gutter e para compensar o gutter do container + gutter dos elementos, os itens devem estar dentro de um elemento **.row**, que compensa os paddings contendo -15px de margin em cada lado.

## Download e exemplo

- Inserir o arquivo **css/helpers.css** para ter disponível diversas classes auxiliares.
- Inserir o arquivo **css/grid.css** para ter disponível o grid.

## Exemplo

Ao baixar o repositório, o arquivo **index.html** possui um exemplo de utilização do grid
