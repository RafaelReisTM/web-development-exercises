# CSS seletores e posicionamento

1- Crie um arquivo 'index.html', no qual deverão ser inseridas as informações dos próximos itens, com o seguinte formato:

    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Exercise: box model</title>
      <link rel="stylesheet" href="style.css">
    </head>
    <body>
      <div id="1" class="box width-and-height">A</div>
      <div id="2" class="box width-and-height padding"">B</div>
      <div id="3" class="box width-and-height padding margin">C</div>
      <div id="4" class="box width-and-height padding margin border">D</div>
    </body>
    </html>

2- Adicione 'style="background: #036b52"' na div #1

3- Adicione 'style="background: #41197f;"' na div #2

4- Adicione 'style="background: #444955"' na div #3

5- Adicione 'style="background: #3898EC"' na div #4

6- Crie um arquivo 'style.css', no qual deverão ser inseridas as informações dos próximos itens, com o seguinte formato:

    .box {
      color: white;
      display: inline-block;
      line-height: 50px;
      text-align: center;
      vertical-align: top;
    }

    .width-and-height {
      height: 50px;
      width: 50px;
    }

2- Crie uma classe '.padding' e insira um padding de 20px para aplicá-lo aos itens B, C e D 

3- Crie uma classe '.margin' e insira uma margem de 30px para aplicá-la aos itens C e D

4- Crie uma classe '.border' e insira uma borda com valor '5px solid black' para aplicá-la ao item D
