# Conductor - DevOps/SRE

O teste de SRE é composto pela construção de uma **pipeline** e o IAC do cluster que o deploy da aplicação será hospedada.
Segue abaixo as informações relevantes sobre esta aplicação:

- É construída em Java;
- A forma de conexão dela é TCP;
- É uma aplicação que não pode ter downtime (nem de poucos segundos);
- Essa aplicação tem dependências externas;

## Pipeline

- A pipeline deverá conter os passos que você julga relevante existir em uma pipeline de entrega continua.
- Deve-se apresentar o GitFlow da aplicação
- O deploy deve ocorrer em um cluster de Kubernetes Service (AKS ou GKE)
- Opcionalmente o deploy deve utilizar o Helm (diferencial)

#### O resultado deve conter um documento de texto (pdf, markdown, git, etc) contendo o passo-a-passo para subir essa pipeline e aplicação, documentação relevante (se houver) e o IAC de forma reprodutível.


## Avaliação

Discutiremos como essa pipeline poderia atender um time com a entrega continua de uma aplicação e quais as melhorias poderiam vir a ter.