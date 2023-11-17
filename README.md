[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/ytCADFsI)

## Diferencia entre clase y objeto:

 La clase es como una plantilla o un molde que define cómo se deben crear los objetos. Los objetos son las instancias reales creadas a partir de esa clase, y tienen sus propias características y comportamientos específicos.

## Diferencia entre clase e Interfaz:

Una clase es una entidad que puede tener atributos y métodos con implementaciones concretas, mientras que una interfaz define un conjunto de métodos que deben ser implementados por cualquier clase que la adopte. Puede heredar de una sola clase (abstracta o no) mientras que una interfaz puede extender varias interfaces de una misma vez. Las interfaces proporcionan un mecanismo para lograr la abstracción y la implementación de múltiples herencias, ya que una clase puede implementar varias interfaces, pero solo puede heredar directamente de una sola clase. Una clase puede tener métodos que sean abstractos o que no lo sean, mientras que las interfaces sólo y exclusivamente pueden definir métodos abstractos.

## ¿Qué es poliformismo?

Se refiere a la capacidad de un objeto de tomar muchas formas, es decir, la capacidad de una función, operación o método de comportarse de diferentes maneras según el tipo de datos con el que se está trabajando.Ocurre cuando tenemos muchas clases que están relacionadas entre sí por herencia. 

- Ejemplo
  En nuestro proyecto se usa el método Obtener Calificación funciona dependiendo de si se usa en un curso o un diplomado. Cuando se usa en cursos solo se retorna la calificacion, pero en diplomados se suman los resultados de los cursos.

## ¿Qué representan las asocianes en un DC?

Una asociación es una relación estructural que describe una conexión entre objetos.
En un diagrama de clases, la asociación representa la relación semántica entre dos o más clases. Esta relación puede ser un vínculo estructural, un flujo de información o una dependencia entre objetos. Las asociaciones en un diagrama de clases se representan mediante líneas que conectan las clases involucradas, y a menudo incluyen información adicional para describir la naturaleza de la relación.

- Ejemplo
  Nuestra clase curso vive en la clase diplomado.

## Diferencia entre composición vs Agrupación

La principal diferencia entre composición y agregación radica en la fortaleza de la relación entre el objeto contenedor y los objetos contenidos. La composición implica una relación más fuerte, donde los objetos contenidos forman parte integral del objeto contenedor y no pueden existir de manera independiente. En cambio, en la agregación, los objetos contenidos pueden existir de forma independiente y su relación con el objeto contenedor es más flexible.

## ¿Qué es encapsulamiento? ¿Qué ventaja representa?

El encapsulamiento se refiere a la idea de reunir los datos (atributos) y los métodos (funciones) que operan sobre esos datos en una única unidad llamada clase. Además, el encapsulamiento también implica ocultar los detalles internos de la implementación de una clase y proporcionar una interfaz clara y controlada para interactuar con esa clase desde el exterior. Contribuye a la creación de código más seguro, modular y mantenible al proporcionar un control más estricto sobre el acceso a los datos y al facilitar la evolución y la flexibilidad en el desarrollo.

- Ejemplo
  Los datos básicos de los alumnos estan encapsulados en una sola clase y estan declarados de forma privada.


## ¿De qué manera se representa la modularidad en POO?

Se logra mediante la creación de clases y objetos que encapsulan funcionalidades específicas, proporcionan interfaces controladas, utilizan la herencia y la abstracción para organizar el código de manera estructurada y fomentan la reutilización y la mantenibilidad del software.



## Considera poliformismo ¿Cuál es la diferencia de usar Herencia Vs Interfaces? Ventajas y Desventajas.

- Ventajas:
### Herencia

Reutilización de Código: Permite la reutilización de código al heredar atributos y métodos de una clase base.
Jerarquía de Clases: Facilita la organización de clases en una jerarquía, donde las clases derivadas pueden especializar o extender el comportamiento de la clase base.
Acceso a Datos y Métodos: Las clases derivadas tienen acceso a los datos y métodos protegidos y públicos de la clase base.

-Desventajas:

Jerarquía Rígida: Puede llevar a una jerarquía rígida y acoplada, ya que las clases derivadas están fuertemente vinculadas a la implementación de la clase base.
Problemas de Diseño: La herencia puede llevar a problemas de diseño como la herencia múltiple (en lenguajes que lo admiten) y la dificultad de mantenimiento cuando cambian las clases base.
Complejidad: A medida que la jerarquía crece, la complejidad puede aumentar, haciendo que el código sea más difícil de entender y mantener.

### Interfaces:

-Ventajas:

Desacoplamiento: Las interfaces permiten el desacoplamiento, ya que una clase puede implementar varias interfaces sin estar limitada por una jerarquía de clases.
Flexibilidad: Proporciona flexibilidad al permitir que las clases implementen múltiples interfaces, lo que es útil cuando una clase necesita proporcionar funcionalidades de varias fuentes.
Mejor Soporte para el Cambio: Al no depender de una jerarquía de clases, las interfaces pueden ser más flexibles y fáciles de adaptar a cambios en los requisitos.

-Desventajas:

Sin Implementación: Las interfaces no pueden contener implementaciones de métodos, lo que significa que todas las clases que implementan una interfaz deben proporcionar su propia implementación.
Menos Reutilización: En comparación con la herencia, puede haber menos reutilización de código, ya que las clases no heredan automáticamente la implementación de métodos.
Complejidad en Implementaciones Múltiples: Cuando una clase implementa múltiples interfaces, puede aumentar la complejidad y requerir una mayor atención a la consistencia de la implementación.
