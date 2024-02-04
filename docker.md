]
Este é um guia rápido dos principais comandos do Docker, uma plataforma de código aberto para desenvolvimento, envio e execução de aplicativos em contêineres. Contêineres permitem empacotar uma aplicação e suas dependências em um ambiente isolado, tornando a execução consistente e fácil de gerenciar.

## Instalação do Docker

Para instalar o Docker em diferentes sistemas operacionais, consulte a [documentação oficial do Docker](https://docs.docker.com/get-docker/).

## Comandos Básicos

1. **`docker version`**
   - Exibe a versão do Docker instalada.
   ```bash
   docker version
   ```

2. **`docker info`**
   - Exibe informações detalhadas sobre a instalação do Docker.
   ```bash
   docker info
   ```

3. **`docker pull`**
   - Baixa uma imagem do Docker Hub para o seu sistema.
   ```bash
   docker pull nome_da_imagem
   ```

4. **`docker images`**
   - Lista todas as imagens disponíveis no sistema.
   ```bash
   docker images
   ```

5. **`docker ps`**
   - Lista todos os contêineres em execução.
   ```bash
   docker ps
   ```

6. **`docker ps -a`**
   - Lista todos os contêineres, incluindo os que estão parados.
   ```bash
   docker ps -a
   ```

7. **`docker run`**
   - Cria e inicia um contêiner com base em uma imagem.
   ```bash
   docker run nome_da_imagem
   ```
   - Adicione `-it` para interação interativa.

8. **`docker exec`**
   - Executa um comando dentro de um contêiner em execução.
   ```bash
   docker exec -it nome_do_contêiner comando
   ```

9. **`docker stop`**
   - Para a execução de um ou mais contêineres.
   ```bash
   docker stop nome_do_contêiner
   ```

10. **`docker rm`**
    - Remove um ou mais contêineres.
    ```bash
    docker rm nome_do_contêiner
    ```

11. **`docker rmi`**
    - Remove uma ou mais imagens.
    ```bash
    docker rmi nome_da_imagem
    ```

12. **`docker build`**
    - Constrói uma imagem a partir de um Dockerfile.
    ```bash
    docker build -t nome_da_imagem caminho_do_dockerfile
    ```

13. **`docker-compose`**
    - Utilizado para definir e executar aplicativos Docker multi-container.
    ```bash
    docker-compose up -d
    ```
    - `-d` executa em segundo plano.

14. **`docker logs`**
    - Exibe os logs de um contêiner em execução.
    ```bash
    docker logs nome_do_contêiner
    ```

15. **`docker network`**
    - Gerencia redes no Docker.
    ```bash
    docker network ls
    ```
16. ** `    docker rm -f $(docker ps -aq)   ` **
    - Para remover todos os containers:
16. ** ` docker rmi -f $(docker images -aq)  ` **
    - Para remover todas os imagens :

Este é um guia básico e há muitos outros comandos e opções disponíveis. Consulte a [documentação oficial do Docker](https://docs.docker.com/) para obter informações mais detalhadas sobre cada comando e conceitos relacionados ao Docker.
```

Copie o texto acima e cole no seu arquivo de texto. Se precisar de mais alguma coisa, estou à disposição!