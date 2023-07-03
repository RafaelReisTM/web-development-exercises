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
            background-color: rgb(175, 78, 78);
          }

          #dark-red {
            background-color: rgb(173, 51, 51);
          }

          #darkest-red {
            background-color: rgb(156, 0, 0);
          }
        </style>
      </head>
      <body>
        <h1>Code School</h1>
        <h2 class="background-color">A new direction for your life</h2>
        <p class="background-color">The best way to start your tech career</p>
        <ul>
          <li id="verde">We teach to learn</li>
          <li id="verde-escuro">We teach to program</li>
          <li id="azul">We teach to work</li>
        </ul>
      </body>
    </html>

2- Coloque todo o CSS da tag style em um arquivo externo.

