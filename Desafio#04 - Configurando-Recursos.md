# Configurando Recursos | VMs

![5f934966a1d20bae1909c9ef2278bd4c](https://github.com/user-attachments/assets/dcc06fd0-ceb3-402d-9f07-31a06329bbb3)

## Passo a Passo para Criar Sua VM

### 1. Acesse o Portal do Azure 🌐

1. Entre no [Portal do Azure](https://portal.azure.com).
2. No painel, procure por “Máquinas Virtuais” e clique em **"Criar"**. 


### 2. Configure a Máquina Virtual ➕

1. **Nome da VM**: Escolha um nome fácil de lembrar.

   ![2](https://github.com/user-attachments/assets/2d30f6bd-ed9f-42a2-8d81-c5f3a98b0d48)

3. **Região**: Selecione a região mais próxima dos seus usuários para melhor performance.

   ![3](https://github.com/user-attachments/assets/7753a722-46b0-46bc-87b6-612a907efcaf)

5. **Imagem**: Escolha o sistema operacional (Windows ou Linux) que você quer usar.

   ![4](https://github.com/user-attachments/assets/cd7963d9-03d7-40b5-b0f9-4e6cf6800f40)

7. **Tamanho**: Selecione o tamanho da VM com base nas suas necessidades de CPU e memória.
   
   ![8](https://github.com/user-attachments/assets/2fac5ad0-3cee-4e84-8839-2e2b27381126)

   Importante!
   ![Importante](https://github.com/user-attachments/assets/a75f4971-63b3-456c-844d-b9eb78a27b40)

### 3. Configure o Dimensionamento da VM 📏

1. **Dimensionamento Manual**: Escolha um tamanho de VM baseado na carga de trabalho que você espera. O Azure oferece uma variedade de tamanhos de VM, desde opções básicas para tarefas leves até opções robustas para aplicações exigentes. 

   ![5 D](https://github.com/user-attachments/assets/b7529669-1546-4a45-89b6-dd40d4f6a833)

   ![6](https://github.com/user-attachments/assets/e053e210-c33b-4972-8f28-98b4506a8448)

3. **Dimensionamento Automático**: Configure a autoescala para ajustar automaticamente os recursos da VM com base na demanda. Isso é útil se você tem variações significativas no uso ou precisa garantir que a VM possa lidar com picos de carga. 
  
4. **Utilize o Azure Advisor**: O Azure Advisor fornece recomendações de dimensionamento com base no desempenho atual da sua VM. Ele pode sugerir ajustes para economizar custos ou melhorar o desempenho. 

### 4. Configure a Rede 🌐

1. **Rede Virtual**: Crie uma nova rede ou escolha uma existente.
3. **Sub-rede**: Escolha a sub-rede para conectar sua VM.
4. **Grupo de Segurança de Rede (NSG)**: Defina regras para controlar o tráfego de entrada e saída da VM. Só permita o tráfego que você realmente precisa.

### 5. Defina Credenciais 🔑

1. **Nome de Usuário e Senha**: Configure um usuário e senha fortes para acessar sua VM.
2. **Chaves SSH (para Linux)**: Se for Linux, use chaves SSH para se conectar com mais segurança.
    
   ![9](https://github.com/user-attachments/assets/fcc5cad0-0bbc-4970-bbee-af8bbcc022b3)

### 6. Configurações Adicionais ⚙️

1. **Monitoramento**: Habilite o monitoramento para ficar de olho no desempenho da VM.
2. **Tags**: Adicione tags para organizar melhor seus recursos.
   
   ![12 Monitoramento](https://github.com/user-attachments/assets/6cc0de46-79ff-455d-82e7-cc6c5610a071)

### 7. Revise e Crie 🔍

1. Confira todas as configurações.
2. Clique em **"Criar"** e aguarde enquanto o Azure prepara sua VM.
   
   ![13 Revisar](https://github.com/user-attachments/assets/ba2acd64-bbbb-4f04-af56-fb29b80e67de)

### 8. Conecte-se à Sua VM 🌟

1. **Para Windows**: Use Remote Desktop (RDP) para se conectar.
2. **Para Linux**: Use SSH para acessar a VM.

# Cuidados Importantes para Produção

## 1. **Segurança**

- **Configuração do NSG**: Defina regras de firewall para proteger sua VM. Bloqueie tudo que não é necessário.
- **Atualizações**: Mantenha o sistema e aplicativos atualizados.
- **Gerenciamento de Credenciais**: Use senhas fortes e considere ferramentas como Azure Key Vault para gerenciar segredos.

## 2. **Desempenho**

- **Tamanho Adequado**: Escolha o tamanho certo da VM para evitar problemas de desempenho.
- **Autoescala**: Configure o dimensionamento automático se sua carga de trabalho variar muito.

## 3. **Backup**

- **Backups Regulares**: Garanta que backups sejam feitos frequentemente.
- **Plano de Recuperação**: Tenha um plano de recuperação em caso de falhas.

## 4. **Monitoramento**

- **Acompanhe o Desempenho**: Use ferramentas de monitoramento para verificar como a VM está funcionando.
- **Relatórios**: Gere relatórios para ficar de olho no uso e na segurança.

## 5. **Custo**

- **Controle de Custos**: Acompanhe o uso e ajuste suas configurações para não gastar mais do que o necessário.

  ![aa](https://github.com/user-attachments/assets/1063db34-76fd-4fb6-90e8-2007105aaa02)
