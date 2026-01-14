# Aplicación ordenamiento con el algoritmo de laq burbuja
---
## Descripción del algoritmo
El **algoritmo de la burbuja** (Bubble Sort) es una forma **simple e intuitiva de ordenar una lista**. Es ideal para principiantes porque imita una idea muy cotidiana: **comparar elementos vecinos y mover los más grandes hacia el final**, como burbujas que suben en el agua.

---

## Idea principal

* Tenemos una lista de valores (números, por ejemplo).
* Comparamos **dos elementos consecutivos**.
* Si están en el orden incorrecto, **los intercambiamos**.
* Repetimos este proceso varias veces hasta que la lista quede ordenada.

Con cada recorrido, el elemento más grande “flota” hasta el final de la lista.

---

## Ejemplo intuitivo

Supongamos la lista:

```text
[5, 3, 8, 4]
```

### Primer recorrido:

* Comparamos `5` y `3` → están mal → intercambiamos → `[3, 5, 8, 4]`
* Comparamos `5` y `8` → están bien → no hacemos nada
* Comparamos `8` y `4` → están mal → intercambiamos → `[3, 5, 4, 8]`

👉 El número **8** ya quedó en su lugar final.

### Segundo recorrido:

* Comparamos `3` y `5` → bien
* Comparamos `5` y `4` → mal → intercambiamos → `[3, 4, 5, 8]`

Ahora la lista ya está ordenada.

---

## Pasos del algoritmo

1. Recorre la lista desde el inicio hasta el final.
2. Compara cada par de elementos vecinos.
3. Si el primero es mayor que el segundo, intercámbialos.
4. Repite el proceso hasta que no sea necesario hacer más intercambios.

---

## ¿Por qué se llama “burbuja”?

Porque en cada pasada, el elemento más grande **sube** al final de la lista, igual que una burbuja sube a la superficie.

---

## Características importantes

* ✅ **Fácil de entender e implementar**
* ❌ **Poco eficiente para listas grandes**
* ⏱️ Complejidad temporal:

> * Peor caso: **O(n²)**
> * Mejor caso (ya ordenado, con optimización): **O(n)**

---

## ¿Cuándo usarlo?

* Para **aprender algoritmos de ordenamiento**
* Para listas pequeñas
* Para practicar conceptos como:

  * bucles
  * comparaciones
  * intercambio de valores

## Repositorio
[Repositorio de la aplicación](https://github.com/dgamarra/ordenamiento-burbuja.git)

![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

