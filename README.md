# Repo para EIEC - DevOps - UNIR

Este repositorio nos servirá para demostrar el uso de Git en la asignatura de EIEC y muchas cosas mas.

---

Los comandos del Makefile funcionarán en Linux y MacOS. En caso de usar Windows, necesitarás adaptarlos o ejecutarlos en una máquina virtual Linux.

## Ejecución

python3 main.py <filename> <dup>
  filename: **ruta** al fichero que contiene la lista de palabras, una por línea
  dup: **yes|no**, yes para eliminar palabras duplicadas, no para mantener la lista


## 📂 Prueba con archivo `words.txt`

Se ha creado un archivo `words.txt` con el siguiente contenido:

```
manzana
pera
banana
kiwi
manzana
uva
melon
banana
sandía
piña
```

Este archivo se colocó en el mismo directorio que el script `main.py`.

---

## 🚀 Ejecución del script

### ✅ Eliminar duplicados (`yes`)

```bash
(3.11.6) srega@GRAD0407UBUNTU:~/Documentos/UNIR/CICD/practicaUnirCICD$ python3 main.py words.txt yes
Se leerán las palabras del fichero palabras.txt
['banana', 'kiwi', 'manzana', 'melon', 'pera', 'piña', 'sandía', 'uva']
```

### ❌ Conservar duplicados (`no`)

```bash
(3.11.6) srega@GRAD0407UBUNTU:~/Documentos/UNIR/CICD/practicaUnirCICD$ python3 main.py words.txt no
Se leerán las palabras del fichero palabras.txt
['banana', 'banana', 'kiwi', 'manzana', 'manzana', 'melon', 'pera', 'piña', 'sandía', 'uva']
```