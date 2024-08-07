## 📣 Hey!!

---

### Este repositório conterá minhas anotações dos conhecimentos obtidos sobre Python através da plataforma Descomplica.

---

#### MANIPULAÇÃO DE DADOS

Entrada de dados: É tudo aquilo que o usuário digita. (nome, CPF, endereço, ...)
E eles ficarão armazenados no Software/Programa/Algoritmo. (Mais especificamente nas variaáveis)

COMANDO PADRÃO PARA ENTRADA DE DADOS:
 *inserção (input)* Este comando permite a atribuição de valores previamente escritos pelo usuário, a variáveis, de forma a tornar a aplicação mais dinâmica. (ENTRAR COM DADOS DENTRO DE UMA VARIÁVEL)
A variável declarada não receberá mais um valor fixo. (nome = "Marcio")
Mas ela irá receber o comendo de input. (nome = input("Digite seu nome: ")
E o valor digitado será colocado dentro da variável nome.

Cada uma das variáveis recebe o comando input, que é formado pela palavra “input” e acrescida de dois parênteses, dentro dos quais, consta o que será exibido na tela como comando para o usuário.

PARA EXECUTAR você pode clicar em Iniciar a Depuração (F5) e passar linha por linha para verificar se há algum erro ou falha no seu algoritmo.

E tudo o que for digitado aparecerá no terminal porque estamos apenas testando, mas quando fpor um programa real em uso, você irá gerar um Software/aplicação que tenha a interface gráfica.


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

*Concatenação* Como os textos não podem se misturar com as variaáveis, a concatenação que é representada como um elo, auxilia o interpretador da linguagem a compreender onde um comando termina ou inicia, de forma que os conceitos não sejam confundidos. E em Python ela é determinada como uma vírgula.

Uma característica padrão de todas as linguagens de programação é que os textos puros sempre são escritos entre aspas.

É importante atentar-se a esse detalhe de forma a garantir que os textos não sejam confundidos com variáveis pelo interpretador Python. Um texto que não esteja entre aspas tem todas as características de uma variável, afinal, variáveis são meras palavras

---

#### SAÍDA DE DADOS

 *impressão (print)* - Este comando permite exibir os valores na tela.
 
Uma saída de dados é o fato de imprimir valores em tela. Essa impressão se dá por meio do comando print() que é responsável por capturar tudo o que estiver previamente descrito em variáveis e imprimir no console mediante a execução.

Sempre que você quiser que algo apareça na tela, você usará o comando print.

PARA VERIFICAR A VERSÃO QUE O SEU PYTHON ESTÁ RODANDO: py --version (hífen hífen)

PARA LIMPAR A TELA: cls

---

#### TRATAMENTO DE INPUT/OUTPUT

Tratamento de dados significa deixar a estrutura do input/output da forma que eu desejo.

EXEMPLO INCORRETO:

a = input("Digite um número: ")
print(a + 5)

EXEMPLO CORRETO:

a = int(input("Digite um número: "))
print(a + 5)

O casting informa ao interpretador do Python que aquele dado que inicialmente foi recebido como texto, na verdade, deve ser convertido para algum outro tipo, como por exemplo, número inteiro.

Caso você não realize esse tratamento, aparecerá erros no seu algoritmo, pois o input foi feito para que você insira texto/string/caractér.

int() - converte dados do tipo String ou Floats para inteiros
float() - converte dados do tipo inteiro ou Strings para números com casas decimais
str() - converte dados do tipo decimais ou inteiros para texto

É importante salientar que, caso você converta números que tenham casas decimais para números inteiros, ocorrerá o arredondamento para baixo, ou seja, um valor de 1,9 será convertido para 1 e não para 2 (a menos que haja um comando específico de arredondamento para cima).

Atente-se, entretanto, ao detalhe: casas decimais em programação, não são marcadas com uma vírgula, mas sim com um ponto, afinal, a vírgula já tem o papel de concatenação. Desta forma, o número 1,9 seria representado como 1.9 dentro de seu código.

---

#### Operadores aritméticos

Um operador é um elemento que relaciona dois ou mais elementos dentro de uma proposição.

Embora muito presentes, as operações matemáticas não são as únicas presentes na programação. Existem outras operações amplamente utilizadas, principalmente em testes condicionais ou laços de repetição

TEMOS 3 CATEGORIAS:
OPERADORES ARITMÉTICOS
OPERADORES RELACIONAIS
OPERADORES LÓGICOS

Alguns operadores no PYTHON são diferentes de outras linguagens de programação.

Possivelmente você notou na linha 4 da Figura 9, que ocorreu um cálculo matemático. Essa é uma das mágicas da programação, a possibilidade de realizar operações aritméticas de maneira precisa e baseadas em dados fixos ou variáveis.

São aqueles responsáveis por realizar cálculos matemáticos. São eles:

+ (operador da adição)
- (subtração) hífen
* (multiplicação) asterisco
/ (divisão)
% (módulo) O módulo é responsável por expôr o resto inteiro de uma divisão, por exemplo: 20 / 3 = 18 (com resto 2). Atente-se ao detalhe: estamos tratando de divisão inteira, logo, o resultado não seria 6.666.
Em suma, a nível de algoritmo, a expressão seria algo como: 20 % 3 = 2, afinal, 20 em uma divisão por 3, sobra dois.
** (potenciação) 2**3 = 2 X 2 X 2 = 8
sqrt() (radiciação) print(sqrt(4)) - IRÁ MOSTRAR o ponto de referência (2+Oj) porque não colocamos o comando completo e também adicionar uma linha de importação do pacote/biblioteca MATH de matemática onde conseguiu trazer o código pronto para poder fazer o cálculo de raiz quadrada. / SQRT É UM MÉTODO / PASSANDO O MOUSE EM CIMA DO SQRT E APERTANDO AS TECLAS CTRL+. ELE JÁ CORRIGE. /from math import sqrt (estou importando a função sqrt do método math

E você pode importar o pacote previamente ou forçar a IDE para que ela importe os pacotes quando ela ver que precisa daquela informação.

Os cálculos de álgebra simples, como as quatro operações fundamentais (adição, subtração, multiplicação e divisão) podem ser executados diretamente. Outros operadores que também podem ser executados de forma direta, embora não compunham as operações básicas, são o módulo (resto de uma divisão) e a potenciação, já a radiciação, requer a importação de um pacote.

Da mesma forma que a regra de operadores, da matemática, prevalece na programação, as regras de agrupamento também estão presentes. Dessa forma, é possível utilizar o conceito de parênteses, colchetes e chaves para agrupar valores por ordem de execução de cálculo, lembrando que, em programação, utilizamos apenas parênteses para agrupar dados.

---

#### Operadores relacionais

Esses operadores relacionam dois elementos entre si buscando uma saída lógica que deverá sempre ser verdadeira ou falsa. Os operadores relacionais são:

> (maior que)
< (menor que)
>= (maior ou igual a)
<= (menor ou igual que)
== (igual a)
!= (diferente de)

Se saldo >= valorDoSaque então realize saque

---

#### Operadores lógicos

Similar aos operadores relacionais, os operadores lógicos também são mais utilizados em situações de comparação entre dois ou mais elementos e têm, obrigatoriamente, a saída verdadeira ou falsa. Os operadores lógicos são:

and (e) - em alguns casos utiliza-se o &&, dependendo da linguagem
or (ou) - em alguns casos utiliza-se o ||, dependendo da linguagem
! (não) - em alguns casos utiliza-se o not, dependendo da linguagem

---

#### Conceituando pacotes

PACOTES/BIBLIOTECAS são conjuntos de códigos pré-prontos pela prória linguagem e você precisa apenas importar alguns comendos quando for utilizar alguns recursos desse código e facilitam a construção de determinados algoritmos.

Em algumas situações você precisará importar pacotes para realizar algumas operações, sejam elas matemáticas ou não.

Existem formas de importar um pacote inteiro para dentro de um projeto, mas em geral esse tipo de prática é evitada, conforme apontado na documentação oficial do Python: “Na maioria dos casos, os programadores Python não usam esse recurso, pois ele introduz um conjunto desconhecido de nomes no interpretador, possivelmente ocultando algumas coisas que você já definiu”.

Para poupar o trabalho do programador, o Python (e outras linguagens também) traz o pacote math(), responsável por importar várias funções matemáticas pré-estruturadas, dentre elas, a função de radiciação.

Ao invocar a função sqrt() ela ficará com um sublinhado apontando uma possível falha. Ao posicionar o mouse sobre o erro é exposto o motivo da falha: “sqrt não está definida”. Isso significa que este arquivo em questão não sabe o que é sqrt, afinal, não há a importação de um pacote que ajude-o a identificar a função utilizada.

Clicando sobre o link azul “Correção rápida”, o VSCode irá propor a importação do pacote “math”.

O código passará a funcionar da maneira correta e estará pronto para ser executado.

Caso você queira importar mais funções de dentro do pacote math, precisará apenas citar seus respectivos nomes ou simplificar o processo de importação, requerendo que o Python importe TUDO de dentro do pacote math. Essa menção de “tudo” é feita por meio de um asterisco:

from math import *

Neste trecho de código acima, estamos informando ao Python: “importe TUDO de dentro do pacote math”.

---

#### Não esqueça do que já exploramos:

Tipagem dinâmica
Sobreposição de valores em variáveis
Regras na construção de nomes de variáveis

---

#### Não esqueça de algumas regras:

Para se agrupar informações, utilize o parênteses
Não existe raiz quadrada de números negativos
Se quiser apontar um número como negativo, coloque o sinal de “menos” antes do número.

---

#### Código utilizados na aula: https://github.com/FaculdadeDescomplica/Python

---

#### Referência Bibliográfica

Python.org. Funções embutidas. Disponível em <https://docs.python.org/pt-br/3/library/functions.html >. Acesso em 10/11/2022

Python.org. Módulos. Disponível em <https://docs.python.org/3/tutorial/modules.html > (adaptado). Acesso em 10/11/2022
