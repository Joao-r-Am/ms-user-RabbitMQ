# Microsserviço Usuário e RabbitMQ

---

### Neste microsserviço é realizado a criação do usuário

Ao criar o usuário uma mensagem é disparada para a fila do RabbitMQ, após isso o [microsserviço de email](https://github.com/Joao-r-Am/ms-email-RabbitMQ) recebe e encaminha para o email do usuario cadastrado.
