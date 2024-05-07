# Base de Datos de Películas

Este es un programa en C para gestionar una base de datos de películas que permite cargar películas desde un archivo CSV, buscar películas por ID, género, década o combinaciones de género y década.

## Funcionalidades

1. **Cargar Películas**: Lee datos de películas desde un archivo CSV y las almacena en una estructura de datos. FUNCIONA BIEN.
2. **Buscar por ID**: Permite buscar y mostrar la información de una película por su ID. FUNCIONA BIEN.
3. **Buscar por Género**: Busca y muestra las películas de un género específico. FUNCIONA BIEN.
4. **Buscar por Década**: Muestra las películas de una década específica. FUNCIONA BIEN.
5. **Buscar por Década y Género**: Muestra las películas de un género en una década específica. FUNCIONA BIEN.

## Mejoramientos

Tal vez agrear algo mas al codigo para que su uso sea mas eficiente. Por ejemplo al momento de querer buscar algo por categorias y luego mostrarlo, tal vez implementar un agregado para asi no tener que volver al menú nuevamente.

## Ejecución del Programa

*Visita* [Repl.it](https://replit.com/@MAURAGONZALEZ2/Tarea-2-estructura-1#tarea2.c).
---
Dirigete a `Shell`

1. **Compilar el Programa**: Para compilar el programa, ejecuta el siguiente comando en tu terminal:

   ```bash
   gcc tdas/*.c tarea2.c -Wno-unused-result -o tarea2
   ```

2. **Ejecutar el Programa**: Una vez compilado, puedes ejecutar el programa con el siguiente comando:

   ```bash
   ./tarea2
   ```

## Ejemplo de Uso

Una vez ejecutado el programa, se mostrará un menú principal con las siguientes opciones:

1. Cargar Películas
   ```bash
   Ingrese su opción: 1
   ID: tt0111161, Título: The Shawshank Redemption, Año: 1994
   Director: Frank Darabont
   Genero: Drama
   Genero: Crime
3. Buscar por id
   ```bash
   Ingrese su opcion: 2
   Ingrese el id de la película : tt0111161
   ID: tt0111161, Título: The Shawshank Redemption, Año: 1994
   Director: Frank Darabont
   Genero: Drama
   Genero: Crime
5. Buscar por género
   ```bash
   Ingrese su opcion: 3
   Ingrese el genero: Comedy
   Pelicula(s) de == Comedy ==

    -Titulo: La vita è bella.
    ~Año: 1997.

    -Titulo: Back to the Future.
    ~Año: 1985.
7. Buscar por década
   ```bash
   Ingrese su opcion: 4
   Ingrese decada deseada, recuerde ingresar la decada completa (ejemplo; 1980): 1990
   Película(s) de la década  == 1990 ==:

    -Título: The Shawshank Redemption.
    ~Año: 1994.

    -Título: Schindler's List.
    ~Año: 1993.
9. Buscar por década y género
    ```bash
    Ingrese su opcion: 5
    Ingrese el género que quiere ver: Adventure
    Ingrese la década que quiere ver: 2010
    Peliculas de == Adventure == en la década == 2010 ==

    -Título: Inception.
    ~Año: 2010.

    -Título: Interstellar.
    ~Año: 2014.
11. Salir

Para utilizar las opciones 2 a 5, primero debes cargar las películas seleccionando la opción 1.

## Actividad INDIVIDUAL

Maura González Silva.
