# Título 1
## Título 2 
### Título 3 
#### Título 4
##### Título 5
###### Título 6

# Parágrafo
Bacon ipsum dolor amet meatball ball tip chuck chicken burgdoggen doner leberkas turkey rump kielbasa beef ribs pork chop jerky.

# Outro parágrafo com quebra de linha

Bacon ipsum dolor amet meatball ball tip chuck chicken burgdoggen doner leberkas turkey rump kielbasa beef ribs pork chop jerky.(Você tem que inserir dois espaços ao final do parágrafo. -->)  
Bacon ipsum dolor amet meatball ball tip chuck chicken burgdoggen doner leberkas turkey rump kielbasa beef ribs pork chop jerky.

# Ênfase

## Negrito
Meu nome é **Felipe Saban**.

## Negrito 2
Meu nome é __Felipe Saban__.

# Itálico I
Meu nome é *Felipe Saban*.
# Itálico II
Meu nome é _Felipe Saban_.
# Negrito e Itálico I
Meu nome é ***Felipe Saban***.
# Negrito e Itálico II
Meu nome é **_Felipe Saban_**.
# Riscado
Meu nome é ~~Felipe Saban~~.
# Citação
> Meu nome é Felipe Saban.
# Citação com Negrito e Itálico
# Negrito e Itálico I
> **Meu nome** é _Felipe Saban_.

# Linhas horizontais
## ex1
***  
--- 
## ex2
* * *
- - - 
## ex3
**********
__________
## ex4
___
____________
_ _ _

# Listas não-ordenadas 1
* Item 1
* Item 2
* Item 3
# Listas não-ordenadas 2
- Item 1
- Item 2
- Item 3
# Listas não-ordenadas 3
+ Item 1
+ Item 2
+ Item 3
# Listas não-ordenadas 4 com subitem
* Item 1
  * SubItem1
  * SubItem2
  * SubItem3
* Item 2
* Item 3
# Listas não-ordenadas 5 com espaçamento
+ Item 1

+ Item 2

+ Item 3
#Listas Ordenadas
## Listas ordenadas 1
1. Item 1
2. Item 2
3. Item 3
## Listas ordenadas 2
1. Item 1
1. Item 2
1. Item 3
## Listas ordenadas 3
7. Item 1
2. Item 2
10. Item 3
## Listas ordenadas 4 (Bota a barra invertida e coloca dois espaços ao final)
1994\. Brasil  
1998\. França  
2002\. Brasil  

# Links
## Links 1
[Clique aqui](http://www.google.com)
## Links 2
[Vá para o google](http://www.google.com "google")
## Links 3 usando variável

[Vá para o google][site-url]

[site-url]:
https:www.google.com

# Imagens
## Imagem 1
![Markdown](https://cdn-images-1.medium.com/max/1200/0*_Sk12T9Yn5ch4StY.png)
## Imagem 2
![markdown][image]

[image]: https://cdn-images-1.medium.com/max/1200/0*_Sk12T9Yn5ch4StY.png
## Imagem com link 1
[![Markdown](https://cdn-images-1.medium.com/max/1200/0*_Sk12T9Yn5ch4StY.png)](http://google.com.br "google")

## Imagem com link e variáveis 
[![Markdown][image-thumbs]][image-url]


[image-thumbs]:https://cdn-images-1.medium.com/max/1200/0*_Sk12T9Yn5ch4StY.png
[image-url]:http://www.google.com

# Tabelas
## Ex 1
| Nome | Idade |
| ---- | ----- |
| Felipe | 32  |
## Ex 2
| Nome | Idade | Profissão |
| ---- |  ---- | ----------| 
| Felipe | 32 | Dev |
| Claudia | 30 | Psicóloga |
| Luke | 3 | Melhor cão do mundo |
## Ex 3 - alinhando
| Nome | Idade | Profissão |
| :---- |  :----: | ----------:| 
| Felipe | 32 | Dev |
| Claudia | 30 | Psicóloga |
| Luke | 3 | Melhor cão do mundo |

# Códigos
## Ex em linha
Informe os parâmetros `username` e `password` para função `login()`.
## Ex em bloco 1 (2 tabs)

    // login.js

    const username = 'Felipe';
    const password = 'segredo';

    login(username,password);

## Ex em bloco 2
```
// login.js

const username = 'Felipe';
const password = 'segredo';

login(username,password);
```

# Syntax Highlighting

```js
// login.js

const username = 'Felipe';
const password = 'segredo';

login(username,password);
```

