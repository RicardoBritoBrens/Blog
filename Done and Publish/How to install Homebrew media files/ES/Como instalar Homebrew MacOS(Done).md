# Como instalar Homebrew en mac OS

## ¿Qué es Homebrew?

De acuerdo con el sitio oficial de Homebrew es todo lo que tú necesitas que Apple no instala por defecto.

Yo pienso que Apple debería considerar incluir esta herramienta como un paso de inicio cuando se restablece una computadora con los valores de fábrica o cuando se compra nueva.

¡Iniciemos!


## Paso 0 - Descargando Homebrew

* Abre tu terminal por defecto, en mi caso estaré usando la terminal que es incluida por defecto la cual es [zsh](https://ohmyz.sh/) esto es así desde la liberación del sistema operativo macOS Catalina en octubre 7 del 2019

Tú puedes encontrarla en la carpeta de aplicaciones como `Terminal.app`.

![Terminal.app](https://macreports.com/wp-content/uploads/2019/05/terminal-app-icon.png)

Este es el icono de la aplicación.

* Copia y pega el siguiente texto, presiona enter y espera a que la descarga se complete.

``` bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)
```

## Paso 1 - Validando la versión instalada

Después que la descarga se complete procedemos a ejecutar el siguiente comando para verificar la correcta instalación de la herramienta.

``` bat
 brew -v
```
O

``` bat
 brew --version
```

Luego deberías de ver lo siguiente en tu terminal.

![brew version](https://github.com/RicardoBritoBrens/Blog/blob/main/How%20to%20install%20Homebrew%20media%20files/brew%20version%20command.png?raw=true)

## Paso 2 - Descargando paquetes

Para descargar nuevas aplicaciones / herramientas puedes usar la siguiente estructura.

brew install + `nombre de paquete/herramienta`

Ejemplo:

``` bat
 brew install discord
```

Luego deberías de ver lo siguiente en tu terminal.

![brew install command progress](https://github.com/RicardoBritoBrens/Blog/blob/main/How%20to%20install%20Homebrew%20media%20files/brew%20install%20command%20progress.png?raw=true)

![brew install command finish](https://github.com/RicardoBritoBrens/Blog/blob/main/How%20to%20install%20Homebrew%20media%20files/brew%20install%20command%20finish.png?raw=true)

¡Eso es todo, ya tienes todo listo!

## Extra

En caso de que necesites remover aplicaciones/herramientas puedes ejecutar el siguiente comando, usando la misma estructura anterior.

``` bat
 brew remove discord
```

![brew remove command](https://github.com/RicardoBritoBrens/Blog/blob/main/How%20to%20install%20Homebrew%20media%20files/brew%20remove%20command.png?raw=true)

Esto es todo por ahora, espero que este pequeño tutorial te sirva de la misma forma que me ha servido a mí.

Para una referencia completa puedes verificar la documentación oficial Homebrew [Aquí](https://brew.sh/index_es).

