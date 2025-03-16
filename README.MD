<h1 align="center">
  <br />
  <img
    src="./_docs/assets/icon.png"
    alt="Mega Man Robots API"
    width="150"
  />
  <br />
  <b>Mega Man Bosses API</b>
  <br />
  <sub
    ><sup><b>(MEGA-MAN-ROBOTS)</b></sup></sub
  >
  <br />
  <a
    href="https://github.com/JulianoTurra/MegaApiDotnetCore/actions/workflows/build.yml"
  >
    <img
      src="https://github.com/JulianoTurra/MegaApiDotnetCore/actions/workflows/build.yml/badge.svg"
      alt=""
    />
  </a>
  <a href="https://github.com/JulianoTurra/MegaApiDotnetCore/releases/latest">
    <img
      src="https://img.shields.io/github/v/release/JulianoTurra/MegaApiDotnetCore"
      alt="Latest Release"
    />
  </a>
</h1>

<p align="center">
  Esta API .NET Core foi projetada para fornecer dados em formato JSON sobre chefes da série Mega Man. É um serviço de backend construído com .NET Core 3.1 e várias dependências modernas para gerenciamento de dados e manipulação de respostas da API.
  <br />
</p>

<p align="center">
  Desenvolvido com Entity Framework Core e outras tecnologias modernas do .NET, este projeto tem como objetivo fornecer uma API robusta para acessar dados dos bosses de Mega Man.
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
    <td>Retorna uma lista de todos os robôs</td>
  </tr>
  <tr>
    <td>GET</td>
    <td>/api/v1/robots/{id}</td>
    <td>Retorna os detalhes de um robô específico pelo ID</td>
  </tr>
  <tr>
    <td>POST</td>
    <td>/api/v1/robots</td>
    <td>Endpoint para criar uma nova entrada de robô</td>
  </tr>
</table>

## Técnicas Usadas

<p align="center">
  - <b>Entity Framework Core:</b> ORM para gerenciamento de dados.<br />
  - <b>RESTful API Design:</b> Garante comunicação clara e eficaz nos
  endpoints.<br />
  - <b>Dependency Injection:</b> Usado ao longo do projeto para promover um baixo acoplamento e uma melhor testabilidade.<br />
</p>

## Dependências

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

## ⚙ Arquitetura

```🌐
src
├── 📂 Controllers      [Rotas para os endpoints]
├── 📂 Models           [Modelos de Banco de Dados]
├── 📂 Services         [Regras de Negócios]
├── 📂 Middlewares      [Funções intermediárias entre a solicitação HTTP e a resposta final do servidor]
├── 📂 Database         [Estruturas relacionadas ao banco de dados]
│   ├── 📂 DTOs             [Modelos de Entrada e Modelos de Visualização (Objetos de Transferência de Dados)]
│   ├── 📂 EntityFramework  [Arquivos relacionados ao ORM Entity Framework]
│   │     ├── 📂 Context         [Configurações do contexto da entidade]
│   │     ├── 📂 Migrations      [Migrações para atualizações do banco de dados]
│   ├── 📂 Repositories     [Padrão de repositório]
```

## Licença Este software está licenciado sob os termos da [MIT]

⌨️ JulianoTurra -
[Github](https://github.com/JulianoTurra)
