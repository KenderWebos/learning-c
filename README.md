# Como puedo compilar C en WINDOWS ?

### 1. Instalar MinGW:

Primero, debes descargar e instalar MinGW (Minimalist GNU for Windows), que es un conjunto de herramientas que incluye el compilador GCC (GNU Compiler Collection) para compilar programas en C y C++ en entornos Windows.

- Ve al enlace: https://sourceforge.net/projects/mingw/
- Descarga el instalador según tu arquitectura (32 bits o 64 bits).
- Ejecuta el instalador y sigue las instrucciones para completar la instalación. Durante el proceso de instalación, selecciona los componentes que deseas instalar. Como mínimo, necesitas seleccionar el compilador de C/C++.

### 2. Crear un archivo de código:

- Crea un archivo con extensión .c que contenga el código fuente de tu programa en C. Puedes utilizar cualquier editor de texto para esto, como Notepad o Visual Studio Code.

Por ejemplo, crea un archivo llamado:

> ***mi_programa.c***

 y agrega el siguiente código de ejemplo:

```c
#include <stdio.h>

int main() {
    printf("¡Hola, mundo!\n");
    return 0;
}
```
### 3. Compilar el programa:

- Abre una ventana de línea de comandos (CMD) y navega hasta el directorio donde se encuentra tu archivo .c.

- Usa el comando gcc seguido del nombre del archivo fuente y el parámetro -o para especificar el nombre del archivo de salida ejecutable. Por ejemplo:

```sh
gcc mi_programa.c -o mi_programa.exe
```
Esto compilará el programa y generará un archivo ejecutable llamado mi_programa.exe.

### 4. Ejecutar el programa:

- Una vez que el programa se haya compilado correctamente, puedes ejecutarlo directamente desde la línea de comandos:

```sh
mi_programa.exe
```
Verás la salida del programa, que en este caso imprimirá "¡Hola, mundo!" en la consola.