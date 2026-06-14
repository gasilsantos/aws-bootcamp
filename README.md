Diagrama 2 

Fluxo Completo
O usuário acessa o site.
O Route 53 resolve o domínio.
O Load Balancer recebe a requisição.
O Load Balancer escolhe uma instância EC2 disponível.
A aplicação processa a solicitação.
Se necessário, consulta ou grava informações no RDS.
Os dados armazenados localmente ficam nos volumes EBS.
A resposta retorna ao usuário.
