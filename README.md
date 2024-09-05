# Ejercicio Jardin Digital - Parte 2

## 05/09

# Descripcion del caso:

Usted se encuentra nuevamente trabajando en su jardin digital,y se le ha solictado ampliar las capacidades del sistema.

Ahora debe ser capaz de almacenar las plantas, considerando el nombre (rosa, petulia, girasol) y la cantidad de dias que lleva sin regar (1, 2,.., n), hasta un maximo de 10 plantas (que es la capacidad que tiene su jardin actualmente). 

Ademas, se deben incluir las siguientes funcionalidades:
- Registrar una nueva planta
- Mostrar las plantas del jardin
- Buscar un planta en el jardin por su nombre
- Regar una planta
- Avanzar un dia

# Requisitos del sistema

1) Considere implementar un metodo (funcion) llamado "*diaSiguiente()*" que se encargara de aumentar en un dia, la cantidad de dias sin riego a **todas las plantas del jardin** 

2) Considere que, si una planta alcanza los 5 dias sin ser regada, esta se secara y morira. Simule esta accion eliminandola automaticamente del sistem.

3) Cuando riegue una planta, el contador de dias sin regar, debera regresar a cero. 

4) Implemente un menu por consola mediante el cual el usuario sea capaz de interactuar con el jardin.

# Sugerencia:

Para almacenar las plantas, podria utilizar una matriz que simule la siguietne tabla:

| Nombre  | Dias sin regar | 
|---------|----------------|
| Rosa    | 1              | 
| Petunia | 3              |
| Girasol | 2              | 


# Codigo de referencia

![Codigo](/carbon(1).png)