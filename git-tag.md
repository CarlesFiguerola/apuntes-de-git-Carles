### git-tag
Lista de etiquetas en orden alfabético (se puede aplicar patrón para listar etiquetas específicas)

### patrones
git tag -l <"patrón">
ejemplo: git tag -l "v1*" <---- listará todas las etiquetas que comiencen por v1

### git tag -a <nombre etiqueta> -m <"mensaje etiqueta">

Etiqueta anotada. Se guardan en la base de datos de Git como objetos enteros. 
Contienen:
- checksum
- nombre del etiquetador
- correo electrónico
- fecha
- mensaje asociado 


