# 17 Un ciclista parte de una ciudad A a las HH horas, MM minutos y SS segundos. El tiempo de viaje hasta llegar a otra ciudad B es de T segundos. Escribir un algoritmo que determine la hora de llegada a la ciudad B.
1. Iniciar
2. Leer Horas
3. Leer Min
4. Leer Seg
5. Leer TiempoSeg
6. TiempoSeg = TiempoSeg + Seg
7. Si TiempoSeg >= 60;<br>
&nbsp;&nbsp;&nbsp;&nbsp; minM = TiempoSeg / 60; <br>
&nbsp;&nbsp;&nbsp;&nbsp;TiempoSeg = TiempoSeg % 60;
8. minM = minM + Min
9. Si minM >= 60;<br>
&nbsp;&nbsp;&nbsp;&nbsp; horasM = minM / 60; <br>
&nbsp;&nbsp;&nbsp;&nbsp;minM = minM % 60;
10. Horas = Horas + horasM
11. Si Horas >= 24;<br>
&nbsp;&nbsp;&nbsp;&nbsp; Horas = Horas - 24;<br>
&nbsp;&nbsp;&nbsp;&nbsp; Ir a 11;
12. Mostrar Mensaje + Horas + minM + TiempoSeg
13. Fin

## Diagrama
<img src=img/Act17.png>

<a href=../README.md > Volver </a>
