# actividad 7
---
[Link: Repositorio de Actividad 7](https://github.com/GermainAN/ACtividad7.git)
---
# 1. configuramos la carpeta de trabajo

![image.png](imagen/image.png)

## 2. Se crea la carpeta de entorno virutal de pyhton

![image.png](imagen/image%201.png)

## 3. Para ejecutar pruebas `behave`

busca los archivos `.feature` dentro de la carpta `feature`  y ejecutrar los escenarios

## **Ejercicio 1: Añadir soporte para minutos y segundos en tiempos de espera**

## 1. **Modifica** la función que maneja el tiempo de espera en `steps.py`

- primero modficiamos el `pattern`
    - modificando el regex, para  que recnosca los minutos

![image.png](imagen/image%202.png)

- aemas agregamos

![image.png](imagen/image%203.png)

![image.png](imagen/image%204.png)

## 2. Implementando un escenario de preuba

![image.png](imagen/image%205.png)

![image.png](imagen/image%206.png)

## 3. implementacion de test

![image.png](imagen/image%207.png)

## 4. ejecutamos el test

![image.png](imagen/image%208.png)

## 5. Integracion de Pipeline  CI/CD

![image.png](imagen/image%209.png)

![image.png](imagen/image%2010.png)

# Ejercicio 2

1. **Modifica** el sistema (la clase `Belly` y los steps en Behave) para que acepte entradas como `"0.5"`, `"2.75"`.

![image.png](imagen/image%2011.png)

1. **Implementa** un nuevo escenario en Gherkin donde se ingiera una cantidad fraccionaria y verifica el comportamiento.

![image.png](imagen/image%2012.png)

1. **Valida** que el sistema lance una excepción o error si se ingresa una cantidad negativa de pepinos.

![image.png](imagen/image%2013.png)

1. **Pruebas unitarias**:
    - Cubre el caso de pepinos fraccionarios en `test_belly.py`.
    - Cubre también el caso de pepinos negativos (se espera un error).

![image.png](imagen/image%2014.png)

![image.png](imagen/image%2015.png)

![image.png](imagen/image%2016.png)

# Ejercicio 3

1. **Modifica** el parsing de tiempo para que reconozca palabras clave en inglés, además de español (por ejemplo, `"two hours"`, `"thirty minutes"`).
    1. acutalizamos la funcion `convertir_palabra_a_numero`  para el ingles 
    
    ![image.png](imagen/image%2017.png)
    
     b. actualizamos el `step_when_wait_time_description`
    
    ![image.png](imagen/image%2018.png)
    
2. **Escribe** al menos dos escenarios de prueba en Gherkin que usen tiempos en inglés.
    
    ![image.png](imagen/image%2019.png)
    

![image.png](imagen/image%2020.png)

![image.png](imagen/image%2021.png)

# Ejercicio 4

1. **Crea** una función que, dada una expresión como "entre 1 y 3 horas", devuelva un valor aleatorio entre 1 y 3 horas.
    
    ![image.png](imagen/image%2022.png)
    
2. **Implementa** un escenario en Gherkin que verifique que, tras comer pepinos y esperar un tiempo aleatorio, el estómago puede gruñir.
    
    ![image.png](imagen/image%2023.png)
    
3. **Imprime** (en consola o logs) el tiempo aleatorio elegido para que el resultado sea rastreable en tu pipeline.

![image.png](imagen/image%2024.png)

![image.png](imagen/image%2025.png)

# Ejercicio 5

![image.png](imagen/image%2026.png)

![image.png](imagen/image%2027.png)

![image.png](imagen/image%2028.png)