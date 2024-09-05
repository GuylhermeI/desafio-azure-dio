# Configurando Armazenamento no Azure | Migração de Dados

![be335fd0dc86f5fda4c98e057a5e322f](https://github.com/user-attachments/assets/b9b74adf-5a0b-4f28-9a0f-873609140942)

## Passo a Passo para Configurar Armazenamento no Azure

### 1. Acesse o Portal do Azure 🌐

1. Entre no [Portal do Azure](https://portal.azure.com).
2. No painel, procure por “Conta de Armazenamento” e clique em **"Criar"**.
   
---

### 2. Configure a Conta de Armazenamento ➕

1. **Nome da Conta**: Escolha um nome único para sua conta de armazenamento.

2. **Região**: Selecione a região mais próxima para melhor performance.

3. **Tipo de Conta**: Escolha "Armazenamento General Purpose v2".
  
4. **Replicação**: Selecione o tipo de replicação desejado (ex: LRS - Locally Redundant Storage).
   
  ![qwer](https://github.com/user-attachments/assets/fe6b345d-58ff-4361-9b95-4eb5efee5639)
  
  ![qwert](https://github.com/user-attachments/assets/a32005eb-e1a7-43da-b169-5ddf0578a3fa)

5. **Proteção de Dados**: Importante habilitar exclusão temporária para blobs.
  ![qwertyu](https://github.com/user-attachments/assets/3a71b729-65e0-475e-bc25-53cfd1d75441)

6. **Finalização**
  ![wwwww](https://github.com/user-attachments/assets/553ca388-2a5e-4167-8244-c3e8e277cbd0)

  ---

### 3. Criar um Compartilhamento de Arquivos 📁

1. **Acesse Sua Conta de Armazenamento**: No portal, vá para "Recursos" e selecione sua conta de armazenamento.
   
3. **Criar um Compartilhamento de Arquivos**: 
   - No menu de "Serviços", clique em "Compartilhamento de Arquivos".
   - Clique em "Adicionar compartilhamento de arquivos".
   - Nomeie o compartilhamento e defina o tamanho.
   - Clique em "Criar".
   
![cpm1](https://github.com/user-attachments/assets/e72eb2b5-6c79-462b-bb92-1c2c8ed178a4)

![cpm2](https://github.com/user-attachments/assets/3021a822-beae-4cb0-9f75-8ed381716cb4)

![cpm3](https://github.com/user-attachments/assets/056248c7-73ca-4686-afcf-1d42bd4db918)

### 4. Migrar Dados para o Azure

1. **Criar um projeto**: 
   - Antes de tudo deve criar um projeto de migração para Azure:
     
     ![mg1](https://github.com/user-attachments/assets/7c5f908e-a660-4887-b371-7541ab8b3bf9)

    ![mg2](https://github.com/user-attachments/assets/7f16b52a-a8d9-412f-a1bd-2585b83a4fb3)
  
    ![mg3](https://github.com/user-attachments/assets/01fa4ad3-b111-470c-bf85-eeb7e7fc18ea)
  
    ![mg4](https://github.com/user-attachments/assets/52811d01-3c21-4d2a-9aa5-6782d7e44db1)
  
    ![mg5](https://github.com/user-attachments/assets/656ec0fb-b94b-4baf-8f10-9f4a48f226f7)
  
    ![mg6](https://github.com/user-attachments/assets/d9ce7dcb-bf0e-444c-8fb9-3258fe1a258b)


3. **Instalar o AzCopy**: 
   - Baixe e instale o AzCopy do site oficial: [AzCopy Download](https://docs.microsoft.com/azure/storage/common/storage-use-azcopy-v10).

    ![azc1](https://github.com/user-attachments/assets/5b2706c7-109f-45cb-ae29-76cf33543718)

    ![azc2](https://github.com/user-attachments/assets/670afcfe-38e2-4ca7-9186-c65891cd7350)

    ![azc3](https://github.com/user-attachments/assets/ed329b13-f72f-4189-8bb3-c4114663df77)


4. **Autenticar com o Azure**:
   ```bash
   azcopy login
   azcopy copy 'caminho/local/do/arquivo' 'https://<sua-conta>.file.core.windows.net/<compartilhamento>/<pasta>?<SAS-token>' --recursive

   ```
   ![azc4](https://github.com/user-attachments/assets/12ac1499-a6a5-44bf-a177-e76143e1551c)

   ![azc5](https://github.com/user-attachments/assets/fef45f4c-4c10-4cd1-9a3a-d5f49d8b8caf)

   ---

Se você encontrou algum desafio ou tem dúvidas, não hesite em abrir uma [issue](https://github.com/GuylhermeI/desafio-azure-dio/tree/main). Estou aqui para ajudar!

Desejo a você **bons estudos** e um ótimo trabalho com seus projetos! Que você continue aprendendo e se aprimorando sempre.

Ó um gatinho pra ficar esperto!

![pi7rq4EdT](https://github.com/user-attachments/assets/ce86c729-e51d-484f-a277-5f460209470b)
