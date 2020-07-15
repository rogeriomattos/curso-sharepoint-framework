# Criando a primeira WebPart

Abra o terminal da sua máquina e siga as seguintes etapas:

### 1. Crie um novo diretório para o seu projeto

```cmd
mkdir primeira-webpart
```

### 2. Entre no diretório criado

```cmd
cd primeira-webpart
```

### 3. Dentro do diretório execute o comando que inicia o geradador Yeoman do Sharepoint

```cmd
yo @microsoft/sharepoint
```

  Esse comando irá iniciar uma serie de perguntas para a configuração do seu projeto inicial, para iniciarmos siga as configurações abaixo:

  - What is your solution name? **PrimeiraWebPart**
  - Which baseline packages do you want to target for your component(s)? **SharePoint Online only (latest)**
  - Where do you want to place the files? **Where do you want to place the files?**
  - Do you want to allow the tenant admin the choice of being able to deploy the solution to all sites immediately without running any feature deployment or adding apps in sites? **Y**
  - Do you want to allow the tenant admin the choice of being able to deploy the solution to all sites immediately without running any feature deployment or adding apps in sites? **N**
  - Which type of client-side component to create? **WebPart**
  
  - What is your Web part name? **PrimeiraWebPart**
  - What is your Web part description? **PrimeiraWebPart description**
  - Which framework would you like to use? **React**

![Prompts Yeoman](https://github.com/rogeriomattos/curso-sharepoint-framework/blob/master/02%20-%20Criando%20a%20primeira%20WebPart%20e%20entendendo%20a%20estrutura/assets/promptsYeomanSharePoint.PNG)

Depois de inserido todas essas configurações o Yeoman vai criar todo o projeto da sua WebPart, isso pode levar alguns minutos para terminar.

Quando a criação tiver concluída você verá a seguinte mensagem indicando que a criação foi bem sucedida.

![Criação da WebPart concluída](https://github.com/rogeriomattos/curso-sharepoint-framework/blob/master/02%20-%20Criando%20a%20primeira%20WebPart%20e%20entendendo%20a%20estrutura/assets/WebPartCreated.PNG)

### Como Testar a WebPart

Para testes o SPFx díspoinibiliza um servidor local, para usar isso basta executar o seguinte comando no terminal:

```cmd
gulp serve
```
Quando executado, o gulp  irá execultar uma serie  de tarefas para criar o seu  servidor local, após concluído a criação será aberto altomaticamente no seu navegador a página do seu servidor local.


