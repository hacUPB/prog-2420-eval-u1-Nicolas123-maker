# Pseudocódigos
### Problema 1.
- Ana quiere saber si ha aprobado sus exámenes finales. Tiene una lista de sus calificaciones y necesita calcular el promedio. Para aprobar, debe tener un promedio de al menos 3.0.
### Pseudocódigo
```
   Inicio
     Definir M como 0
     Definir K como 3.0
     Leer n
     Defina n = b
     Mientras n>0 entonces:
        Leer c
        M = M + c
        n = n-1
    Fin Mientras
    P = M/B
    If P >= k ;
      Print "Aprobaste!", P 
      Else; print "No aprobaste", p
    Fin If
   Fin
```

### Problema 2.
- María tiene un registro de las velocidades a las que ha conducido su vehículo y el tiempo que ha mantenido cada velocidad. Quiere calcular la distancia total recorrida.
### Pseudocódigo
```
   Inicio
     Defina D como 0
     Leer c
     Mientras c > 0;
       Leer v
       Leer t
       D = v*t + D
       C = C - 1
    Fin mientras
    Print "Has recorrido", D
   Fin
```
### Problema 3.
- Se desea saber cuántos años, meses y días tiene actualmente una persona, basándose en su fecha de nacimiento. Además, le gustaría saber si ya ha cumplido años este año o aún no, y si hoy es su cumpleaños para celebrarlo. Cada una de las fechas está conformada por 3 variables: día, mes y año
### Pseudocódigo
```
   Inicio
     Defina Día
     Defina Mes
     Defina año 
     Print "Escribe tu fecha de nacimiento:"
     Leer I
     Leer E
     leer Ñ
     F= Ñ - Año
     If Día= I and Mes= E;
       Print "Hoy cumples!", F "Felicidades!"
       Else;
       If Día< I and Mes< E;
           Print "Tu edad es:", F-1
           else;
           If Día> I and Mes> E ;
             Print "Tu edad es:", F
             Else;
            Fin If
        Fin If
     Fin If
   Fin 
```