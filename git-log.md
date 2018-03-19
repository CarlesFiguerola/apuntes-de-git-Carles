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
