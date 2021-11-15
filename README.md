# `PROJECTBACKEND`

#### `Para execução dos programas utilizamos a extenção Thunder Client no Vs Code`


- Acesso atraves do Request https://projetbackend.herokuapp.com como url principal seguido das rotas e subrotas desejadas.

## Rotas principais

```
/paises
```

```
/estados
```

```
/cidades
```

## Subrotas

```
/listall
```

```
/listname/:id
```

```
/add
```

```
/update/:id
```

```
/delete/:id
```


## Opções de rotas banco de dados:
- Acesso Paises: 
 ``` 
 https://projetbackend.herokuapp.com/paises 
 ```
- Acesso Estados:
 ```
 https://projetbackend.herokuapp.com/estados 
 ```
- Acesso Cidades
 ```
 https://projetbackend.herokuapp.com/cidades 
 ```

## Opções de consultas de todos itens gerados no banco de dados
### ``listall``

- Para consultar todo conjunto de informação no banco de dados, deve-se utilizar a url juntamente com a rota desejada (ex: /paises), com a subrota /listall conforme exemplos abaixo:

```
https://projetbackend.herokuapp.com/paises/listall 
```

```
https://projetbackend.herokuapp.com/estados/listall
```

```
https://projetbackend.herokuapp.com/cidades/listall 
```


## Opções de consultas por id
### ``/listname/:id``

- Para consultar um determinado comnjunto de informações (ex: informações sobre determinado pais) no banco de dados, deve-se utilizar a url juntamente com a rota principal (ex: /paises), com a subrota /listname/[id] conforme exemplos abaixo:

```
https://projetbackend.herokuapp.com/paises/lisname1
```

```
https://projetbackend.herokuapp.com/estados/listname3
```

```
https://projetbackend.herokuapp.com/cidades/listname7
```


## Adicionando novos dados
### ``/add``

- Para adicionar novos dados deve-se utilizar a url juntamente com a rota principal (ex: /paises), com a subrota /add conforme exemplos abaixo:

```
https://projetbackend.herokuapp.com/paises/add
```

```
https://projetbackend.herokuapp.com/estados/add
```

```
https://projetbackend.herokuapp.com/cidades/add
```


## Atualizando dados
### ``/update/:id``

- Para atualizar os dados deve-se utilizar a url juntamente com a rota principal (ex: /paises), com a subrota /update/[id] conforme exemplos abaixo:

```
https://projetbackend.herokuapp.com/paises/update/2
```

```
https://projetbackend.herokuapp.com/estados/update/5
```

```
https://projetbackend.herokuapp.com/cidades/update/9
```


## Deletando dados
### ``/delete/:id``

- Para deletar os dados deve-se utilizar a url juntamente com a rota principal (ex: /paises), com a subrota /delete/[id] conforme exemplos abaixo:

```
https://projetbackend.herokuapp.com/paises/delete/2
```

```
https://projetbackend.herokuapp.com/estados/delete/5
```

```
https://projetbackend.herokuapp.com/cidades/delete/9
```
