## 🆘 VIM

### modo comando 👉🏼 esc
- **j** bajar una linea
- **k** subir una linea
- **h** espacio a la izquierda
- **l** espacio a la derecha
- **w** una palabra a la derecha
- **b** una palabra a la izquierda
- **^** comienzo de linea 
- **$** final de linea

#### eliminar
- **x** elimina un caracter
- **dw** elimina una palabra
- **dd** elimina una linea
- **D** elimina desde posicion actual del cursor

#### reemplazar
- **r** reemplaza caracter
- **cw** reemplaza una palabra
- **cc** reemplaza linea
- **C** reemplaza desde posicion actual del cursor
- **~** invierte mayusculas y minisculas de un caracter

#### copiar
- **yy** copiar linea completa
- **p** pegar el ultimo texto copiado o eliminado

#### buscar
- **/patron** busca hacia adelante
- **n** siguiente resultado
- **N** resultado anterior
- **?patron** busca hacia atras

### modo insercion 👉🏼 i
- **i** inserta en posicion actual del cursor
- **I** inserta al comienzo de la linea
- **a** adjunta después de posicion actual del cursor
- **A** adjunta al final de linea

### modo de linea 👉🏼 :
- **:w** guarda cambios 
- **:w!** guarda cambios de manera forzada
- **:q** salir de vim
- **:q!** salir sin guardar
- **:wq!** guardar y salir de vim
- **:n** ubicar cursor en linea indicada
- **:$** ubicar cursor en ultima linea
- **:set nu** habilitar numeracion de lineas
- **:setnonu** deshabilitar numeracion de lineas
