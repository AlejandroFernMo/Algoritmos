# 20 Diseñar un algoritmo que nos diga el dinero que tenemos (en euros y céntimos) después de pedirnos cuantas monedas tenemos (de 2€, 1€, 50 céntimos, 20 céntimos o 10 céntimos)
1. Iniciar
2. Leer 2e
3. Leer 1e
4. Leer 50c
5. Leer 20c
6. Leer 10c
7. Calcular calderilla = 50c * 50 + 20c * 20 + 10c *10
8. Si calderilla >= 100; <br>
&nbsp;&nbsp;&nbsp;&nbsp; calderilla = calderilla - 100; <br>
&nbsp;&nbsp;&nbsp;&nbsp;1e = 1e + 1;<br>
&nbsp;&nbsp;&nbsp;&nbsp;Ir a 8
9. Calcular capital = 2e * 2 + 1e  
11. minM = minM + Min
12. Si minM >= 60;<br>
15. Mostrar Mensaje + capital + calderilla
16. Fin

## Diagrama
<img src=img/Act20.png>

<a href=../README.md > Volver </a>
