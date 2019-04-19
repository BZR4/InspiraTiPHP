# Step by Step, ohh...

## Ambiente para Fluxo de Trabalho
### Editor de Texto
#### Sublime Text
#### VisualStudio Code

### Controle de Versão
### Navegadores

## Criar Projeto

### Configurar estrutura de diretórios
#### Diretórios
1. Crie o diretório `inspirati`;
2. Dentro do inspirati, crie o diretórios:
  - css
  - js
  - images

##### Descritivo dos diretórios

Diretório | Conteúdo | Justificativa
-- | -- | --
**inspirati**  | Todos os arquivos do projeto  |  Conteiner principal para estruturação e gerenciamento dos arquivos do
**css**  | Bibliotecas de arquivos CSS para estilização dos elementos da aplicação web.  |  Todas as estilizações existentes no BootStrap estão neste diretório, você precisa de um local especifico para poder acessa-las, o diretório css é o lugar.
**js**  | Bibliotecas para interação dos componentes do BootStrap.  |  Muitos comportamentos existentes nos componentes do BootStrap como de menus, botões e janelas modais modais realizam modificações instantâneas no elementos, estas ações deveriam ser criadas programaticamente mas estão inclusas nestas bibliotecas, ou seja você não precisará programá-las mas precisa tê-las para funcionar.
**images**  | Conteiner para imagens utilizadas no Projeto, caso houver.   |  Localização das imagens a serem utilizadas no projeto.


```javascript
// Extra small devices (portrait phones, less than 576px)
// No media query for `xs` since this is the default in Bootstrap

// Small devices (landscape phones, 576px and up)
@media (min-width: 576px) { ... }

// Medium devices (tablets, 768px and up)
@media (min-width: 768px) { ... }

// Large devices (desktops, 992px and up)
@media (min-width: 992px) { ... }

// Extra large devices (large desktops, 1200px and up)
@media (min-width: 1200px) { ... }
```


### Configurar BootStrap
### Testar BootStrap
### Inicializar projeto para versionamento


### Prepara persistência de dados
#### Criar Modelagem de Dados
#### Criar Banco de dados
#### Criar Views para consultas
#### Criar Scripts para implementação em servidor de hospedagem

### Criar Formulários para persistência de dados
#### Criar formulário de cadastro de Funcionários utilizando BootStrap
#### Criar Script PHP para gravar dados de funcionário em Base de Dados
#### Realizar testes de inclusão de funcionário em Base de Dados
