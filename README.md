# leitapp_ui

## Desenvolvimento

1. Inicie o ambiente 
    ```sh
    docker-compose up -d
    ```

    > Pare o ambiente com ``docker-compose down``

    > Para comandos do yarn utilize ``docker-compose exec app yarn <complemento>``

2. Inicie o servidor
    ```sh
    docker-compose exec app yarn start
    ```

3. Acesse `localhost:3000`