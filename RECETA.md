# Receta: Guardar los números pares

1. Mostrar mensaje de bienvenida
2. totalPares ← __0____
3. contador ← __0____
4. MIENTRAS contador ___<___ CANTIDAD HACER
       numero ← leerEntero("_Ingera un nuemero_")
       SI numero __/2==0____ ENTONCES
           pares[__total pares____] ← numero
           totalPares ← ____totalPares+1__
       FIN SI
       contador ← __contador+1____
   FIN MIENTRAS
5. Mostrar "Pares encontrados: " y __totalPares____
6. i ← 0
7. MIENTRAS i <totalPares   HACER
       Mostrar pares[i]
       i ← _i+1_____
   FIN MIENTRAS