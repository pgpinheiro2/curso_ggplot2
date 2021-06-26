# Minicurso R: ggplot2

Notas do minicurso sobre o pacote `ggplot2` do `R` a ser ministrado para servidores públicos na Universidade Federal do Amapá. No entanto, nada impede, claro!, que outros públicos utilizem este material.

## Introdução

### Apresentação: [video](link)

### Instalação do pacote `ggplot2`
```{r setup, echo=T}
install.packages('ggplot2')
library(ggplot2)
# ou
require(ggplot2)
# Comando extra que agrupa os anteriores
# if(!require(ggplot2)==T){install.packages('ggplot2')};require(ggplot2)

```

## Base de dados `escolhida`
O R já vem instalado com diversas base de dados. Vamos escolher uma delas para aplicar nossos exemplos.

Com o comando `data()` podemos ver a relação de *datasets* no `R`.
```{r }
data()
```

## Exemplo 1: 
$f(x|\theta) = \frac{1}{\theta_2 - \theta_1} I_{(\theta_1,\theta_2)}(x)$

## Exemplo 2: 

## Exemplo 3: 

## Resumo Final: A gramática dos gráficos!

## Referências
Este curso está sendo elaborado com duas referências básicas. Usamos o livro *R for Data Science* dos autores *Wickham* e *Grolemund*. O outro material que usamos é da série *cheat sheet* do *RStudio*. Para nossa sorte, ambos estão acessíveis nos *links* a seguir.

![R for Data Science](https://d33wubrfki0l68.cloudfront.net/b88ef926a004b0fce72b2526b0b5c4413666a4cb/24a30/cover.png)

![Clique aqui para acessar ao livro!](https://r4ds.had.co.nz/)


![Data Visualization Cheatsheet](https://d33wubrfki0l68.cloudfront.net/21d683072b0c21cbd9b41fc0e37a587ad26b9525/cbf41/wp-content/uploads/2018/08/data-visualization-2.1.png)


### Anexos
- Instalação do `R` no windows: [![Passo-a-passo em inglês para instalação do R no Windows](http://img.youtube.com/vi/ZoPJGmpYJzw/0.jpg)](http://www.youtube.com/watch?v=ZoPJGmpYJzw "Como instalar o R no Windows")

#### Matemática básica no `R`
```{r }
# Soma:
1+2
# Subtração
5-2
# Multiplicação
3*4
# Potenciação
2^4
2**4
2^2^2^2
16^2^2
# Divisão
10/2
# Quociente da divisão; parte inteira
7%/%2
# Resto da divisão
7%%2
# Módulo
abs(-5)
abs(10)
# Logarítmo
log(10)
log(10,10)
log(1)
log(1,exp(1))
# Exponencial
exp(0)
exp(1)
# Pi
pi
# Funções Trigonométricas
sin(pi/2)
cos(pi)
tan(1/2)
tan(45*pi/180)
tan(pi/4)
# Fatorial
factorial(4)
4*3*2*1
# Combinações
choose(5,2)
5*4/factorial(2)
# Somatórios
x = 1:10
sum(x)
# Produtórios
prod(x)
```

