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
1+3
10+2

# Subtração:
5-2
10-2
2-10

# Multiplicação;
2*3
7*4

# Potenciação
2^3
4^4
2**3
4**4

# Divisão;
8/2
10/3

# Quociente da divisão; parte inteira: %/%
10%/%3

# Resto da divisão: %%
10%%3

# Módulo:
abs(-3)
abs(8)
abs(-10)

# Logarítmo:
log(2)
log(2,10)
log10(2)
?log
help(log)
log(2,exp(1))
log

# Exponencial:
exp(1)
exp(3)
exp(0)

# Pi
pi

# Funções Trigonométricas:
?sin
sin(pi/2)
sinpi(1/2)
cos(pi/2)
cos(pi)
cos(0)
tan(pi/4)
sin(pi/4)/cos(pi/4)

# Fatorial:
factorial(4)
4*3*2*1

# Combinações:
choose(10,2)
10*9/factorial(2)
factorial(10)/(factorial(10-2)*factorial(2))

# Somatórios:
x = 3:13
x
sum(x)
cumsum(x)
max(cumsum(x))
x |> cumsum() |> max()

# Produtórios:
x |> prod()
prod(x)
```

