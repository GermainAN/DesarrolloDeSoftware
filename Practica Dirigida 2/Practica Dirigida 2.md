# Practica Dirigida 2

# **Descarga y guarda el script**

![image.png](image.png)

# **Asignar permisos de ejecución**

![image.png](imagen/image%201.png)

![image.png](imagen/image%202.png)

# **Opción: agregar un submódulo**

![image.png](imagen/image%203.png)

![image.png](imagen/image%204.png)

# **Opción: Gestión de ramas (Opción 4)**

![image.png](imagen/image%205.png)

![image.png](imagen/image%206.png)

# Crear un hook pre-commi

![image.png](imagen/image%207.png)

# **Finalizar la sesión**

![image.png](imagen/image%208.png)

# Preguntas

**1. ¿Qué diferencias observas en el historial del repositorio después de restaurar un commit mediante reflog?**

El historial muestra que el HEAD ha sido movido a un estado anterior, permitiendo recuperar commits perdidos o revertir cambios recientes. Esta operación es local y no afecta el historial compartido con otros colaboradores.

**2. ¿Cuáles son las ventajas y desventajas de utilizar submódulos en comparación con subtrees?**

- **Submódulos:**
    - *Ventas:* Permiten mantener una relación clara con repositorios externos, facilitando actualizaciones independientes.
    - *Desventajas:* Requieren pasos adicionales para clonar y actualizar, lo que puede complicar la gestión.
- **Subtrees:**
    - *Ventajas:* Integran el código externo directamente en el repositorio principal, simplificando su uso.
    - *Desventajas:* La sincronización con el repositorio original puede llegar a  ser más compleja.
**3. ¿Cómo impacta la creación y gestión de hooks en el flujo de trabajo y la calidad del código?**

Los hooks automatizan tareas como validaciones y pruebas antes de commits o pushes, asegurando que solo código que cumple con ciertos estándares se integre al repositorio. Esto mejora la calidad del código y reduce errores en etapas tempranas del desarrollo.

**4. ¿De qué manera el uso de git bisect puede acelerar la localización de un error introducido recientemente?**

`git bisect` realiza una búsqueda binaria entre commits para identificar rápidamente el punto exacto donde se introdujo un error, reduciendo significativamente el tiempo de diagnóstico.

**5. ¿Qué desafíos podrías enfrentar al administrar ramas y stashes en un proyecto con múltiples colaboradores?**

Los principales desafíos incluyen la posibilidad de conflictos al aplicar stashes en ramas actualizadas por otros, dificultad para rastrear cambios temporales y la necesidad de una coordinación efectiva para evitar sobrescribir el trabajo de otros colaboradores.


# **Ejercicios**

## Extiende el menú de gestión de ramas para incluir la funcionalidad de renombrar ramas.

![image.png](imagen/image%209.png)

![image.png](imagen/image%2010.png)

## Amplia la sección de "Gestión de git diff" para permitir ver las diferencias de un archivo específico entre dos commits o ramas.

![image.png](imagen/image%2011.png)

# Crea una función que permita instalar automáticamente un hook que, por ejemplo, verifique si se han agregado comentarios de documentación en cada commit.

![image.png](imagen/image%2012.png)

![image.png](imagen/image%2013.png)

# Implementa una opción en el script que realice un merge automatizado de una rama determinada en la rama actual, incluyendo la resolución automática de conflictos (siempre que sea posible).

![image.png](imagen/image%2014.png)

![image.png](imagen/image%2015.png)