# Trabajo Práctico Nº1 - Programación Orientada a Objetos en Python

Este repositorio contiene el desarrollo de la primera actividad de la materia **Programación Avanzada para Ciencia de Datos (2° cuatrimestre 2025)**.  
El objetivo fue implementar conceptos básicos de **Programación Orientada a Objetos (POO) en Python** a través de la creación y manipulación de clases.

---

## Contenido desarrollado

1. **Clase `Persona`**
   - Atributos: `_nombre` y `_edad`.
   - Método `mostrar()`: imprime un mensaje con el nombre y la edad de la persona.
   - Se crean cinco instancias de la clase para mostrar datos del equipo.

2. **Validaciones en el constructor**
   - Se verifica que la edad sea un número entero.  
     - En caso contrario, se lanza una excepción `TypeError`.
   - Se verifica que la edad no sea negativa.  
     - En caso contrario, se lanza una excepción `ValueError`.
   - Se implementan casos de prueba con manejo de excepciones mediante `try-except`.

3. **Método `cumplir_anios()`**
   - Incrementa en 1 la edad de la persona.
   - El método `mostrar()` se modificó para indicar también el cumpleaños.

4. **Función externa `comparar_edades(persona1, persona2)`**
   - Recibe dos objetos `Persona` y determina cuál es mayor o si tienen la misma edad.

5. **Lista de personas**
   - Se crea una lista `lista_de_personas` con al menos cinco instancias.
   - Función `mostrar_lista(lista_de_personas)`: recorre la lista e invoca el método `mostrar()` de cada objeto.

---

## Archivos

- `TP1_POO.ipynb` → Notebook con el desarrollo completo de la consigna.  
- `README.md` → Explicación del contenido del repositorio.  

---

## Tecnologías utilizadas

- Lenguaje: **Python 3**  
- Entorno: **Jupyter Notebook**  

---

## Autor/es

Trabajo realizado en el marco de la asignatura **ASIG00202 - Programación Avanzada para Ciencia de Datos** (Universidad de la Ciudad, 2025).  

**Grupo 5HP**
- Antonio Martinez
- Enrique Vazquez
- Pablo Ciociano
- Paula Cochimano
- Matias Banchio
