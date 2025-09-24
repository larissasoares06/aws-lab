# aws-lab
Registro de conhecimentos em gerenciamento de instâncias EC2 na AWS.
## 📌 Objetivo do Projeto
Este laboratório tem como objetivo consolidar os conhecimentos adquiridos sobre **gerenciamento de instâncias EC2 na AWS**

**Oque é a instância EC2**
 - EC2 – Elastic Compute Cloud, são as máquinas virtuais na AWS, podendo ser com sistema operacional Windows ou Linux.
 - Pode ser composta por CPU, memória, disco, rede e Sistema Operacional
 - É do tipo IAAS (infraestrutura como serviço)
 - Fornece a capacidade de computação na cloud da AWS
 - As imagens de máquina da Amazon estão disponíveis para escolha no momento da criaçãO

**Otimizando Recursos**
 ---> Tudo em relação a otimizar recursos é poupando custos desnessários. Como:
 - Desligando instâncias não usadas
 - Reovendo recursos não usados
 - Escalar recursos de forma horizontal ou vertical
     - Horizontal: adicionando o número de recursos
     - Vertical: acrescentando ou reduzindo a capacidade de um recurso em um mesmo nó.
       
 - INTÂNCIAS SOB DEMANDA: são compradas a uma taxa fixa por hora e são recomendadas para aplicativos com cargas de trabalho irregulares de curto prazo que não podem ser interrompidas.
 - INSTÂNCIAS RESERVADAS: podem ser mais baratas, porém é necessário manter pelo ano inteiro.
 - INSTÂNCIAS SPOT: possuem um desconto de até 90%, porém podem ser encerradas pela AWS a qualquer momento.


**Amazon EBS**
 - É uma storage confiável que pode ser anexado em qualquer instância EC2.
 - Possui a capacidade de expansão de forma rápida (como conectar um HD externo), podendo criar novas partições em uma instância


**Amazon S3**
 - É um serviço de armazenmento deobjetos em nuvem (ideal para grandes volumes de dados )
   - S3 Standard (bastante utilizado)
   - S3 Standard IA
   - S3 one zone
   - S3 Glacier
 - A maioria possui alta disponilidade (99,999999999%)
 - O ciclo d evida permite fazer a transição de objetos e migrar automaticamente para a classe Glacier


 ----> Insights e Aprendizados
 A partir dos meus estudos (dentro e fora do DIO) pude perceber a
- Importância de configurar corretamente Security Groups para liberar portas (22, 80, 443).
- Diferença entre parar (`stop`) e encerrar (`terminate`) a instância.
- Gerenciamento de custos na AWS usando instâncias do Free Tier.
- Boas práticas no uso de chaves privadas e segurança.

