Proyecto BIBLIOTECA VIRTUAL
Este proyecto forma parte del programa Oracle Next Education y Alura Latam. El objetivo es proporcionar una experiencia práctica en el rol de desarrollador back-end, desarrollando una aplicación que gestione una biblioteca virtual. La aplicación estará conectada a una base de datos relacional y permitirá aplicar conocimientos avanzados de Java y Spring, como el consumo de APIs externas y la persistencia de datos.

Requisitos
Para ejecutar este proyecto necesitas:

*Java 11 o superior
*Spring Framework
*Una base de datos configurada (en este caso PostgreSQL)

Funcionalidades
El programa incluye las siguientes funcionalidades:

Buscar libros por título: Realiza una búsqueda en una API externa y guarda el libro en la base de datos si es encontrado.
Mostrar libros registrados: Lista todos los libros almacenados en la base de datos.
Mostrar autores registrados: Lista todos los autores almacenados en la base de datos.
Mostrar autores por periodo: Lista los autores que estuvieron activos en un periodo específico.
Listar libros por género: Muestra los libros almacenados en la base de datos según su género literario.
Repositorios
Los repositorios utilizados son:

LibroRepository: Interfaz para las operaciones CRUD sobre los libros.
AutorRepository: Interfaz para las operaciones CRUD sobre los autores y consultas personalizadas.
