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
- [Fluent UI Blazor](https://www.fluentui-blazor.net/)
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
>Adicionando uma nova página, instalando o code generator
```shell
dotnet tool install -g dotnet-aspnet-codegenerator 
```

>Instalando os templates do Fluent UI
```shell
dotnet new install Microsoft.FluentUI.AspNetCore.Templates
```
>Verificando os templates instalados os templates do Fluent UI
```shell
dotnet new list fluent
```


## Algumas referências
- [Macoratti](https://www.macoratti.net/)
- [CRUD para IMPRESSIONAR na entrevista por Balta](https://youtu.be/fmDYYsSXrKM?si=xdJhd0ecpUjetxXb)
- [Equinox Project](https://github.com/EduardoPires/EquinoxProject)
- [Fluent UI - Blazor](https://www.fluentui-blazor.net/)
