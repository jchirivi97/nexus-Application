# nexos-Application


### Prueba de Conocimiento Desarrollador Java
  La empresa Nexos Software requiere desarrollar un sistema de inventario para el sector
  automotriz donde se controle la mercancía que ingresa y la que sale. El sistema debe permitir
  registrar nueva mercancía, editar y eliminar.
  Para registrar mercancía nueva se requiere tener en cuenta los siguientes datos: Nombre
  producto, cantidad, fecha de ingreso, usuario que realiza registro. Restricciones: no puede haber
  mas de una mercancía con el mismo nombre, la cantidad debe ser un número entero, la fecha de
  ingreso debe ser menor o igual a la fecha actual.
  Para editar mercancía se deben tener las mismas condiciones de cuando se registra una nueva,
  aparte hay que registrar el usuario que hace la modificación y la fecha.
  Para eliminar mercancía, solo lo puede hacer el usuario que la registró.
  El sistema también debe permitir mostrar por pantalla la mercancía registrada, los filtros de
  búsqueda pueden ser por fecha, usuario y/o nombre (se debe buscar mínimo por un filtro).
  Los usuarios que pueden ejecutar las acciones deben estar registrados con su nombre, edad, cargo
  y fecha de ingreso a la compañía.
  Los posibles cargos son, Asesor de ventas, administrador y soporte, con la posibilidad de que se
  creen nuevos cargos a futuro.
Nota: No es necesario contar con un login para saber que usuario está realizando las acciones, en
cada acción se puede elegir el usuario (previamente creados en BD) en un menú desplegable.

### Elaborado
- Jimmy Armando Chirivi Nivia

### Tecnología

Backend

- Java 8
- Spring framework, Spring data, Spring web
- BD PostgreSQL
- Maven

FrontEnd
 - Vuejs
 - Axios

### Repositorios 

- Backend: https://github.com/jchirivi97/nexus-backend
- FrontEnd: https://github.com/jchirivi97/nexus-front
