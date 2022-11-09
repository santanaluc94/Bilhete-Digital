# Docker Lumen/React

Projeto desenvolvido com fins de estudos de docker.

### Serviços do ambiente
- MySQL
- Apache
- phpMyAdmin
- PHP 7.4
- Lumen
- Node
- React

## Comandos

Para **instalar** todo o ambiente é necessário somente um passo:

```sh
bin/install
```

Para **parar** os contêiners do projeto:

```sh
bin/stop
```

Para **iniciar** os contêiners do projeto:

```sh
bin/start
```

Para **iniciar** os servidores do projeto, é só passar como parâmetro "lumen" ou "react":

```sh
bin/run
```

> #### Executando o servidores:
> - _Sem argumentos_: Inicia os dois servidores locais sem atrelar o terminal
> - **lumen**: Inicia o servidor local do lumen atrelando o terminal
> - **react**: Inicia o servidor local do react atrelando o terminal

Para **entrar** no contêiner do projeto, é só passar como parâmetro "lumen" ou "react":

```sh
bin/bash lumen
bin/bash react
```

Para **reiniciar** os contêiners do projeto:

```sh
bin/restart
```

Para **deletar** o projeto:

```sh
bin/kill
```

> Este comando inclui as seguintes funções:
> - deletar o lumen
> - deletar o react
> - deletar o node
> - deletar o banco de dados
> - deletar os contêiners
> - deletar o volume do contêiner
> - deletar a rede dos contêiners

---

## Acessos

### MySQl

Acessos do banco de dados como administrador:

```txt
Usuário: admin
Senha: admin1234
```

Os endereços de IP do MariaDB:

```txt
padrão: 171.0.0.10:3306
local: 127.0.0.1:3306
```

### phpMyAdmin

O acesso ao phpMyAdmin já vem por padrão o usuário de administrador do banco de dados.
Os endereços de IP do phpMyAdmin:

```txt
padrão: 171.0.0.15:80
local: 127.0.0.1:8000
```

### Lumen

Os endereços de IP do Lumen:

```txt
padrão: 171.0.0.20:80
local: 127.0.0.1:80
```

### React

Os endereços de IP do React:

```txt
padrão: 171.0.0.21:8080
local: 127.0.0.1:8080
```