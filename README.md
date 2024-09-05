# 🎓 Bootcamp AZ-900 - DIO 

![_3fYL8i6Q-n-155t3dn_4hksVs3MIJxHadG7A7FI_oTy9pL-UqrC-cycJtDkuZzC](https://github.com/user-attachments/assets/1ffece00-af0f-4c54-b2f0-bc53f163b116)

## 📁 Repositório AZ-900

Bem-vindo ao repositório do **Bootcamp AZ-900** da DIO! Aqui você encontrará alguns dos recursos e links que vou utilizar para concluir o bootcamp.

## 🗂️ O Que Você Encontrará Aqui

Este repositório está organizado para ajudar a armazenar e gerenciar todos os materiais do bootcamp.

- **📚 Recursos de Estudo**: Links e materiais recomendados para o estudo do AZ-900.
- **💻 Projetos e Desafios**: Códigos e exercícios práticos realizados durante o bootcamp.
- **🔗 Link Útil**: Link para a documentação oficial (Material de grande importância para o exame AZ-900)

## 🔍 Recursos de Estudo

Aqui você encontrará uma lista de recursos úteis para se preparar para o exame AZ-900:

- [Link para o material oficial do Azure](https://docs.microsoft.com/azure/)
- [Cursinho sobre Azure](https://www.youtube.com/watch?v=h5PNYnwApkM&list=LL&index=9)
- [Guia de Estudos](https://medium.com/@shalinds/my-two-week-journey-to-passing-the-az-900-exam-122f5f1e3732)

## 💻 Projetos e Desafios

Veja os projetos e desafios que completei durante o bootcamp:

- **Desafio 1**: [Criação de VM em Azure](https://github.com/GuylhermeI/desafio-azure-dio/blob/main/Desafio%2301%20-%20Cria%C3%A7%C3%A3o-de-VM-em-Azure.md)
- **Desafio 2**: [Configuração de um serviço na Azure](https://github.com/GuylhermeI/desafio-azure-dio/blob/main/Desafio%2302%20-%20Inst%C3%A2ncia%20de%20Banco%20de%20Dados.md)
- **Desafio 3**: [Criação de Infraestrutura no Azure](https://github.com/GuylhermeI/desafio-azure-dio/blob/main/Desafio%2303%20-%20Construindo-Arquiteturas_no_Azure.md)
- **Desafio 4**: [Configurando Recursos](https://github.com/GuylhermeI/desafio-azure-dio/blob/main/Desafio%2304%20-%20Configurando-Recursos.md)
- **Desafio 5**: [Dominando Armazenamento Azure](https://github.com/GuylhermeI/desafio-azure-dio/blob/main/Desafio%2305%20-%20Dominando-Armazenamento-Azure.md)
- **Desafio 6**: [Acesso | Microsoft Entra ID | Defender for Cloud](https://github.com/GuylhermeI/desafio-azure-dio/blob/main/Desafio%2306%20-%20Identidade-Acesso-Seguran%C3%A7a.md)

## 🔗 Azure

- [Documentação do Azure](https://docs.microsoft.com/azure/)

---

```cpp
#include <iostream>
#include <string>

int main() {
    std::string nivelEstudo;
    
    // Solicita ao usuário que informe seu nível de estudo
    std::cout << "Qual é o seu nível de estudo para o AZ-900? (Básico/Avançado): ";
    std::cin >> nivelEstudo;

    // Condicional para determinar o resultado com base no nível de estudo
    if (nivelEstudo == "Básico") {
        std::cout << "Com o conhecimento básico, você está preparado para passar no AZ-900!" << std::endl;
    } else if (nivelEstudo == "Avançado") {
        std::cout << "Com um estudo mais aprofundado, você está a caminho de se tornar um especialista em Azure!" << std::endl;
    } else {
        std::cout << "Nível de estudo desconhecido. Por favor, insira 'Básico' ou 'Avançado'." << std::endl;
    }

    return 0;
}

```
