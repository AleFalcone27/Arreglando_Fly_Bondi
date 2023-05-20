# Fixing-Flybondi's Web ✈️

### PROBLEMA
#### Mientras estaba completando el formulario para postularme a un puesto en la pagina de [Flybondi](https://flybondi.breezy.hr/p/0097a6a84e48/apply?token=2157224a6c21&source=Career%20Portal) empecé a toquetear un poco los textareas y logre esto: 
#### Van a tener que hacer un poco de zoom... 🔍


![img](problema.png)


#### y me tome el atrvimiento de solucionarlo... 

--------------------

### SOLUCIÓN 1️⃣
#### Fijar un max y min, width y height 

![img](minYmax.png)

#### - Con esta solución no solo conseguimos limitar el tamaño máximo sino también limitar el mínimo, es decir el usuario sigue teniendo la para modificar el textarea a su gusto pero siempre PERO dentro de unos límites fijados por el desarrollador. Como estamos utilizando medidas relativas 

### SOLUCIÓN 2️⃣
### Hacer uso de la propiedad resize de los textareas.

![img](none.png)

#### - Con esta solución directamente no le permitimos al usuario y por ende evitamos la posibilidad de que pueda romperse el layout