# Reto3
Algoritmo para hayar numeros primos hasta n.
### Pseudocodigo
        n=Numero entero
        Para n en rango (1,n)
        	Si n>= 1  y n es un numero primo 
        		i=2
        		Mientras (i<n) hacer
        			n%i
        			Si n%i==0
        				n no es un numero primo
        			i+=1
        		Si n es un numero primo
        			Escribir n
    
        A(Inicio) --> B[n=Numero entero]
    B --> C[Para n hasta que i=n]
    C -->D[i=2]
    D -->E[Mientras i < n hacer]
    E -->F{Si n%i==0}
    F -->|si| G[n no es un numero primo]
    F --> |no|I[es un numero primo]
    G -->J
    I --> J[i+=1]
    J -->E
    E -->K[Escribir numeros primos]
    K -->L(Fin)
    
