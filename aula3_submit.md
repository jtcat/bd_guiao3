# BD: Guião 3


## ​Problema 3.1
 
### *a)*

```
Cliente(nome, endereco, num_carta, -NIF-)
Aluguer(data, duracao, -número-, Cliente_NIF, Balcao_número, Veiculo_matricula)
Balcao(nome, endereco, -número-)
Veiculo(ano, marca, -matrícula-, Tipo_Veiculo_código)
Tipo_Veiculo(designacao, arcondicionado, -código-)
Similaridade(Tipo_Veiculo_código)
Ligeiro(Tipo_Veiculo_código, numlugares, portas, combustivel)
Pesado(Tipo_Veiculo_código, peso, passageiros)
```


### *b)* 

```
Cliente:
    Chaves candidatas: NIF, num_carta.
    Chave primária: NIF
    Chave estrangeiras: NIF

Aluguer:
    Chaves candidatas: número
    Chave primária: número
    Chaves estrangeiras: Cliente_NIF, Balcao_número, Veiculo_matricula

Balcao:
    Chaves candidatas: número, endereço, nome
    Chave primária: número
    Chaves estrangeiras:

Veiculo:
    Chaves candidatas: matrícula
    Chave primária: matrícula
    Chaves estrangeiras: código

Tipo_Veiculo:
    Chaves candidatas: código
    Chave primária: código
    Chaves estrangeiras:

Ligeiro:
    Chaves candidatas: Tipo_Veiculo_código
    Chave primária: Tipo_Veiculo_código
    Chaves estrangeiras: Tipo_Veiculo_código

Pesado:
    Chaves candidatas: Tipo_Veiculo_código
    Chave primária: Tipo_Veiculo_código
    Chaves estrangeiras: Tipo_Veiculo_código
```


### *c)* 

![ex_3_1c!](ex_3_1c.jpg "AnImage")


## ​Problema 3.2

### *a)*

```
Airport(-Airport_code-, City, State, Name)
Can_Land(-Aiport_code-, -Type_Name-, Max_Seats, Company)
Airplane_Type(-Type_Name-, Max_Seats, Company)
Airplane(-Airplane_id-, Total_no_of_seats, Airplane_Type_Type_Name)
Leg_Instance(No_of_avail_seats, Date, Airplane_Airplane_id)
```


### *b)* 

```
... Write here your answer ...
```


### *c)* 

![ex_3_2c!](ex_3_2c.jpg "AnImage")


## ​Problema 3.3


### *a)* 2.1

![ex_3_3_a!](ex_3_3a.jpg "AnImage")

### *b)* 2.2

![ex_3_3_b!](ex_3_3b.jpg "AnImage")

### *c)* 2.3

![ex_3_3_c!](ex_3_3c.jpg "AnImage")

### *d)* 2.4

![ex_3_3_d!](ex_3_3d.jpg "AnImage")