# Como usar
Baixe apenas o arquivo [grid.css](https://github.com/BrunoSaibert/grid-css-px/blob/master/grid.css) e adicione no seu projeto.

# Sistema de Grid
Esse sistema de grid utiliza float e foi idealizado para facilitar o desenvolvimento de interfaces responsivas e conta com uma distribuição de até 12 colunas.

# Descrição
O sistema de grid funciona a partir de um esquema de colunas dentro de um container que segura o conteúdo e tem como tamanho máximo 960px. Cada coluna flutuará para a esquerda e tem um gutter de 10px nas laterais via padding 
Veja como funciona:

- As colunas devem ser adicionadas dentro de um .container.
- O conteúdo das colunas devem iniciar com .grid-*, respeitando sempre o máximo de 12 colunas. Por exemplo, três colunas iguais usariam três .grid-4.
- As colunas são definidas em um tamanho fixo de pixiel, sendo que cada coluna tem de base 60px.

# Demonstração
[Demo](http://brunosaibert.com.br/projetos/grid-css-px/)