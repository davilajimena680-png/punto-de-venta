# Punto de Venta Dolores: TDD


## 1. Producto

Rojo: la prueba falla porque la clase `Producto` todavía no existe.

![Producto rojo](access/producto-rojo.png)

Verde: se crea `Producto` y la prueba pasa.

![Producto verde](access/producto-verde.png)

---

## 2. Dinero

Rojo: la prueba falla porque `Dinero` todavía no existe.

![Dinero rojo](access/dinero-rojo.png)

Verde: se implementa `Dinero` y la prueba pasa.

![Dinero verde](access/dinero-verde.png)

### Dinero como texto

Rojo: la prueba del formato de texto falla.

![Dinero texto rojo](access/dinero-texto-rojo.png)

Verde: se implementa la representación en texto y la prueba pasa.

![Dinero texto verde](access/dinero-texto-verde.png)

### Reto

![Dinero reto](access/dinero-reto.png)

---

## 3. Carrito

Rojo: la prueba falla porque `Carrito` todavía no existe.

![Carrito rojo](access/carrito-rojo.png)

Verde: se implementa `Carrito` y la prueba pasa.

![Carrito verde](access/carrito-verde.png)

### IVA

Rojo: la prueba del cálculo de IVA falla.

![Carrito IVA rojo](access/carrito-iva-rojo.png)

Verde: se implementa el cálculo de IVA y la prueba pasa.

![Carrito IVA verde](access/carrito-iva-verde.png)

### Existencias

Rojo: la prueba de control de existencias falla.

![Carrito existencias rojo](access/carrito-existencias-rojo.png)

Verde: se implementa el control de existencias y la prueba pasa.

![Carrito existencias verde](access/carrito-existencias-verde.png)

