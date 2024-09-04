# Configuração de um serviço na Azure
![zpRiGBe](https://github.com/user-attachments/assets/9eb14a5a-f2b9-424c-ad53-f1e49daeccd2)

Ao analisar os tópicos para a criação de uma VM no Azure, é notável a vasta gama de opções que devemos personalizar, e diversos campos que devemos atribuir valores para assim ser criado. Com isso é de extrema importância a leitura do documento oficial do serviço que será criado (para que consiga defivir o SLA com precisão)

Opções necessárias para a criação:

- Básico
- Discos (definição de armazenamento)
- Rede (atribuir a rede que irá armazenar o serviço)
- Gerenciamento
- Monitoramento (habilitar ou não rules, monitoramento de integridade do aplicativo, diagnóstico de convidade do SO...)
- Avaçado (caso queira ser mais específico com a criação da VM)

Na criação de um DB é mostrado opções parecidas:

- Básico
- Segurança
- Rede (atribuir a rede que irá armazenar o serviço)

Além de ter que configurar esse tópicos mencionados, deve-se criar um servidor que visa fazer a alocação do DB criado.

