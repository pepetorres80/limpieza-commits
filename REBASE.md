## Rebase interactivo

Durante esta práctica se realizó una limpieza del historial de commits utilizando el comando:

```bash
git rebase -i HEAD~3
```

### Estado inicial:
El repositorio tenía tres commits con mensajes poco descriptivos:
- "Arreglos"
- "Cambios"
- "Actualización de cosas"

### Objetivo:
- Fusionar los tres commits en uno solo más significativo.
- Mejorar la claridad y profesionalidad del historial.

### Acciones realizadas:
- Se utilizó `reword` para editar el mensaje del primer commit.
- Se usó `squash` para combinar los otros dos commits en el primero.
- Se editó el mensaje final y se dejó como:

```
feat: Añadido contenido completo al archivo.txt (Hola Mundo!)
```

### Resultado:
El historial quedó con un único commit bien documentado, lo cual facilita el mantenimiento y revisión del código en entornos colaborativos.
