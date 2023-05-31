# Exemplo Docker App
<p>Exemplo de aplicação Docker File</p>

<p>Executar o Docker Desktop na máquina</p>
<p>Docker Hub: https://hub.docker.com/</p>

# Comandos 

> <p>Cria a imagem como o nome "app" </p>
* <p>docker build -t app:v1 .</p>
> <p>Sobe o container "app" </p>
* docker run -dp 3000:3000 app
> <p>Visualiza imagens</p>
* <p>docker images</p>
>  <p>Login no Docker Hub</p>
* <p>docket login</p>
>  <p>Publica no Docker Hub</p>
* <p>docker push fernandazaccarorigolin/app:v1</p>

# Imagem do aplicativo de exemplo

![Home](src/static/images/App.png)
