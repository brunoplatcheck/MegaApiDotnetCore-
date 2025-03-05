<h1 align="center">
  <br />
  <img
    src="_docs\assets\icon.png"
    alt="Mega Man Robots API"
    width="150"
  />
  <br />
  <b>Mega Man Robots API</b>
  <br />
  <sub
    ><sup><b>(MEGA-MAN-ROBOTS)</b></sup></sub
  >
  <br />
  <a
    href="https://github.com/Jonny23Parker/MegaApiDotnetCore/actions/workflows/build.yml"
  >
    <img
      src="https://github.com/Jonny23Parker/MegaApiDotnetCore/actions/workflows/build.yml/badge.svg"
      alt=""
    />
  </a>
  <a href="https://github.com/Jonny23Parker/MegaApiDotnetCore/releases/latest">
    <img
      src="https://img.shields.io/github/v/release/Jonny23Parker/MegaApiDotnetCore"
      alt="Latest Release"
    />
  </a>
</h1>

<p align="center">
  This .NET Core API is designed to serve JSON formatted data about bosses from
  the Mega Man series. It is a backend service built with .NET Core 3.1 and
  various modern dependencies for data management and API response handling.
  <br />
</p>

<p align="center">
  Developed with Entity Framework Core and other modern .NET technologies, this
  project aims to provide a robust API for accessing Mega Man robot data.
  <br />
</p>

<p align="center">
  <br />
  <img src="./_docs/assets/carbon.png" />
</p>

## API Endpoints

<table align="center">
  <tr>
    <th>Method</th>
    <th>Endpoint</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>GET</td>
    <td>/api/v1/robots</td>
    <td>Returns a list of all robots</td>
  </tr>
  <tr>
    <td>GET</td>
    <td>/api/v1/robots/{id}</td>
    <td>Returns details of a specific robot by ID</td>
  </tr>
  <tr>
    <td>POST</td>
    <td>/api/v1/robots</td>
    <td>Endpoint to create a new robot entry</td>
  </tr>
</table>

## Techniques Used

<p align="center">
  - <b>Entity Framework Core:</b> ORM for data management.<br />
  - <b>RESTful API Design:</b> Ensures clear and effective communication
  endpoints.<br />
  - <b>Dependency Injection:</b> Used throughout to promote loose coupling and
  enhanced testability.<br />
</p>

## Dependencies

<table align="center">
  <tr>
    <th>Package</th>
    <th>Version</th>
    <th>Link</th>
  </tr>
  <tr>
    <td>Microsoft.EntityFrameworkCore</td>
    <td>3.1.8</td>
    <td>
      <a
        href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore/3.1.8"
        >NuGet</a
      >
    </td>
  </tr>
  <tr>
    <td>Microsoft.EntityFrameworkCore.Design</td>
    <td>3.1.8</td>
    <td>
      <a
        href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.Design/3.1.8"
        >NuGet</a
      >
    </td>
  </tr>
  <tr>
    <td>Microsoft.EntityFrameworkCore.SqlServer</td>
    <td>3.1.8</td>
    <td>
      <a
        href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.SqlServer/3.1.8"
        >NuGet</a
      >
    </td>
  </tr>
  <tr>
    <td>Newtonsoft.Json</td>
    <td>12.0.2</td>
    <td>
      <a href="https://www.nuget.org/packages/Newtonsoft.Json/12.0.2">NuGet</a>
    </td>
  </tr>
</table>

## :gear: Arch

```🌐
src
├── 📂 Controllers      [Routes for endpoints]
├── 📂 Models           [Database models]
├── 📂 Services         [Business rules]
├── 📂 Middlewares      [Intermediate functions between the HTTP request and the final server response]
├── 📂 Database         [Structures related to the database]
│   ├── 📂 DTOs             [Input Models and View Models (Data Transfer Objects)]
│   ├── 📂 EntityFramework  [Files related to the ORM Entity Framework]
│   │     ├── 📂 Context         [Entity context settings]
│   │     ├── 📂 Migrations      [Migrations for database updates]
│   ├── 📂 Repositories     [Repository pattern]
```


