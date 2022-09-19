Para treinar o que foi visto nesta aula, vamos recriar a imagem a seguir utilizando as novas propriedades de grid:

Página do navegador com 5 elementos quadriláteros que preenchem todo seu espaço. Esses quadriláteros possuem tamanhos e cores individuais. O layout está em um grid 4x4 (4 colunas e 4 linhas). O cabeçalho ocupa todas as colunas da primeira linha. O menu lateral ocupa 3 linhas e 1 coluna. O conteúdo do meio ocupa 2 colunas e 3 linhas. O primeiro bloco restante ocupa 1 linha e 1 coluna e o segundo bloco restante ocupa 2 linhas e 1 coluna.

O layout acima é composto pelos seguintes componentes: cabeçalho, menu lateral, conteúdo do meio e dois elementos ocupando o restante do espaço lateral.

O layout está em um grid 4x4 (4 colunas e 4 linhas). O cabeçalho deve ocupar todas as colunas da primeira linha. O menu lateral deve ocupar 3 linhas e 1 coluna. O conteúdo do meio deve ocupar 2 colunas e 3 linhas. O primeiro bloco restante deve ocupar 1 linha e 1 coluna e o segundo bloco restante deve ocupar 2 linhas e 1 coluna.

Utilize todas as propriedades vistas em aula e estes arquivos como referência:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="grid.css">
</head>
<body class="corpo">
    <header class="cabecalho"></header>
    <nav class="lateral"></nav>
    <section class="meio"></section>
    <section class="direita-cima"></section>
    <section class="direita-baixo"></section>
</body>
</html>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.corpo {
    background-color: #444444;
    padding: 8px;
    width: 100vw;
    height: 100vh;
}

.cabecalho {
    background-color: #cc2a2a;
    border-radius: 10px;
    min-width: 50px;
    min-height: 50px;
    margin: 8px;
}

.lateral {
    background-color: #45cc2a;
    border-radius: 10px;
    min-width: 50px;
    min-height: 50px;
    margin: 8px;
}

.meio {
    background-color: #2aa6cc;
    border-radius: 10px;
    min-width: 50px;
    min-height: 50px;
    margin: 8px;
}

.direita-cima {
    background-color: #352acc;
    border-radius: 10px;
    min-width: 50px;
    min-height: 50px;
    margin: 8px;
}

.direita-baixo {
    background-color: #cc2a96;
    border-radius: 10px;
    min-width: 50px;
    min-height: 50px;
    margin: 8px;
}