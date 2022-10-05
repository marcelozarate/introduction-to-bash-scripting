# Comentarios en Bash

Como con cualquier otro lenguaje, usted puede añadir comentarios a su script. Los comentarios se utilizan para dejar notas a lo largo del código.

Para hacerlo, necesita agregar el símbolo `#` al comienzo de la línea. Los comentarios nunca se mostrarán por pantalla.

Aquí hay un ejemplo de comentario:

```bash
# Este es un comentario y no será mostrado en pantalla
```

Ahora continuemos y agregemos algunos comentarios a nuestro script:

```bash
#!/bin/bash

# Preguntar por el nombre del usuario

read -p "¿Cuál es su nombre? " nombre

# Saludar al usuario
echo "Hola $nombre"
echo "¡Bienvenido a DevDojo!"
```

Los comentarios son una gran manera de describir algunas funcionalidades complejas directamente en sus scripts, de manera tal que otras personas puedan recorrer su código con facilidad.
