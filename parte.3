# Juego.canvas.parte.3
Parte 3
Para detectar la colisión de la bola, vamos a definir una variable llamada ballRadius, añade este fragmento de código al que ya tenemos:

  var ballRadius = 15;

Ahora, tenemos que actualizar la línea que dibuja la bola en la función drawBall(), reemplaza con el siguiente fragmento:

  ctx.arc(x, y, ballRadius, 0, Math.PI*2);
  
El siguiente código sirve para que la bola rebote de arriba a abajo. Lo vamos a agregar a la función draw().

  if(y + dy > canvas.height || y + dy < 0) {
    dy = -dy;
  }

Nuestro siguiente fragmento es para que la bola pueda rebotar de derecha a izquierda, agrgalo en la función draw() debajo del fragmento anterior:

  if(x + dx > canvas.width || x + dx < 0) {
      dx = -dx;
  }

  if(y + dy > canvas.height || y + dy < 0) {
      dy = -dy;
  }
  
Pueba tu código.

Un problema que tenemos es que la bola se hunde un poco en las paredes cuando rebota, para evitar que eso pase agrega el siguiente código:

  if(x + dx > canvas.width-ballRadius || x + dx < ballRadius) {
      dx = -dx;
  }
  if(y + dy > canvas.height-ballRadius || y + dy < ballRadius) {
      dy = -dy;
  }
  
Compara tu código.

   var canvas = document.getElementById("myCanvas");
   var ctx = canvas.getContext("2d");
   var ballRadius = 15;
   var x = canvas.width/3;
   var y = canvas.height-40;
   var dx = 3;
   var dy = -3;
   function drawBall(){
       ctx.beginPath();
       ctx.arc(x, y, ballRadius, 0, Math.PI*2);
       ctx.fillStyle = "#800080";
       ctx.fill();
       ctx.closePath();
   }
   function draw() {
   ctx.clearRect(0, 0, canvas.width, canvas.height);
   drawBall();
   if(x + dx > canvas.width-ballRadius || x + dx < ballRadius) {
   dx = -dx;
   }
   if(y + dy > canvas.height-ballRadius || y + dy < ballRadius) {
   dy = -dy;
   }
    x += dx;
    y += dy;
    }
setInterval(draw, 15);
