### git log
Muestra el historial de commits

Muestra la salida del historial con el formato indicado
`git log --pretty=format:"%h - %an, %ar : %s"`  ---> 
%h ---> hash ---> ba2e659 
%an---> autor---> Carles Figuerola, 
%ar---> horario relativo ---> fa 26 minuts 
%s ---> mensaje del commit ---> Se eliminó el archivo preparar.md

Muestra el log después de la fecha indicada
`git log --after="2016-04-07"`
Muestra el log antes de la fecha indicada
`git log --after="2017-05-07"`
Muestra log combinado rango de horas
`git log  --before="2018-03-19 16:42:00" --after="2018-03-19 15:00:00"`

Agrega etiqueta al commit más reciente
`git log --decorate`

`git log --oneline`
Este comando nos muestra el historial en una sola línea por commit.       