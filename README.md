# Ponderada teste de carga semana 7

### Para realizar os testes de carga no projeto, utilizamos o K6, uma ferramenta especializada para realizar testes de carga em endpoints, a partir da definição de parametros de quantidade de usuários (vus) e tempo de teste (duration).

#### O código de teste realizado está evidenciado aqui na pasta "./teste.js". Já no projeto do grupo, esse teste e suas variações de cenário podem ser encontradas no diretório:

~~~
2024-T0003-ES09-G03\codigo\backend\src\scripts\load\answerdReport
~~~

#### O Endpoint testado foi o 
~~~
/client/answerdReport/
~~~
Esse endpoint tem a função de enviar as respostas de um questionário, que usuário fornece, para o banco de dados.

#### Resultados de teste em diferentes cenários:


#### 10 usuários em 5 minutos:
<img src ="assets\k6-aR-case1.jpeg">

#### 100 usuários em 5 minutos:
<img src ="assets\k6-aR-case2.jpeg">

#### 1000 usuários em 15 minutos:
<img src ="assets\k6-aR-case3.jpeg">

#### 10.000 usuários em 15 minutos:
<img src ="assets\k6-aR-case4.jpeg">

#### 1000 usuários em 30 minutos:
<img src ="assets\k6-aR-case5.jpeg">

#### 10.000 usuários em 30 minutos:
<img src ="assets\k6-aR-case6.jpeg">