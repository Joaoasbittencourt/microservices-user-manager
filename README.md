# Serviços users-manager

O objetivo desse repositorio é rodar toda infra-estrutura necessária para a aplicação "users-manager" rodar https://github.com/Joaoasbittencourt/users-manager.

## Como rodar:

1. Certifique-se de ter docker instalado
2. execute o commando abaixo para clonar todos os repositorios necessários:
```bash
git clone https://github.com/Joaoasbittencourt/users-manager &&\
git clone https://github.com/Joaoasbittencourt/user-service &&\
git clone https://github.com/Joaoasbittencourt/fake-store-service
```

3. execute para `docker compose --profile default up --build` para rodar todos os serviços necessários.

4. Acesse http://localhost:3000 para acessar a aplicação principal.
