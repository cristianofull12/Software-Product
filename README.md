# Software Product 
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/cristianofull12/Software-Product/blob/main/LICENSE) 

# Sobre o projeto

Este projeto tem como objetivo a criação de um CRUD com 3 camadas (front/back/banco), onde será entreque dividido em 3 AC´s e uma prova final. 

- AC1 - Será implementado a funcionalidade de inserção de um registro no banco de dados.
- AC2 - Será implementado a funcionalidade de editar um registro no banco de dados.
- AC3 - Será implementado a funcionalidade de visualizar os detalhes de um registro no banco de dados.
- Prova - Será implementado a funcionalidade de exclusão de um registro no banco de dados.

# Tecnologias utilizadas
## .Net
- C# MVC 
- Entity Framework
 
## Banco de Dados 
- Microsoft Sql Server

# Como executar o projeto

Pré-requisitos: .Net 6.0.5 (questão de compatibilidade)

## Clonar o repositório
```bash
git clone https://github.com/xxxxxxxxxxxxxxxxxxxxx
```

- Abrir o projeto no vscode ou na IDE de preferencia 
- Instalar dependencias:
- Entity Framework - a nível de máquina
```bash
dotnet tool install --global dotnet-ef --version 6.0.5
```
- SqlServer - Pacote a nível de projeto
```bash
dotnet add package Microsoft.EntityFrameworkCore.SqlServer --version 6.0.5
```
- Design - Pacote a nível de projeto
```bash
dotnet add package Microsoft.EntityFrameworkCore.Design --version 6.0.5
```
- Rodar a aplicação
```bash
dotnet watch run
```

# Autor

Cristiano Pereira da Silva
