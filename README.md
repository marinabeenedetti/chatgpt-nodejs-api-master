## Project chat serverless integrado com API do OpenAI ChatGPT para a AWS Cloud Week
Back-end do projeto de um chat serverless que integra com a OpenAI chatGPT e utiliza o AWS Cloud para estudo do funcionamento do AWS Cloud.


<!-- ## 🎥 Implementation Video

In the GitHub edit, drag the video that it already puts on github itself.

## 👏 Learning and more implementations

Describe what you learned and implemented in the project. -->

## 💡 Technologies used

- [x] Lambda Functions
- [x] API Gateway
- [x] DynamoDB 
- [x] Websocket API para comunicação em tempo real.
- [x] Nodejs.16x

## 🚀 Running the project

 ### Back-end

- Clonar o repositório
- Instalar as dependências com o comando ```npm install```
- Atualizar o arquivo ```.env``` com a sua chave do OpenAI
- Compactar o conteúdo do projeto em um arquivo ```.zip```

<!-- ### Front-end Web

Clone the project

```bash
  git clone thsi project
```

Enter the project directory

```bash
  cd ignite-todolist
```

Install with dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```
--->
## Na AWS

- Acessar o console da AWS
- Criar uma função no serviço AWS Lambda
- Fazer o upload do conteúdo do arquivo ```.zip``` no código da função
- Acessar o serviço AWS API Gateway
- Criar uma API Websocket
- Criar os endpoints (obs: os três primeiros endpoints marcados com ```$``` são padrão de uma API Websocket do API Gateway):
    - ```$connect```
    - ```$disconnect```
    - ```$default```
    - ```setName```
    - ```sendPublic```
    - ```sendPrivate```
    - ```sendBot```

## Testando o Websocket

- Baixar a dependência ```wscat``` através do comando ```npm i -g wscat```. 
- Utilizar o parâmetro ```-g``` para instalar de forma global no sistema operacional, podendo chamá-la de fora do projeto.

### Utilizando o wscat

- ```wscat -c url_de_conexao_do_websocket```
- Exemplo de chamada ```{"action":"sendPublic", "message":"Hello World!"}```

<!-- 
## 🌎 License

This project is under the MIT license. See the [LICENSE](https://choosealicense.com/licenses/mit/) file for more details.-->
