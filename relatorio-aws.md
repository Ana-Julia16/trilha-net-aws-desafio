# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 25/08/2025
**Empresa:** Abstergo Industries 
**Responsável:** Ana Julia Arantes Ramos

## Introdução
Este relatório apresenta uma proposta estratégica para a implementação de três serviços da Amazon Web Services (AWS) na Abstergo Industries. O objetivo principal do projeto é a redução de custos operacionais e de infraestrutura de forma imediata, otimizando nossos investimentos em tecnologia e aumentando a eficiência financeira do departamento de TI.

## Descrição do Projeto
O projeto foi estruturado em 3 etapas, cada uma focada em uma área de alto custo atual. A implementação destes serviços resultará em uma economia substancial, convertendo despesas de capital (CapEx) em despesas operacionais (OpEx) variáveis e mais baixas.

### Etapa 1: Otimização do Armazenamento de Dados
- **Nome da ferramenta:** Amazon S3 com Gerenciamento de Ciclo de Vida (Intelligent-Tiering).
- **Foco da ferramenta:** Redução de custos com armazenamento de arquivos, backups e documentos.
- **Descrição de caso de uso:** Atualmente, a Abstergo Industries armazena um volume crescente de dados (documentos, backups de sistema, arquivos de projetos antigos) em servidores locais caros e de alta performance, independentemente da frequência de acesso. Com o Amazon S3, armazenaremos esses dados em nuvem com um custo por Gigabyte drasticamente menor. Utilizando a política de "Intelligent-Tiering", o próprio sistema moverá automaticamente arquivos menos acessados para camadas de armazenamento ainda mais baratas (arquivamento), garantindo que paguemos o mínimo possível, sem a necessidade de gerenciamento manual e liberando espaço em nossos sistemas primários. A economia estimada apenas nesta etapa é superior a 60% dos custos atuais de armazenamento de dados não críticos.

### Etapa 2: Flexibilização da Capacidade Computacional
- **Nome da ferramenta:** Amazon EC2 com Auto Scaling.
- **Foco da ferramenta:** Eliminar gastos com capacidade de processamento ociosa.
- **Descrição de caso de uso:** Nossos sistemas internos e portais para clientes possuem picos de demanda durante o horário comercial e ociosidade durante a noite e fins de semana. No entanto, mantemos uma infraestrutura dimensionada para o pico, pagando por ela 24/7. Com o EC2 Auto Scaling, a nossa infraestrutura se ajustará dinamicamente à demanda: mais recursos serão alocados nos momentos de pico e reduzidos ao mínimo nos períodos de baixa utilização. O resultado é que pagaremos apenas pela capacidade computacional que efetivamente usamos, eliminando o desperdício e reduzindo os custos com servidores em até 40%.

### Etapa 3: Automação de Tarefas sem Servidores
- **Nome da ferramenta:** AWS Lambda.
- **Foco da ferramenta:** Reduzir custos operacionais através da execução de tarefas sob demanda.
- **Descrição de caso de uso:** Diversas tarefas de rotina, como a geração de relatórios noturnos, processamento de logs ou a automação de backups, hoje exigem servidores dedicados que ficam a maior parte do tempo ociosos. O AWS Lambda nos permite executar essas tarefas sem um servidor. O código é executado apenas quando necessário e somos cobrados apenas pelos milissegundos de execução. Isso elimina completamente o custo associado a um servidor (manutenção, energia, licenciamento e ociosidade) para essas funções, representando uma otimização de custo que pode chegar a 90% para processos automatizados.

## Conclusão
A implementação destes três serviços AWS na Abstergo Industries tem como esperado uma **redução significativa e imediata nos custos de TI**, além de aumentar a agilidade e a segurança da nossa infraestrutura. A transição para um modelo de pagamento conforme o uso otimizará nosso orçamento, liberando capital para ser investido em inovação e no core business da empresa. Recomenda-se a aprovação deste projeto para iniciarmos a implementação e a colheita dos benefícios financeiros o mais breve possível.

## Anexos

- Projeção de Economia Detalhada (Q4 2025).
- Cronograma Proposto para Implementação.
- Análise Comparativa de Custos: Modelo Atual vs. Modelo AWS.

---

**Assinatura do Responsável pelo Projeto:**

![Assinatura de Ana Julia Arantes Ramos](./assinatura.png)
Ana Julia Arantes Ramos
