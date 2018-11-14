# PuntoFijo

Este método resuelve sistemas de ecuaciones no necesriamente lineales. Al igual que los otros métodos, se puede utilizar para determinar raíces de una función, siempre y cuando se cumplan los criterios de convergencia.
Para que converja, la derivada debe de ser menor que 1 en magnitud
"Un número a tal que a = g(a)"
Pasos:
1. Se ubica la raíz de la función
2. Se despeja (x = g(x))
3. derivas g(x)
4. Obtienes el rango de valores en los cuales está el punto fijo "R"
5. Con "R" se busca la raíz en g(x) --> g(R) = R

Después de las iteraciones que se necesiten, se obtiene la raíz

En el código se tiene en 0 el primer término al igual que el siguiente. Se hace un ciclo de tipo for con un rango de 100 para que alcance a hacer las iteraciones necesitadas con el error que se indico, en este caso 0.001
El siguiente valor, o sea x1 sera la función evaluada en el primer termino(x0) el cual al principio es 0 y después de obtener el error, se iguala a x1 dependiendo de si logró o no logró el error deseado 
