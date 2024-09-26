# 10  Un alumno desea saber cuál será su calificación final en la materia de Algoritmos. Dicha calificación secompone de los siguientes porcentajes:
## 55% del promedio de sus tres calificaciones parciales.
## 30% de la calificación del examen final.
## 15% de la calificación de un trabajo final.
1. Iniciar
2. Leer parcial
3. Si parcial no entre 1 y 10;
      Ir a 2

4. Calificación = Calificación + parcial
5. Contador = Contador ++
6. Si contador < 3;
      Ir a 2
7. Promedio = Calificacion / Contador  
8. Leer Nota_ExFinal
9. Si Nota_ExFinal no entre 1 y 10;
      Ir a 8
10. Leer Nota_TrFinal
11. Si Nota_TrFinal no entre 1 y 10;
      Ir a 10
12. Calcular NotaFinal = Promedio * 0.55 + Nota_ExFinal * 0.30 + Nota_TrFinal * 0.15
13. Mostrar NotaFinal

## Diagrama
<img src=img/Act10.png>

<a href=../README.md > Volver </a>
