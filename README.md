<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Tic-Tac-Toe Game</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="msg-container hide">  <!--to hide mssg container we us HIDE and thn in (css display none)-->
      <p id="msg">Winner</p>
      <button id="new-btn">New Game</button>
    </div>
    <main>
      <h1>Tic Tac Toe</h1>
      <div class="container">
        <div class="game">
          <button class="box"></button>
          <button class="box"></button>
          <button class="box"></button>
          <button class="box"></button>
          <button class="box"></button>
          <button class="box"></button>
          <button class="box"></button>
          <button class="box"></button>
          <button class="box"></button>
        </div>
      </div>
      <button id="reset-btn">Reset Game</button>
    </main>
    <script src="first.js"></script>
  </body>
</html>
