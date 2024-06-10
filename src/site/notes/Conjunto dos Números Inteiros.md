---
{"dg-publish":true,"permalink":"/conjunto-dos-numeros-inteiros/","tags":["gardenEntry"]}
---

---
A partir do [[Conjunto dos Números Naturais\|Conjunto dos Números Naturais]] podemos construir o conjunto dos números inteiros.

Teorema: A relação ~ em $\mathbb N\times\mathbb N$ definida por $(a,b)$~$(c,d)$ quando $a+d=b+c$ é de equivalência.
  

Para a relação ~ vale as seguintes propriedades:

i) Reflexividade: $(a,b)$~$(a,b)$, pois $a+b=b+a$ para todo $(a,b)\in \mathbb N\times \mathbb N$.

  

ii) Simetria: $(a,b)$~$(c,d)\Rightarrow(c,d)$~$(a,b)$. 

Essa implicação equivale à implicação $a+d=b+c\Rightarrow c+b=d+a$, que decorre da comutatividade da adição em $\mathbb N$.  

iii) Transitividade: $(a,b)$~$(c,d)$ e $(c,d)$~$(e,f)\Rightarrow (a,b)$~$(e,f)$.

Se $(a,b)$~$(c,d)$ e $(c,d)$~$(e,f)$, então $a+d=b+c$ e $c+f=e+d$; daí $a+d+f=b+c+f$ e $c+f+b=e+d+b$, o que implica $a+d+f=e+d+b$ e portanto $a+f=e+b$, ou seja: $(a,b)$~$(e,f)$.
  

Logo ~ é uma relação de equivalência em $\mathbb N\times \mathbb N$ e, por conseguinte, determina uma partição neste conjunto em classes de equivalência. Para cada $(a,b)\in \mathbb N\times \mathbb N$. Assim:

  

$\overline{(a,b)}=${$(x,y)\in \mathbb N\times \mathbb N | (x,y)$~$(a,b)$}$=$

={$(x,y)\in \mathbb N\times \mathbb N | x+b=y+a$}

  

Definição: O Conjunto quociente $\mathbb N\times \mathbb N/$~, constituído pelas classes de equivalência $\overline{(a,b)}$, se denota por $\mathbb Z$ e será chamado de conjunto dos números inteiros.


Assim,

$\mathbb Z =(\mathbb N\times \mathbb N/$~)={$\overline{(a,b)} | (a,b)\in \mathbb N\times \mathbb N$}.

  
  
Observação: se admitirmos por um momento a nossa noção intuitiva de números inteiros e de subtração, notamos que $a+d=b+c\Leftrightarrow a-b=c-d$, isto é, dois pares ordenados são equivalentes segundo a definição acima, quando a diferença entre suas coordenadas, na mesma ordem, coincidem.