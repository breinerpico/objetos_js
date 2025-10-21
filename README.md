# objetos_js

# Intevalos De Tiempo

En JavaScript, cuando se habla de intervalos de tiempo, normalmente se hace referencia a dos funciones globales muy utilizadas:

* setInterval()

* setTimeout()

Sin embargo, no son objetos por sí mismos, pero el objeto global Window (en entornos de navegador) es quien proporciona estas funciones.

# Window

El objeto Window proporciona métodos para controlar los intervalos de tiempo en la ejecución de código. Específicamente:

* setTimeout(): Ejecuta una función una sola vez después de un retraso especificado.

* setInterval(): Ejecuta una función repetidamente, con un retardo fijo entre cada llamada.*

Estos métodos son útiles para:

1.Temporizadores

2.Ejecuciones periódicas

3.Animaciones simples

4.Actualización de contenido en tiempo real (como relojes, contadores, etc.)

# Principales métodos relacionados con intervalos
Método	                            
1.setTimeout(function, delay)     
2.clearTimeout(id)	                
3.setInterval(function, delay)	    
4.clearInterval(id)	              

Descripción
1.Ejecuta una función después de un retraso (enmilisegundos).
2.Cancela una función programada con setTimeout.
3.Ejecuta una función repetidamente cada cierto tiempo.
4.Detiene la ejecución repetitiva programada con setInterval.

# Propiedades relacionadas

typeof window.setTimeout === "function" // true


# Ejemplo de página web que utiliza intervalos de tiempo

Ejemplo: Un sitio de reloj digital en tiempo real.

Página de ejemplo: https://time.is/

Esta página muestra la hora actual en tiempo real. Para lograr esto, probablemente utiliza setInterval() para actualizar el contenido del DOM cada segundo.