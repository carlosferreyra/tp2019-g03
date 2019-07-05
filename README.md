# TP Final 2019 - Grupo 3 - Administración de Turnos

## Grupo 03
1. Albarenga, Joaquin
2. Cardozo, Edgar
3. Ferreyra, Carlos Eduardo
4. Medina, Pablo
5. Saravia, Matias
6. Zigaran, Elias Natan 

#### Funcionalidad de la Aplicación
La funcionalidad de la aplicacion es la Gestion de Turnos del Hospital de niños de la provincia de Resistencia, Chaco.

#### Arquitectura empleada
La Arquitectura empleada, como se mencionó anteriormente, se basa en el Modelo 
Cliente-Servidor, donde se pueden identificar 3 capas con 2 niveles. La capa superior visible 
al usuario final (FrontEnd), que representa el Cliente y el nivel superior; la capa intermedia 
donde se maneja la lógica de Negocio (BackEnd) en conjunto con la capa de Acceso a Datos, estos 2 últimos representan el Servidor o nivel inferior. 

#### Frontend: Javascript (JSX) - Biblioteca ReactJS
Para el desarrollo frontend, se decidió por la utilización del entorno de ejecución Node.Js en 
su versión 10.x recurriendo a la biblioteca de ReactJS. Ésta se encuentra diseñada para un 
desarrollo óptimo de las Interfaces web y los entornos donde el Usuario final va a consumir 
el servicio. Cabe añadir, se utilizó el complemento de desarrollo web Bootstrap.

#### Backend: PHP - Framework Laravel
Se llegó al acuerdo de utilizar PHP como lenguaje destinado al desarrollo backend, mediante la utilización del framework Laravel. Framework o complemento que simplifica la configuración y el modelado de la lógica de negocio en el backend.

#### Base de Datos: MySQL
La Base de Datos Utilizada para el soporte de este servicio es MySQL, tomando como criterio de elección su uso sin licencias comerciales bajo la edición Community y ahorrando costos de licencia para el Cliente.

#### Acceso a Datos: Eloquent (ORM)
El servicio realiza el acceso a datos a través de un ORM, Drivers y Controladores necesarios para acceder a una Base de Datos determinada y adaptable a otras tecnologías de Base de Datos. El servicio utiliza la ORM Eloquent del framework Laravel, que se 
implementa a través de su API desarrollada para ejecutarse en un entorno PHP, el cual permite el Mapeo de Objetos con las entidades relacionales de la Base de Datos. Dicha ORM se encuentra adaptada para usarse sobre Sistema Gestor de Base de Datos MySQL y las sentencias o QUERYS pertinentes a este.

#### Framework Frontend: ReactJS
ReactJS es una biblioteca JavaScript de código abierto diseñada para crear interfaces de usuario con el objetivo de facilitar el desarrollo de aplicaciones en una sola página (SPA). Es mantenido por Facebook y la comunidad de software libre. React intenta ayudar a los desarrolladores a construir aplicaciones que usan datos que cambian todo el tiempo. Su objetivo es ser sencillo, declarativo y fácil de combinar.


