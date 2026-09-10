<p align="center">
    <img height="256px" src="https://raw.githubusercontent.com/NicoBenialgo/Ejercicios-Lenguajes1-UNAHUR/refs/heads/main/header-S01ejercicios.png" alt="Guía de ejercicios - Semana 1 // Lenguajes Informáticos 1 (UNAHUR)" />
</p>

<h1 align="center">Resolución de ejercicios opcionales</h1>

<p align="center">En este repositorio se encontrará el problema y la solución de cada punto especificado en el archivo que se adjuntó desde el Campus Universitario. Son un total de 10 ejercicios que tendrá planteado tanto el problema como la resolución elegida en el lenguaje peticionado.</p>

# Condiciones de la actividad

Herramientas       | Info              | Value (example)
-----------------: | :-----------:     | ---------------
Visual Studio Code | Editor de código  | `code.visualstudio.com`
Live Server        | Compilador        | (extensión de VSC)
Codepen (opcional) | Editor de código  | `codepen.io`
XML Validation     | Validador XML     | `xmlvalidator.com`
The JSON Validator | Validador JSON    | `jsonlint.com`

> [!NOTAS]
>
> - Si aún observás esta nota, es porque el trabajo no ha sido subido.
> - Si observas algún error dentro de este repositorio, favor de avisarme a mi cuenta de Discord [![Cuenta personal de Discord](https://img.shields.io/discord/930763773109735484?color=5865F2&label=Cuenta%20personal%20de%20Discord&logo=discord&logoColor=white)](https://discord.gg/weskerdetemu).


1. EJERCICIO 1 (Un libro en XML) - Creá un archivo XML que represente la información de un libro. El documento debe incluir los siguientes datos:
   * Título
   * Autor
   * Año de publicación
   * Género

Acordate de incluir la declaración XML al inicio (`<?xml version="1.0" encoding="UTF-8"?>`) y de elegir nombres de etiquetas descriptivos en español. Una vez creado el archivo, abrilo en el navegador. Si el XML es bien formado, el navegador lo muestra con colores. Si hay un error, te indica en qué línea está.

2. EJERCICIO 2 (Menú de un restaurante) - Creá un documento XML que represente la estructura del menú de un rstaurante. El menú debe tener las siguientes secciones, cada una con al menos dos ítems:
    * Entradas
    * Platos principales
    * Postres
    * Bebidas
  
Cada ítem del menú debe tener al menos: nombre y precio. Si querés agregar descripción o si es vegetariano, mejor todavía. Pensá bien como estructurás la jerarquía: ¿el menú es el elemento raíz? ¿Cómo agrupás las secciones? ¿Usás atributos o subelementos para el precio?

3. EJERCICIO 3 (Encontrá el error) - El siguiente fragmento XML tiene un error de estructura. Encontralo y corregilo.

    
    ```toml
    <estudiante>
        <nombre>Pablo Rodriguez</nombre>
        <edad>21</edad>
        <carrera>Ingeniería en Informática</carrera>
        <cursos>
            <curso>Matemáticas</curso>
      	    <curso>Física</curso>
        </estudiante>
    </cursos>
    ```

Una vez que lo corrijas, pegá el XML en el navegador para verificar que ya no haya errores. Pista: el error es de anidamiento — alguna etiqueta no se cerróen el órden correcto.

4. EJERCICIO 4 (Tienda en línea) - [terminar en breve...]
