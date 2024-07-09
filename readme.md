# Overview Modelo Conceitual + Projeto Loja de Livros

## MER (Modelo Entidade Relacionamento)
Utilizado para descrever os objetos do mundo real através de **entidades**, com suas propriedades que são os **atributos** e os seus **relacionamentos**.


## Entidades
Um objeto do mundo real e que possuem uma existência independente.

![alt text](imgs/entidades-modelagem.png)

#### Entidades Fortes
Não dependem de outras entidades para existirem.

![alt text](imgs/modelagem-entidades-fortes.png)

#### Entidades Fracas
Dependem de outras entidades para existir, ou seja, elas não possuem existência própria.

![alt text](imgs/modelagem-entidades-fracas.png)

#### Entidades Associativas
Utilizadas quando existe a necessidade de associar uma entidade a um relacionamento.

![alt text](imgs/modelagem-entidade-associativa.png)

## Relacionamentos
As entidades podem se relacionar entre si, havendo assim uma associação.

#### (1:1) 
Entidade X se associa unicamente a uma ocorrência da entidade Y.

#### (1:N)
Entidade X se associa a várias ocorrências da entidade Y, porém, a entidade Y pode apenas se associar a uma ocorrência da entidade X.

#### (N:N)
Entidade X o pode se associar a várias ocorrências da entidade Y e a entidade Y pode também se associar a várias ocorrências da entidade X.

![alt text](imgs/modelagem-relacionamentos.png)

## Atributos
Descrevem as propriedades das entidades.

#### Atributos Simples
Atributos simples são indivisíveis, ou seja, são atributos atômicos, um exemplo seria o atributo CPF.

#### Atributos Composto
Podem ser divididos em partes menores, que representam outros atributos, como o atributo endereço.

#### Atributo Multivalorado
Um atributo Multivalorado pode ter um ou N(vários) valores associados a ele, como, por exemplo, o atributo telefone.

#### Atributo Derivado
Dependem de outro atributo ou até mesmo outra entidade para existir, como, por exemplo, o atributo idade e o atributo data de nascimento.

#### Atributo Chave
O atributo chave é utilizado para identificar de forma única uma entidade (ID).

![alt text](imgs/modelagem-atributos.png)






