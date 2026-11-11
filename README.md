Simulador de Gestión y Asignación de memoria.

En él desarrollamos las partes/módulos necesarios para que los planificadores de Largo, mediano y corto plazo puedan gestionar el circuito de los procesos, para que, puedan ser finalmente procesados por la CPU.
Está demás decir que asumimos que el procesador es mononúcleo, por lo que el dispatcher con el algoritmo de planificación a corto plazo de Shortest Remaining Time First (SRTF) se encargará de elegir qué trabajo será el más conveniente para procesarse en cada instante de tiempo durante la simulación.
Cuenta con un menú interactivo que puede manejarse mediante las flechas de (arriba) y (abajo), fue pensado para que sólo se admitan 10 procesos en la simulación, mostrando la información de la ejecución mediante una interfaz gráfica utilizando las tablas de la librería RICH
El simulador fue enteramente escrito en python, y utiliza librerías con funciones pertenecientes a "Windows", por lo que es el único sistema operativo capaz de ejecutarlo desde el binario proporcionado en el repositorio.
