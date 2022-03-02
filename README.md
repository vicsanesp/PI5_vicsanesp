head section

Integer getN()
Integer getM()
Integer getE(Integer i)
Integer getMU(Integer i)

Integer n = getN()
Integer m = getM()

goal section
min sum(x[i], i in 0 .. m)

constraints section -> para sumatorios
sum(getE(i) x[i], i in 0 .. m) = n
	siempre la variable a la derecha, el producto es el espacio en blanco
bounds section -> para cuando no haya sumatorios
x[i] <= getMU(i), i in 0 .. m
	en las inecuaciones la variable siempre a la izquierda, evitar operaciones, aunque sean sencillas utilizar metodos que las hagan
int
x[i], i in 0 .. m
