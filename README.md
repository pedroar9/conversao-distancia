
# 🚀 Projeto Conversão de Distância

## 📌 Sobre o Projeto

Este projeto foi desenvolvido em **Python** para realizar a conversão de distâncias entre diferentes unidades de medida.

Ele serve como exemplo para a **criação de um ambiente containerizado** usando  **Docker**, permitindo que a aplicação seja facilmente executada e distribuída sem a necessidade de configurar dependências manualmente.

---

## 🛠 Tecnologias Utilizadas

* [**Python 3.12**](https://www.python.org/)
* [**Flask**](https://flask.palletsprojects.com/) - Para criar a API Web
* [**Gunicorn**](https://gunicorn.org/) - Servidor WSGI para rodar a aplicação Flask
* [**Docker**](https://www.docker.com/) - Para containerização da aplicação
* [**DockerHub**](https://hub.docker.com/) - Repositório de imagens Docker

---

## 📂 Estrutura do Projeto

/conversao-distancia
│── templates                # Layout web da página
│── app.py                   # Arquivo principal da API Flask
│── requirements.txt         # Dependências do projeto
│── Dockerfile               # Arquivo para criação da imagem Docker
│── README.md                # Documentação do projeto

---

## 📦 Como Executar o Projeto

### 🔹 Clonar o Repositório

```sh
git clone https://github.com/pedroar9/conversao-distancia.git
cd conversao-distancia
```

### 🔹 Construir a Imagem Docker

```sh
docker build -t conversao-distancia .
```

### 🔹 Executar o Contêiner

```sh
docker run -p 5000:5000 conversao-distancia
```

A aplicação estará rodando em:

📍 [**http://localhost:5000**](http://localhost:5000/)

---

## 🔄 Como Usar a API

A API está configurada para converter distâncias entre diferentes unidades.

---

## 🌍 Publicação no DockerHub

A imagem do projeto está disponível no DockerHub e pode ser baixada diretamente com o comando:

```sh
docker container run pedroar9/conversao-distancia-desafio:v1
```

🔗 **Link da imagem:** [DockerHub - pedroar9/conversao-distancia-desafio](https://hub.docker.com/repository/docker/pedroar9/conversao-distancia-desafio/)

---

## 👨‍💻 Autor

**Pedro Assis**

[![Linkedin](https://i.sstatic.net/gVE0j.png) LinkedIn](https://www.linkedin.com/in/pedrocarlos-assis/) | [![GitHub](https://i.sstatic.net/tskMh.png) GitHub](https://github.com/pedroar9) | 📧 [Email](mailto:pedrocarlos.assis@gmail.com)
---

## 📝 Licença

Este projeto está sob a licença MIT - veja o arquivo [LICENSE](https://mit-license.org/) para mais detalhes.

---

