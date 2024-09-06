# Gerenciando Políticas | Azure 

![d47s57m-8d67f32a-1347-4f97-be00-bd9355d20683](https://github.com/user-attachments/assets/513750be-5620-46bc-9c7a-b9743afd1267)

## 1. Portal de Confiança do Azure

O Portal de Confiança do Azure é uma plataforma que oferece visibilidade e controle sobre a conformidade e a segurança dos seus recursos no Azure. Ele fornece informações sobre práticas recomendadas, conformidade com normas e a segurança dos dados. Para acessar e utilizar o Portal de Confiança, siga estes passos:

1. **Acesse o Portal de Confiança**:

  ![st1](https://github.com/user-attachments/assets/d26a5f83-a5e9-46c3-b720-abc8a66bf8ae)

Este portal facilita a gestão de políticas de conformidade e ajuda a garantir que seus recursos estejam alinhados com as melhores práticas de segurança e as exigências regulatórias. O Portal de Confiança inclui uma visão geral das certificações e do cumprimento de normas do Azure, permitindo que você avalie rapidamente o estado de conformidade e identifique áreas que necessitam de atenção.

---

## 2. Preview do Azure

O Preview do Azure permite que você experimente novos serviços e funcionalidades antes de serem lançados oficialmente. Para começar a usar um recurso em Preview, siga estes passos:

1. **Acesse o Portal do Azure**:
   - Faça login no [Portal do Azure](https://portal.azure.com/).
   
![p1](https://github.com/user-attachments/assets/42630b4e-17e3-45f8-af66-5530669c930e)

2. **Navegue para 'Todas as funções'**:
   - No menu de navegação à esquerda, selecione **"Todos os serviços"** e procure por recursos em Preview.

    ![p4](https://github.com/user-attachments/assets/d96e5382-03c9-46e7-bdf1-47c19db11d4a)

3. **Selecione e Ative o Preview**:
   - Escolha o recurso que você deseja experimentar e siga as instruções para ativar o Preview.
   - Esteja ciente de que recursos em Preview podem não ser totalmente estáveis e podem ter funcionalidades limitadas.
   
    ![p5](https://github.com/user-attachments/assets/d0c9bb70-b5a5-4c2c-a212-62948464786b)
   
    ![p6](https://github.com/user-attachments/assets/3a6ae280-4154-4eac-bf67-237ef93c6de0)

---

## 3. Bloqueio de Recursos

O Bloqueio de Recursos no Azure permite que você impeça a exclusão ou modificação acidental de recursos críticos. Para criar um bloqueio de recurso, siga estes passos:

1. **Acesse o Portal do Azure**:
   - Faça login no [Portal do Azure](https://portal.azure.com/).

2. **Navegue até o Recurso**:
   - No menu de navegação à esquerda, selecione **"Recursos"** e escolha o recurso que você deseja proteger.
  
    ![b1](https://github.com/user-attachments/assets/0f05e346-ce1a-438b-a278-6bce50c1eec7)

3. **Configure o Bloqueio**:
   - No painel do recurso, selecione **"Bloqueios"**.
   - Clique em **"Adicionar bloqueio"** e escolha um tipo de bloqueio:
     - **ReadOnly**: Impede alterações, mas permite leitura.
     - **CanNotDelete**: Impede exclusão do recurso.

    ![b2](https://github.com/user-attachments/assets/9252881c-c359-4a28-9484-4f5d245a9a0f)

4. **Defina o Nome e Descrição**:
   - Insira um nome e uma descrição para o bloqueio.
   - Clique em **"Salvar"** para aplicar o bloqueio ao recurso.
   
    ![b3](https://github.com/user-attachments/assets/7df17666-dcd2-4903-a492-0f9f391de4ed)

    ![b4](https://github.com/user-attachments/assets/c3f2d14c-d801-4060-98f0-36a4be58f035)

---

## 4. Gerenciamento de Policies

O gerenciamento de políticas no Azure ajuda a garantir que os recursos estejam em conformidade com as normas e regulamentos da sua organização. Para criar uma política, siga estes passos:

1. **Acesse o Portal do Azure**:
   - Faça login no [Portal do Azure](https://portal.azure.com/).

2. **Navegue para 'Azure Policy'**:
   - No menu de navegação à esquerda, selecione **"Azure Policy"**.
   
    ![po1](https://github.com/user-attachments/assets/829c0fc2-8a77-4ed5-8bf0-35633c2fd3f8)

3. **Crie uma Nova Política**:
   - Selecione **"Definitions"** e clique em **"New Policy Definition"**.
   - Defina os critérios e a política que você deseja aplicar.


    ![po2](https://github.com/user-attachments/assets/555625c8-8d36-4e30-a10b-0f94416160ba)

    ![po3](https://github.com/user-attachments/assets/50452de8-9a48-441d-aec0-70494a319374)

5. **Aplique a Política**:
   - Após definir a política, selecione **"Assignments"** e clique em **"Assign Policy"**.
   - Escolha a política criada e defina o escopo de aplicação (como um grupo de recursos ou uma assinatura).

    ![po 4](https://github.com/user-attachments/assets/041decfb-554c-46e3-976a-d07845ace5e9)

    Importante: Selecione se quer deixar ativado a policy ou não. ![po5](https://github.com/user-attachments/assets/c5715181-b90a-42b9-aed6-5f800c60ad81)

    ![po6](https://github.com/user-attachments/assets/0a22919e-2942-4c15-b15f-36d25ae5d867)

    ![po7](https://github.com/user-attachments/assets/1ccc3df1-d55c-4f8a-bc0b-45b60738902c)

6. **Revise e Salve**:
   - Revise os detalhes e clique em **"Create"** para aplicar a política.

---
