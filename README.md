# Serviços users-manager

O objetivo desse repositorio é rodar toda infra-estrutura necessária para a aplicação "users-manager" rodar https://github.com/Joaoasbittencourt/users-manager.

## Como rodar:

1. Certifique-se de ter docker instalado
2. execute o commando abaixo para clonar todos os repositorios necessários e rodar todos os containers necessários:

```bash
git clone https://github.com/Joaoasbittencourt/users-manager &&\
git clone https://github.com/Joaoasbittencourt/user-service &&\
git clone https://github.com/Joaoasbittencourt/fake-store-service &&\
docker compose --profile default up --build
```
