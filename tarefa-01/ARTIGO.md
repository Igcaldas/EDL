# **Rust**

### **Origem**

A linguagem cresceu em 2006, vinda de um projeto pessoal de um funcionário da Mozilla , Graydon Hoare. Mozilla começou a patrocinar o projeto em 2009 e o anunciou em 2010.
Rust é uma linguagem de programação que foi desenvolvida pela Mozilla Corporation. Foi feita com a intenção de ser uma linguagem utilizada por sistemas  altamente concorrentes e seguros. Projetada para ser segura , concorrente e prática.



**Influências**
 Alef C#, C++, Cyclone, Erlang, Haskell, Limbo, Newsqueak, OCaml, Scheme, Standard ML, Swift

![rust histo](https://user-images.githubusercontent.com/7257385/64481538-b1920a00-d1b3-11e9-88a5-2d358c1e050a.jpg)


### **Classificação**

Seu design habilita a criação de programas que possuem alta performance e controle de uma linguagem baixo-nível, porém com a abstração poderosa de uma linguagem alto-nível. Essas propriedades fazem Rust ser indicada para programadores que possuem experiência em linguagens como C e estão procurando por uma alternativa mais segura, assim como aqueles que vem de linguagens como o Python que procuram formas de escrever códigos que rodam melhor sem sacrificar a expressividade.

Rust realiza a maioria das medidas de segurança e decisões de controle de memória em tempo de compilação, fazendo com que a performance de execução não seja afetada. Isso é útil em diversos casos que outras linguagens não são boas: programas com requisitos de espaço e tempo previsíveis, inseridas em outras linguagens, e escrever código baixo-nível, como drivers de dispositivos e sistemas operacionais.
Rust gerencia memória e recursos automaticamente, sem necessitar de um coletor de lixo.

* Segurança sem coletor de lixo (linguagens como Java, GO).
* Concorrência sem disputa de dados.
* Abstração sem overhead.
* Multiparadigma (orientada a objetos, estruturada, imperativa compilada, concorrente, funcional)
*	Pattern matching
*	Task-based concurrency. Lightweight tasks can run in parallel without sharing any memory 
*	Funções de alta ordem (closures)
*	Polimorfismo, combinando interfaces parecidas com java e classes parecidas com haskell
*	Generics
*	Sem 'buffer overflow'

## ***Exemplos de cógidos***
Em rust, podemos definir um tipo de dados como:
* Signed: que guarda valor negativo ou positivo

* Unsigned: guarda apenas valroes positivos 
_________________________________________________
![uni](https://user-images.githubusercontent.com/7257385/64481049-9f5f9e00-d1aa-11e9-95ef-5e9c68935169.jpg)
_________________________________________________

![Hello World](https://user-images.githubusercontent.com/7257385/64479753-9b735200-d191-11e9-92de-010047fe0c3f.jpg)

_________________________________________________
![variaveis](https://user-images.githubusercontent.com/7257385/64480149-d1680480-d198-11e9-9e6d-8da53e67e24c.jpg)

*Em rust , as variáveis são imutáveis por padrão*
_________________________________________________
Definindo string
String Literal(&str) / String Object(String)
![string c](https://user-images.githubusercontent.com/7257385/64482030-ed32d100-d1bf-11e9-857e-3afcca315349.jpg)

_________________________________________________

![fatorial](https://user-images.githubusercontent.com/7257385/64482023-ae9d1680-d1bf-11e9-8ecc-bf8a7510ba38.jpg)


### ***Avaliação comparativa***
Ownership
Rust has an ownership system where all values have a unique owner, where the scope of the value is the same as the scope of the owner.
Values can be passed by immutable reference using &T, by mutable reference using &mut T or by value using T. At all times, there can either be multiple immutable references or one mutable reference. The Rust compiler enforces these rules at compile time and also checks that all references are valid.

### ***Códigos representativos***
