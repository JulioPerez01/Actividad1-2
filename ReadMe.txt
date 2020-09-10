ordenaSeleccion - La función ordena los números en orden ascendente de un vector, 
		  compara el primer numero del vector con los demás números de 
		  este, si encuentra un numero menor al que ya tiene, lo remplazará
		  y seguirá comparando hasta encontrar el numero mas pequeño y 
		  posicionarlo en la primera posición, después se repiten los pasos 
		  hasta que todos los números están ordenados, la función requiere 
		  dos ciclos for anidados para funcionar de esta manera. Debido a 
		  esto, tiene una complejidad de O(n^2).

ordenaBurbuja - La función compara el numero en la posición n con el de la posición 
		n+1, si n es mayor, entonces intercambia posición con n+1, en el 
		caso contrario, los deja en el orden en que están y sigue comparando 
		los siguientes números, hasta que deja el número más grande al final. 
		Después vuelve a empezar, pero sin contar los números que ya dejo 
		hasta el final y así hasta ordenar todos. Esta función utiliza dos 
		for y tiene una complejidad de n(n+1/2), por lo cual al tomar el peor 
		de los casos seria  O(n^2).

ordenaMerge - La función ordena los números de un vector en orden ascendente, esta 
	      función hace uso de otras, con las cuales divide el vector en la mitad 
	      y vuelve a dividir las mitades hasta que solo tiene un número, para 
	      luego utilizar otra función para ordenar las mitades obtenidas y así 
	      hasta que todos los números se ordenan. Debido a que n se va dividiendo 
	      entre 2, y se recorre en n pasos por lo cual tiene una complejidad de 
	      O(n log(n)) 

busqSecuencial - La función hace una búsqueda en vector para encontrar si el número 
		 que ingresaron está en el vector y va comparando el numero ingresado 
	         con cada uno de los valores en el vector. Si está el   número 
		 ingresado regresa la posición, de lo contrario, regresara -1 .Debido 
		 a esto tiene una complejidad de O(n).

busqBinaria - La función solo funciona si el vector esta ordenado, si el vector cumple 
	      con esta característica, entonces la función obtiene el numero que esta 
	      a la mitad y lo compara con numero ingresado, si es menor, repite los 
	      pasos con la parte de abajo, de lo contrario repite los pasos con la 
	      parte de arriba, así hasta que encuentre el dato o la posición donde 
	      debería estar. Debido a esto, la complejidad de los datos es O(log(n)). 
 