![Logo](https://www.famaf.unc.edu.ar/documents/3253/Logo-FAMAF_UNC-color-2.jpg)
# FaMAF - Archivos
Este espacio está dedicado a recopilar y organizar el material usado durante la cursada de Licenciatura en Ciencias de la Computación y Matemática Aplicada.


## Clonar repositorio completo

Para clonar el repositorio entero con todas la materia ejecuta

```bash
git clone --recursive https://github.com/FaMAF-Material
```
## Clonar sub-repositorios
Abrir el repositorio y copiar la URL, luego ejecutar

```bash
git submodule add <URL_del_subrepositorio> <ruta_local_del_submódulo>
```
Despues de agregar el submódulo, podes agregar y actualizar de la siguiente manera

```bash
git submodule init
git submodule update
```

Para la clonación recursiva
```bash
git clone --recursive <URL_del_repositorio_principal>
```

