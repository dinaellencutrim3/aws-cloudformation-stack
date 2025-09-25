# aws-cloudformation-stack
aws-cloudformation-stack/
│── README.md          # documento principal com toda a explicação
│── template.yaml      # arquivo do CloudFormation (stack)
└── /images            # pasta só para prints de tela
    ├── stack-criada.png
    ├── recursos.png

# 🚀 Primeira Stack com AWS CloudFormation

## 📌 Descrição
Este repositório contém a prática realizada no desafio da **DIO - Digital Innovation One**, onde implementei minha primeira stack utilizando o **AWS CloudFormation**.  
O objetivo principal é aplicar os conceitos de **Infraestrutura como Código (IaC)**, documentar o processo e organizar os arquivos em um repositório público.

---

## 🛠️ Tecnologias Utilizadas
- **AWS CloudFormation**
- **AWS Management Console**
- **YAML/JSON** para definição de templates
- **Git & GitHub** para versionamento
- **Markdown** para documentação

---

## 📖 Passo a Passo Realizado

1. Criação de um **template** em YAML para provisionar recursos na AWS.  
2. Acesso ao **AWS Management Console** → CloudFormation.  
3. Upload do arquivo de template.  
4. Validação e criação da stack.  
5. Verificação dos recursos provisionados automaticamente.  
6. Registro de evidências (prints) e anotações sobre a experiência.

---

## 📂 Estrutura do Repositório


---

## 📸 Evidências
As capturas de tela do processo estão organizadas na pasta [/images](./images).  

---

## ✨ Insights Adquiridos
- O **CloudFormation** simplifica a criação e gerenciamento de recursos na nuvem.  
- Utilizar **YAML** torna o template mais legível e fácil de manter.  
- O conceito de **IaC (Infrastructure as Code)** é essencial para automação e escalabilidade.  
- Documentar o processo ajuda a reforçar o aprendizado e serve como base para futuros projetos.  

---

## 📌 Próximos Passos
- Adicionar **parâmetros** e **outputs** ao template.  
- Criar stacks mais complexas, incluindo **VPCs, subnets e balanceadores de carga**.  
- Explorar o uso do **AWS CLI** e **CI/CD** para deploy automatizado de stacks.  


AWSTemplateFormatVersion: "2010-09-09"
Description: "Template para criar um bucket S3 via CloudFormation"

Resources:
  MeuBucketS3:
    Type: AWS::S3::Bucket
    Properties:
      BucketName: meu-bucket-stack-exemplo-dio


