## 📣 Hey!!

---

### Este repositório conterá minhas anotações dos conhecimentos obtidos sobre Python através da plataforma Descomplica.

---

#### MANIPULAÇÃO DE DADOS

Ao invés de simplesmente alterarmos valores diretamente no código, veremos como lidar com esses valores por meio de comandos específico que recebem os dados digitados pelo usuário e os atribui às variáveis.

 *inserção (input)* Este comando permite a atribuição de valores previamente escritos pelo usuário, a variáveis, de forma a tornar a aplicação mais dinâmica.

 *output (saída)* 

*As Operações Aritméticas fundamentais são: adição, subtração, multiplicação e divisão.

nome = input("Digite seu nome: ")
nascimento = input("Qual seu ano de nascimento? ")
email = input("Digite seu e-mail: ")
print("Nome: " , nome , ". E-mail: " , email , ". Nascimento: " , nascimento , ".")

---

Os textos não podem se misturar com variáveis, a menos que exista algum elo entre as partes envolvidas. Este elo nós chamamos de concatenação.

Em Python, a concatenação é determinada como sendo uma vírgula e deve ficar entre:

um texto e uma variável;
uma variável e outra variável;
uma variável e uma função;
um texto e uma função;
um texto e uma estrutura de dados, por exemplo, listas;
uma variável e uma estrutura de dados;
uma função e uma estrutura de dados.

Esta concatenação auxilia o interpretador da linguagem a compreender onde um comando termina ou inicia, de forma que os conceitos não sejam confundidos.

---

#### SAÍDA DE DADOS

Uma saída de dados é o fato de imprimir valores em tela. Essa impressão se dá por meio do comando print()

---

#### TRATAMENTO DE INPUT/OUTPUT

O casting informa ao interpretador do Python que aquele dado que inicialmente foi recebido como texto, na verdade, deve ser convertido para algum outro tipo, como por exemplo, número inteiro.

int() - converte dados do tipo String ou Floats para inteiros
float() - converte dados do tipo inteiro ou Strings para números com casas decimais
str() - converte dados do tipo decimais ou inteiros para texto

---

É importante salientar que, caso você converta números que tenham casas decimais para números inteiros, ocorrerá o arredondamento para baixo, ou seja, um valor de 1,9 será convertido para 1 e não para 2 (a menos que haja um comando específico de arredondamento para cima).

---

Embora muito presentes, as operações matemáticas não são as únicas presentes na programação. Existem outras operações amplamente utilizadas, principalmente em testes condicionais ou laços de repetição

#### Operadores aritméticos

São aqueles responsáveis por realizar cálculos matemáticos. São eles:

+ (adição)
- (subtração)
* (multiplicação)
/ (divisão)
% (módulo)
** (potenciação)
sqrt() (radiciação)

Os cálculos de álgebra simples, como as quatro operações fundamentais (adição, subtração, multiplicação e divisão) podem ser executados diretamente. Outros operadores que também podem ser executados de forma direta, embora não compunham as operações básicas, são o módulo (resto de uma divisão) e a potenciação, já a radiciação, requer a importação de um pacote

---

#### Operadores relacionais

Esses operadores relacionam dois elementos entre si buscando uma saída lógica que deverá sempre ser verdadeira ou falsa. Os operadores relacionais são:

> (maior que)
< (menor que)
>= (maior ou igual a)
<= (menor ou igual que)
== (igual a)
!= (diferente de)

