# BDD automation .NET playground

## P.O.C Objective (WIP)
Learn how to implement  **BDD**  test automation with [specflow][specflow] and [Docker][docker] 

## Content
  1.  [TODO List](#TODO-List) 
  2.  [Stack](#Stack)
  3.  [Requirements](#Requirements)
  4.  [Directory tree](#Directory-tree)
  5.  [How to use](#How-to-use)

## TODO List
- [ ] Create a directory structure	
- [ ] Implement a simple **Book** CR~~UD~~
  - [ ] Implement **Create**
  - [ ] Implement **Read**
  - [ ] Implement **Fluent Validation** to validate payload
- [ ] Implement a simple **Author** CR~~UD~~
  - [ ] Implement **Create**
  - [ ] Implement **Read**
  - [ ] Implement **Fluent Validation** to validate payload
- [ ] Implement a simple **Category** CR~~UD~~
  - [ ] Implement **Create**
  - [ ] Implement **Read**
  - [ ] Implement **Fluent Validation** to validate payload
- [ ] Implement a simple **Catalog** CR~~UD~~
  - [ ] Implement **Create**
  - [ ] Implement **Read**
  - [ ] Implement **Fluent Validation** to validate payload
- [ ] Implement a simple **Customer** CR~~UD~~
  - [ ] Implement **Create**
  - [ ] Implement **Read**
  - [ ] Implement **Fluent Validation** to validate payload
- [ ] Create **Catalog** route
  - [ ] Create Price rule
  - [ ] Validate rule with [specflow][specflow]
- [ ] Conclusion documentation



## Stack

### Languages

1. [**C#**][csharp] as development language 
2. [**Gherkin**][gherkin] as specification language **(BDD)**
3. [**yaml**][yaml] as docker configuration language

### Frameworks

1. [**asp.net core**][aspnetcore] as development framework
2. [**Xunit**][xunit] as test framework
3. [**Specflow**][specflow] as BDD framework
4. [**EF core**][efcore] as ORM

### Data base
1.	[**SQL server**][sqlserver]

### Container

1. [**Docker**][docker]



## Requirements

1. [Docker][docker]
2. dotnet sdk V5.0.202 or latest **(If want run locally)**



## Directory tree

```txt
ROOT \
┣ BookStore.App \
┃ ┣ 📂 controllers \
┃ ┣ 📂 Domain \
┃ ┣ 📂 DTO \
┃ ┣ 📂 Validation \
┃ ┣ 📂 Infrastructure \
┃ ┃ ┣ 📂 Mappers
┃ ┣ 📂 Properties \
┃ ┃ 📂 IOC \
┃ ┃ ┣ 📜 ServicesInjection.cs
┃ ┣ 📜 appsettings.json
┃ ┣ 📜 Program.cs
┃ ┣ 📜 Startup.cs
┣ BookStore.Test \
┣ 📜 BookStore.sln
┣ 📜 docker-compose.yml
┣ 📜 README.md
┣ 📜 test.sh
```

## How to use
### Test with docker

```bash
./test.sh
```
### Test locally

```bash
docker-compose up -d databse &&\
donet test
```


[specflow]: https://specflow.org/
[yaml]: https://yaml.org/
[gherkin]: https://docs.specflow.org/projects/specflow/en/latest/Gherkin/Gherkin-Reference.html
[csharp]: https://docs.microsoft.com/en-us/dotnet/csharp/
[ docker ]: https://www.docker.com/
[ aspnetcore]: https://docs.microsoft.com/en-us/aspnet/core/?view=aspnetcore-5.0
[ efcore ]: https://docs.microsoft.com/en-us/ef/core/
[ xunit ]: https://xunit.net/
[sqlserver]: https://www.microsoft.com/pt-br/sql-server/sql-server-downloads

