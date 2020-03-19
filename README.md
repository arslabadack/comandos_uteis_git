# Comandos úteis GIT

- Instalar git no Linux:

```
$ sudo apt install git
```



### Configurações de usuário

- Nome:

```
$ git config --global user.name "Seu Nome"
```

- E-mail:

```
$ git config --global user.email "seuemail@algumacoisa"
```



**Visualizar informações sobre o usuário git existente na máquina:**

```
$ git config user.name
```

```
$ git config user.email
```

- Tudo:

```
$ git config --list
```



### Quando precisar de ajuda:

```
$ git help comandoEscolhido
```

- Para visualiza todos os comandos:

```
$ git help
```



### Iniciar primeiro repositório:

(todas configurações do repositório ficam na pasta **.git** existente dentro do repositório).

``` 
$ git init
```



### Após ter realizado alguma modifição em uma pasta ou arquivo:

Serve para iformar ao git sobre as modificações que foram realizadas.

```
$ git add nomeArquivo
```

- Para visualizar como está o estado do repositório no momento:

```
$ git status
```



### Criar uma versão do seu código fonte

```
$ git commit -am "mensage do que você fez"
```



- Visualizar as modificações realizadas em cima da versão anterior caso haja:

```
$ git diff
```

- Visualizar os arquivos que foram modificados desde a ultima versão, caso haja:

```
$ git diff --name-only
```



### Visualizar commits anteriores

```
$ git log
```

- Visualizar quais alterações foram feitas em determinado commit:

```
$ git show númeroDoCommit
```
