## O que é NumPy?
NumPy, abreviação de "Numerical Python", é uma biblioteca em Python voltada para computação científica. Essencial para manipulação eficiente de dados numéricos, oferece suporte a arrays multidimensionais e funções matemáticas de alto desempenho. 

Criada em 2005 por Travis Oliphant, é um projeto de código aberto, sendo parcialmente implementada em Python, mas a maioria das partes computacionalmente intensivas é escrita em C ou C++.

## Por que usar Numpy?
Em Python, as listas são frequentemente usadas como arrays, porém, sua velocidade de processamento é limitada. 

O NumPy visa oferecer um objeto array até 50 vezes mais rápido do que as listas Python convencionais.

Denominado ndarray, o objeto array do NumPy proporciona uma variedade de funções de suporte que simplificam a manipulação de dados. 

Arrays são amplamente empregados na ciência de dados, destacando-se pela sua velocidade e eficiência computacional.

## Por que o NumPy é mais rápido que Listas?
Os arrays do NumPy são armazenados de maneira contínua na memória, ao contrário das listas, possibilitando que os processos acessem e manipulem esses arrays de maneira muito eficiente. 

Na ciência da computação esse comportamento é conhecido como "localidade de referência". Essa é a principal razão pela qual o NumPy é mais rápido do que as listas. 

Além disso, as operações no NumPy são executadas de maneira vetorizada, o que implica que várias operações são realizadas simultaneamente, resultando em desempenho mais eficiente em comparação com os loops em Python puro usados em listas.
