# Conversão de Distâncias

Aplicação Python que converte métricas de distância. Dockerizada para facilitar execução.

Link da Imagem no <a href="https://hub.docker.com/repository/docker/gabrielpiske/conversao-distanci/general">Docker Hub</a>

## **Como Usar**

### 1. Clone o Repositório
```bash
git clone https://github.com/gabrielpiske/conversao-distancia.git
cd conversao-distancia
```

### 2. Crie a Imagem Docker
```bash
docker build -t conversao-distancia
```

### 3. Rode o Contêiner
```bash
docker run -d -p 8080:5000 conversao-distancia
```

Acesse em: http://localhost:8080
