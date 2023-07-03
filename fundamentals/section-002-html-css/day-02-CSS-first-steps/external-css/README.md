# CSS inline e externo

1- Crie um arquivo 'index.html', no qual deverão ser inseridas as informações dos próximos itens, com o seguinte formato:

    <!DOCTYPE html>
    <html lang="pt-br">
      <head>
        <meta charset="UTF-8">
        <title>CodeSchool</title>
        <style>
          h1 {
            color: seagreen;
            font-size: 65px;
            font-family: sans-serif, Helvetica; 
          }

          .background-color {
            background-color: whitesmoke;
          }

          p {
            font-weight: 600;
          }

          body {
            font-size: 16px;
          }

          li {
            font-style: italic;
            line-height: 60px;
            text-align: center;
            text-decoration: underline;
            font-size: 2em;
          }

          #red {
            background-color: green;
          }

          #dark-red {
            background-color: seagreen;
          }

          #darkest-red {
            background-color: blue;
          }
        </style>
      </head>
      <body>
        <h1>Code School</h1>
        <h2 class="cor-de-fundo">A new direction for your life</h2>
        <p class="cor-de-fundo">The best way to start your tech career</p>
        <ul>
          <li id="verde">We teach to learn</li>
          <li id="verde-escuro">We teach to program</li>
          <li id="azul">We teach to work</li>
        </ul>
      </body>
    </html>

2- Coloque todo o CSS da tag style em um arquivo externo.

