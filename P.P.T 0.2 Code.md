<html>
 <head>
  <meta charset="utf-8"/>
   <title> Piedra, papel o tijera </title>
    <script>
        function aleatorio (min, max) {
            return Math.floor(Math.random() * (max - min+1)+min)}
     let jugador = 0
     let pc = aleatorio (1,3)
     jugador = parseInt (prompt("Elige: 1 para Piedra 🗿, 2 para Papel 📄 o 3 para Tijera ✂️ "))
     if (jugador == 1) {alert ("Elegiste Piedra 🗿")} 
     else if (jugador == 2) {alert ("Elegiste Papel 📄")}
     else if (jugador == 3) {alert ("Elegiste Tijera ✂️")}
     else alert ("Elegiste PERDER!!")
     //combate
     if(pc == jugador) {alert ("EMPATE")}
     else if (jugador == 1 && pc == 3) {alert ("GANASTE")}
     else if (jugador == 2 && pc == 1) {alert ("GANASTE")}
     else if (jugador == 3 && pc == 2) {alert ("GANASTE")}
     else {alert ("PERDISTE")}
     //para saber que eligio el pc
     if(pc == 1) {alert ("PC eligio 🗿")}
     else if(pc == 2) {alert ("PC eligio 📄")}
     else if(pc == 3) {alert ("PC eligio ✂️")}
     //Por si el pc elige una opcion no valida
     else {alert ("EL PC PERDIO ✂️")}
    </script>
   </head>
  <body>
    <h1>Piedra, Papel o Tijera</h1>
    <p>Bienvenido a Piedra, Papel o Tijera
        1. Selecciona el numero correspondiente a su objeto de desicion
        2. Una vez seleccionado el objeto oprima ENTER
        3. Mantengase atento a las alertes que apareceren indicando su resultado
    Para volver a jugar, recargue la pagina o oprima COMMAND + R
    </p>
</body>
</html>
