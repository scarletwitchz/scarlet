# Permutação

## <mark style="color:purple;">Regra</mark>

→ A ordem não importa. → n = p

## <mark style="color:purple;">Tipos de permutações</mark>

### Simples

* É o caso da **Fatorial**, quem já foi escolhido uma vez, não será escolhido de novo.
* Se Número de opções = Número de escolhas → Temos uma **permutação**.
* Permutação de n = n!
* <mark style="color:yellow;">Ex</mark>.: $$P_{5} = 5!$$&#x20;

→ <mark style="color:yellow;">Anagramas (com letras distintas) são permutações simples frequentes.</mark>

> Qual é o número possível de anagramas para a palavra **ADVENTO**? $$n = P_{7} = 7! = 7\times6\times5! = 42\times120 = 5040$$



#### Com restrições

> Qual o número possível de anagramas que comecem em **consoante** para a palavra ADVENTO? _Consoantes: D, V, N, T_ = 4 (número que vai no início)&#x20;

<figure><img src="https://i.imgur.com/m5NVzoy.png" alt=""><figcaption></figcaption></figure>



### Com Repetição

> Usadas quando um dos elementos do conjunto se repete.
>
> * n = número de elementos
> * r = número de repetições $$P^r_{n}=\frac{n!}{r!}$$

#### <mark style="color:yellow;">Exemplo</mark>

> → Anagrama com letras repetidas.&#x20;
>
> **ASTERISCO** = 9 letras → 9! ($$P_{9}$$)&#x20;
>
> S se repete = 2 letras → 2! ($$P_{2}$$)

$$P^2_{9} = \frac{9!}{2!} = \frac{9\times8\times7\times5\times4\times3\times{\cancel2!}}{{\cancel2!}} = 181440$$



#### <mark style="color:yellow;">Exemplo 2</mark>

> → Anagrama com ASSASSINAR.&#x20;
>
> **ASSASSINAR** = 10 letras → 10! ($$P_{10}$$)&#x20;
>
> A se repete = 3 letras → 3! ($$P_{3}$$)&#x20;
>
> S se repete = 4 letras → 4! ($$P_{4}$$)
>
> $$P_{10}^{3,4}=\frac{10!}{3!\times{4!}} = \frac{10\times{9}\times{8}\times{7}\times {\cancel6}\times 5\times {\cancel4!}}{{\cancel 4!}\times {\cancel3\times{\cancel2}}\times 1} = 25200$$

### Circular

#### Exemplo

$$PC_{n}=\frac{n!}{n} = (n-1)!$$

> 5 amigos vão a um restaurante e se sentam ao redor de uma mesa redonda de 5 lugares diferentes. De quantos jeitos eles podem se sentar?

$$PC_{n}=\frac{5!}{5}=4! = 24$$

