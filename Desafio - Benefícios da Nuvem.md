# Redundância - SLA
![9c7lhx7ijif11](https://github.com/user-attachments/assets/41d10d40-2b06-407d-b569-ca2f9ac80714)

Com base nas aulas vistas anteriormente, é possível dizer que a porcentagem do SLA será definida a partir de vários fatores, um deles é a redundância, que será aplicada em algum serviço (VM por exemplo) que será criado.

- LRS (Armazenamento com redundância local):
    Quando criado uma VM tendo sua redundância como LRS significa que ela não esta em um cenário crítico, aonde não sera movido dados de extrema importância.

- GZRS (Armazenamento de redundância zona geográfica):
    Quando criado uma VM tendo sua redundância como GZRS, esta visando a segurança dos dados, sendo eles de extrema importância. Portando, é estabelecido esse nível de redundância quando a máquina é criada em um cenário de dados críticos.
