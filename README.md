# Teriyaki Docker

### Requirements

- [Git](https://git-scm.com/downloads)
- [Docker latest](https://www.docker.com/)
- [Docker-compose latest](https://docs.docker.com/compose/)

### Usage

1.  Clone repository **teriyaki-docker**:
   [https://bitbucket.org/nldanang/teriyaki-docker/src/master](https://bitbucket.org/nldanang/teriyaki-docker/src/master/)

2. Enter the teriyaki-docker folder and copy .env.example to .env
    ```
    cp .env.example .env
    ```
    You can always refer to the docker-compose.yml file to see how those variables are being used.

3.  Build the environment and run it using docker-compose
    ```
    docker-compose up -d
    ```

4.  Enter the Workspace container
    ```
    ./mi go api
    or
    ./mi ga
    ```

