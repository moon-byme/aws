# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

* **Data:** 18/01/2026
* **Empresa:** Abstergo Industries
* **Responsável:** Lethycia Zenaide

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Lethycia Zenaide. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos para a operação de distribuição farmacêutica.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

### Etapa 1: Amazon S3 Intelligent-Tiering
- **Foco da ferramenta:** Otimização automática de custos de armazenamento.
- **Descrição de caso de uso:** A Abstergo armazena uma grande quantidade de notas fiscais, imagens de produtos e históricos de transações. Com o S3 Intelligent-Tiering, os dados que não são acessados frequentemente (ex: notas fiscais antigas) são movidos automaticamente para camadas de armazenamento mais baratas, gerando economia imediata sem necessidade de intervenção manual.

### Etapa 2: AWS Lambda
- **Foco da ferramenta:** Computação sem servidor (Serverless) / Redução de custos com infraestrutura ociosa.
- **Descrição de caso de uso:** Substituição de servidores EC2 que ficavam ligados 24/7 apenas aguardando pedidos. Com o AWS Lambda, o código para processar pedidos de compra e atualizações de estoque é executado apenas quando uma ação ocorre (ex: uma farmácia parceira envia um pedido). A empresa paga apenas pelos milissegundos de execução, eliminando custos de servidores ociosos durante a madrugada ou finais de semana.

### Etapa 3: AWS Cost Explorer
- **Foco da ferramenta:** Gestão Financeira e Visualização de Custos.
- **Descrição de caso de uso:** Implementação de painéis para monitorar o consumo da nuvem em tempo real. A ferramenta permite identificar quais recursos estão subutilizados, prever gastos futuros e identificar tendências de desperdício, permitindo que a equipe de TI tome decisões baseadas em dados para manter o orçamento sob controle.

## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado a redução dos custos operacionais (OpEx) e a flexibilidade da infraestrutura, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias, como o uso de Savings Plans para cargas de trabalho constantes, que possam melhorar ainda mais os processos da empresa.

## Anexos

- [Documentação Oficial AWS S3](https://aws.amazon.com/s3/)
- [Guia de Preços AWS Lambda](https://aws.amazon.com/lambda/pricing/)
- [Manual de Gestão de Custos AWS](https://aws.amazon.com/aws-cost-management/)

Assinatura do Responsável pelo Projeto:

Lethycia Zenaide