<h1 align="center">
  <br />
  <img src="./_docs/assets/icon.png" alt="MegaMan Bosses API" width="150" />
  <br />
  <b>MegaMan Bosses API</b>
  <br />
  <sub><sup><b>(MEGA-MAN-BOSSES)</b></sup></sub>
  <br />
  <a href="https://github.com/seu-repo/megaman-bosses-api/actions/workflows/build.yml">
    <img src="https://github.com/seu-repo/megaman-bosses-api/actions/workflows/build.yml/badge.svg" alt="Build Status" />
  </a>
  <a href="https://github.com/seu-repo/megaman-bosses-api/releases/latest">
    <img src="https://img.shields.io/github/v/release/seu-repo/megaman-bosses-api" alt="Latest Release" />
  </a>
</h1>

<p align="center">
  Uma API desenvolvida em .NET Core 3.1 para listar os bosses da franquia MegaMan.
  A API retorna dados em formato JSON, incluindo ID, código, nome, vida e imagem de cada boss.
  <br />
</p>

<p align="center">
  <br />
  <img src="./_docs/assets/carbon.png" />
</p>

## 🚀 Tecnologias Utilizadas

- **[.NET Core 3.1](https://dotnet.microsoft.com/en-us/download/dotnet/3.1)**
- **[Entity Framework Core 3.1.8](https://docs.microsoft.com/en-us/ef/core/)**
- **[SQL Server](https://www.microsoft.com/pt-br/sql-server/sql-server-downloads)**
- **[Newtonsoft.Json 12.0.2](https://www.newtonsoft.com/json)**

## 🔗 API Endpoints

<table align="center">
  <tr>
    <th>Método</th>
    <th>Endpoint</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td>GET</td>
    <td>/api/v1/robots</td>
    <td>Retorna a lista de todos os bosses</td>
  </tr>
  <tr>
    <td>GET</td>
    <td>/api/v1/robots/{id}</td>
    <td>Retorna os detalhes de um boss específico pelo ID</td>
  </tr>
  <tr>
    <td>POST</td>
    <td>/api/v1/robots</td>
    <td>Cria um novo boss</td>
  </tr>
</table>

## 📦 Dependências

<table align="center">
  <tr>
    <th>Pacote</th>
    <th>Versão</th>
    <th>Link</th>
  </tr>
  <tr>
    <td>Microsoft.EntityFrameworkCore</td>
    <td>3.1.8</td>
    <td><a href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore/3.1.8">NuGet</a></td>
  </tr>
  <tr>
    <td>Microsoft.EntityFrameworkCore.Design</td>
    <td>3.1.8</td>
    <td><a href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.Design/3.1.8">NuGet</a></td>
  </tr>
  <tr>
    <td>Microsoft.EntityFrameworkCore.SqlServer</td>
    <td>3.1.8</td>
    <td><a href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.SqlServer/3.1.8">NuGet</a></td>
  </tr>
  <tr>
    <td>Newtonsoft.Json</td>
    <td>12.0.2</td>
    <td><a href="https://www.nuget.org/packages/Newtonsoft.Json/12.0.2">NuGet</a></td>
  </tr>
</table>

## 🛠 Estrutura do Projeto

```plaintext
.vs/
.vscode/
bin/
Controllers/
Database/
middlewares/
Models/
obj/
Properties/
Services/
appsettings.Development.json
appsettings.json
global.json
MegamanApi.csproj
MegamanApi.sln
Program.cs
Startup.cs
```

## ▶️ Como Executar o Projeto

1. **Clone o repositório**:
   ```sh
   git clone <URL_DO_REPOSITORIO>
   cd <NOME_DO_DIRETORIO>
   ```

2. **Restaure os pacotes NuGet**:
   ```sh
   dotnet restore
   ```

3. **Execute a aplicação**:
   ```sh
   dotnet run
   ```

4. **Acesse a API**:
   - A API estará disponível em `http://localhost:5000`

## 🤝 Contribuição
Se quiser contribuir com o projeto, siga os passos:
1. Fork este repositório.
2. Crie uma branch com sua funcionalidade (`git checkout -b minha-feature`).
3. Commit suas alterações (`git commit -m 'Minha nova funcionalidade'`).
4. Envie para o repositório remoto (`git push origin minha-feature`).
5. Abra um Pull Request.

## 📜 Licença
Este projeto está sob a licença MIT. Para mais detalhes, consulte o arquivo `LICENSE`.

<h1 align="center">
  <br />
  <img src="./_docs/assets/icon.png" alt="MegaMan Bosses API" width="150" />
  <br />
  <b>MegaMan Bosses API</b>
  <br />
  <sub><sup><b>(MEGA-MAN-BOSSES)</b></sup></sub>
  <br />
  <a href="https://github.com/seu-repo/megaman-bosses-api/actions/workflows/build.yml">
    <img src="https://github.com/seu-repo/megaman-bosses-api/actions/workflows/build.yml/badge.svg" alt="Build Status" />
  </a>
  <a href="https://github.com/seu-repo/megaman-bosses-api/releases/latest">
    <img src="https://img.shields.io/github/v/release/seu-repo/megaman-bosses-api" alt="Latest Release" />
  </a>
  <a href="https://github.com/seu-repo/megaman-bosses-api/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/seu-repo/megaman-bosses-api" alt="License" />
  </a>
</h1>

<p align="center">
  Uma API desenvolvida em .NET Core 3.1 para listar os bosses da franquia MegaMan.
  A API retorna dados em formato JSON, incluindo ID, código, nome, vida e imagem de cada boss.
  <br />
</p>

<p align="center">
  <br />
  <img src="./_docs/assets/carbon.png" />
</p>

## 🚀 Tecnologias Utilizadas

- **[.NET Core 3.1](https://dotnet.microsoft.com/en-us/download/dotnet/3.1)**
- **[Entity Framework Core 3.1.8](https://docs.microsoft.com/en-us/ef/core/)**
- **[SQL Server](https://www.microsoft.com/pt-br/sql-server/sql-server-downloads)**
- **[Newtonsoft.Json 12.0.2](https://www.newtonsoft.com/json)**

## 🔗 API Endpoints

<table align="center">
  <tr>
    <th>Método</th>
    <th>Endpoint</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td>GET</td>
    <td>/api/v1/robots</td>
    <td>Retorna a lista de todos os bosses</td>
  </tr>
  <tr>
    <td>GET</td>
    <td>/api/v1/robots/{id}</td>
    <td>Retorna os detalhes de um boss específico pelo ID</td>
  </tr>
  <tr>
    <td>POST</td>
    <td>/api/v1/robots</td>
    <td>Cria um novo boss</td>
  </tr>
  <tr>
    <td>PUT</td>
    <td>/api/v1/robots/{id}</td>
    <td>Atualiza um boss existente</td>
  </tr>
  <tr>
    <td>DELETE</td>
    <td>/api/v1/robots/{id}</td>
    <td>Deleta um boss existente</td>
  </tr>
</table>

## 📦 Dependências

<table align="center">
  <tr>
    <th>Pacote</th>
    <th>Versão</th>
    <th>Link</th>
  </tr>
  <tr>
    <td>Microsoft.EntityFrameworkCore</td>
    <td>3.1.8</td>
    <td><a href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore/3.1.8">NuGet</a></td>
  </tr>
  <tr>
    <td>Microsoft.EntityFrameworkCore.Design</td>
    <td>3.1.8</td>
    <td><a href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.Design/3.1.8">NuGet</a></td>
  </tr>
  <tr>
    <td>Microsoft.EntityFrameworkCore.SqlServer</td>
    <td>3.1.8</td>
    <td><a href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.SqlServer/3.1.8">NuGet</a></td>
  </tr>
  <tr>
    <td>Newtonsoft.Json</td>
    <td>12.0.2</td>
    <td><a href="https://www.nuget.org/packages/Newtonsoft.Json/12.0.2">NuGet</a></td>
  </tr>
</table>

## 🛠 Estrutura do Projeto

```plaintext
.vs/
.vscode/
bin/
Controllers/
Database/
middlewares/
Models/
obj/
Properties/
Services/
appsettings.Development.json
appsettings.json
global.json
MegamanApi.csproj
MegamanApi.sln
Program.cs
Startup.cs
```

## ▶️ Como Executar o Projeto

1. **Clone o repositório**:
   ```sh
   git clone <URL_DO_REPOSITORIO>
   cd <NOME_DO_DIRETORIO>
   ```

2. **Restaure os pacotes NuGet**:
   ```sh
   dotnet restore
   ```

3. **Execute a aplicação**:
   ```sh
   dotnet run
   ```

4. **Acesse a API**:
   - A API estará disponível em `http://localhost:5000`

## 🤝 Contribuição
Se quiser contribuir com o projeto, siga os passos:
1. Fork este repositório.
2. Crie uma branch com sua funcionalidade (`git checkout -b minha-feature`).
3. Commit suas alterações (`git commit -m 'Minha nova funcionalidade'`).
4. Envie para o repositório remoto (`git push origin minha-feature`).
5. Abra um Pull Request.

