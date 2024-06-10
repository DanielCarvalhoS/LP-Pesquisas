# LP-Pesquisas
![image](https://github.com/DanielCarvalhoS/LP-Pesquisas/assets/162492997/34c3cdcf-1c08-47e5-aa36-8262dc184597)

>[!Important]
>- 13/06/24.
>- Pesquisar na documentação de script do Unity dez funções de matemática e cinco funções de física. Para cada função(Método) descrever os parametros de entrada e os tipos de retorno.

Ir no site oficial da Unity (Em funções), e analisar os métodos.
Pesquisar os tipos de dados do C# (Na mesma pesquisa).

Separar a Pesquisa, afinal o Unity tem alguns tipos de dados do Unity.

## Sites:
>[!Important]
Matemática
>-https://docs.unity3d.com/ScriptReference/Mathf.html
Física
>-https://docs.unity3d.com/ScriptReference/Physics.html

## Programação

-Vamos primeiramente explicar sobre os tipos de dados do C#, contando seu funcionamento e diferenças ao tipos de dados com o Unity
  Logo após, vamos falar sobre os métodos de Matemática (10), assim falando oque cada método escolhido faz, oque ele recebe, para que recebe e oque entrega.
  Repetir essa ação para os métodos de Física. Tudo isso, falando os parametros de entrada e tipo de retorno para ambos.

 Métodos Mathf:
Max - DeltaAngle
Min - Abs
Repeat - Approximately
Round - MoveTowards
PiLog - InverseLerp

 Métodos Physic:

IgnoreColision -
Simulate -
BoxCast -
CheckSphare -
OverlapSphare 

##Tese escrita:

Os tipos de dados do c# no Unity definem a natureza dos dados armazenados nas variáveis.

Int é usado para números inteiros.
Float é utilizado para números decimais.
Com Bool, podemos armazenar valores que serão definidos como verdadeiros ou falsos.
String serve para armazenar textos.
Usamos Vector2 e Vector3 para representar posições ou direções 2D e 3D.
Para declarar uma variável e seu tipo, colocamos seu tipo e em seguida o nome da variável, fechando com um ponto e vírgula. Por exemplo: float Num1;


Métodos Matemáticos:
- Max: 
Voçê entrega dois ou mais valores, e então ele retorna o maior entre eles. Se for um número negativo, o mais próximo de zero é considerado o maior. Por exemplo: Mathf.Max(1, 2) - Ele retornará o número 2. E no caso de: Mathf.Max(-5.2f, -1.3f) - ele retornará -1,3.
- Min:
O usuário entregará dois ou mais valores, e o programa retornará o menor entre eles. Exemplo: Mathf.Min(1, 2) - ele retornará o número 1.
- Repeat:
Sua declaração é: Mathf.Repeat(Var, Comprimento). Ele faz um loop no valor da váriavel de forma que não seja maior que o comprimento ou menor que zero. Por exemplo: Mathf.Repeat(1, 5) - ele irá repetir 1.
- Round:
A declaração é: Mathf.Round(Variável float). Você entrega um número decimal, e ele retorna o mesmo arrendondado para o inteiro mais próximo. Se o número entregue terminar em ,5 estará entre um número par e outro impar. Nesse caso, ele retornará o número par. Exemplo: Mathf.Round(12.4) - ele retorna 12; Já no caso de: Mathf.Round(12.7) - ele retorna 13.
- Abs:
A declaração é: Mathf.Abs(Var inteira ou float). O usuário entrega um valor, e o programa retorna seu valor absoluto, ou seja, a distância que ele está do número zero na reta númerica. Exemplo: Mathf.Abs(-2.6) - ele retornará 2,6.
- DeltaAngle (Calcula a menor diferença dentre dois ângulos):
A declaração é: Mathf.DeltaAngle(Float atual e float do alvo). O usuário atribui o valor do ângulo atual do objeto e também o ângulo do alvo. O programa vai retorna um valor dentre -179 e 180 em graus. Assim o programa vai calcular a menor diferença dentre ambos os ângulos.
-  Approximately (Compara dois pontos de valores e retorna verdadeiro aso sejam similar).
A declaração é: Mathf.Approximately (Float a e Float b). O usuário entrega dois pontos de valores e retorna verdadeiro caso eles sejam similares. Assim usando o ponto Float de imprecisão, fazendo uma comparação de floats usando o operador igual impreciso. Exemplo 

Métodos Físicos:
- IgnoreColision:
A declaração é: Physics.IgnoreCollision(Collider collider1, Collider collider2, bool ignore = true); O usuário entrega dois colisores que irão colidir entre si ou terão essa colisão ignorada, definindo ignore como true (verdadeiro).
- CheckSphere:
A declaração é: Physics.CheckSphere(transform.position, sphereRadius). Você entrega o centro da espefera (position) e o raio (sphereRadius), e então ele verifica se há colisão com ela e retorna como verdadeiro ou falso.
