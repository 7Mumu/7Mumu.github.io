# Architecture

  Para que el juego se ejecute normalmente, necesitamos la carpeta js, la carpeta de activos y el archivo "index.html".
  ![architect1](https://github.com/7Mumu/7Mumu.github.io/blob/master/slides/architecture1.png)  
  En la carpeta js, están todos los archivos de javascript que necesitamos para que el juego funcione.
  En la carpeta assets, están las imagenes y las músicas que usamos.  
  En el archivo "index.html" tenemos la configuración de la página web del proyecto.  
  En la carpeta js, están todos los archivos de javascript que necesitamos para que el juego funcione.  
  ![architect2](https://github.com/7Mumu/7Mumu.github.io/blob/master/slides/architecture2.png)  
  
  Con los archivos Menu.js implementamos el menú inicial.  
  En el archivo Game.js está implementado las mecánicas del juego. 

  Está el protagonista del juego en "Game.js", el jugador puede usar arriba, abajo, izquierda y derecha para controlarlo y no chocar con el virus. La aceleración hacia la izquierda no es lo mismo que la aceleración hacia la derecha. La derecha será más rápida. Hay gravedad durante el salto, pero el botón hacia abajo lo acelerará un poco. La derecha será más rápida. A través de "Player.js" puedes ver que hay dos formas, la forma normal y la forma ninja. El jugador puede controlar al personaje para que toque la máscara para transformarse en un “Ninja” (traje de protección). Al atacar un virus, la salud del jugador se reducirá en uno o la forma ninja cancelará un golpe. En la forma de "Ninja",después de la exención, se volverá normal. Cuando el juego termine, aparecerá "GAMEOVER", puede hacer clic en "restart" para comenzar de nuevo. Los virus y las máscaras aparecerán aleatoriamente con el tiempo. El virus vuela del lado derecho de la pantalla a la izquierda. La máscara aparecerá aleatoriamente en un área determinada del mapa. Nuestra configuración es que el fondo se desplazará automáticamente.