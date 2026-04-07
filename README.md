<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Exercício Margin, Padding e Border</title>
  <style>
    h1 {
      margin: 30px;              /* espaço externo */
      padding: 10px;             /* espaço interno */
      border: 2px solid blue;    /* borda */
      background-color: lightgray;
    }

    p {
      margin: 10px;              /* espaço externo menor */
      padding: 20px;             /* mais espaço interno */
      border: 3px dashed red;    /* borda tracejada */
      background-color: lightyellow;
    }

    .caixa {
      margin: 40px;              /* bastante espaço externo */
      padding: 5px;              /* pouco espaço interno */
      border: 4px dotted green;  /* borda pontilhada */
      background-color: lightpink;
    }
  </style>
</head>
<body>
  <h1>Exemplo com H1</h1>
  <p>Este é um parágrafo com margin, padding e border aplicados.</p>
  <div class="caixa">Sou uma div estilizada com margin, padding e border.</div>
</body>
</html>
