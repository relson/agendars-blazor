# AgendaRS .NET

Inspirado no [Projeto Equinox](#algumas-referências) do [Eduardo Pires](https://github.com/EduardoPires/) porem documentando o passo a passo de como se pode criar o projeto do zero e em vários níveis de complexidade bem como um template de github action para implantação em um servidor simples via ```ssh```.

Etapas:
- [X] - Criar repositório no github 
- [ ] - CRUD Básico
- [ ] - Implatação
- [ ] - Blog Post

## Tecnologias

- Dotnet 8
- Blazor (InteractiveServer)
- Fluent UI Blazor
- EntityFramework
- SQLite

## Criando o Projeto

> Verificando a versão do dotnet

```shell
dotnet --info
```

> Instalando/Atualizando o EntityFramework
```shell
dotnet tool install --global dotnet-ef # se ainda não estiver instalado
dotnet tool update --global dotnet-ef  # para atualizar para versão mais recente
```


## Algumas referências
- [Macoratti](https://www.macoratti.net/)
- [CRUD para IMPRESSIONAR na entrevista por Balta](https://youtu.be/fmDYYsSXrKM?si=xdJhd0ecpUjetxXb)
- [Equinox Project](https://github.com/EduardoPires/EquinoxProject)
