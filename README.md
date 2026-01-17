# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 17/01/2026
Empresa: Abstergo Industries 
Responsável: Gabriel Felix Alexandre dos Santos

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Gabriel Felix Alexandre dos Santos. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

## Etapa 1 – AWS Cost Explorer
Nome da Ferramenta:

AWS Cost Explorer

Foco da Ferramenta:

Análise, visualização e controle de custos

Caso de Uso:

O AWS Cost Explorer é utilizado como ponto inicial do projeto, permitindo à empresa visualizar detalhadamente os gastos com serviços AWS.
Por meio de gráficos e relatórios personalizados, é possível identificar recursos subutilizados, picos de consumo e tendências de gastos ao longo do tempo.

## Etapa 2 – Amazon EC2 Auto Scaling

Foco da Ferramenta:
Ajuste automático da infraestrutura conforme a demanda

Caso de uso:
A partir dos dados obtidos pelo AWS Cost Explorer, a Abstergo pode identificar padrões de uso e aplicar o Amazon EC2 Auto Scaling para otimizar seus recursos computacionais.
Essa ferramenta ajusta automaticamente a quantidade de servidores em funcionamento de acordo com a demanda real, evitando custos com infraestrutura ociosa. Em horários de menor movimento, menos recursos são utilizados; em períodos de pico, o sistema escala automaticamente para manter o desempenho.
Assim, o Auto Scaling complementa a etapa anterior ao agir diretamente sobre os pontos de custo identificados, tornando a operação mais eficiente.

##Etapa 3 – Amazon S3 Intelligent-Tiering

Foco da Ferramenta:
Redução de custos com armazenamento de dados

Caso de uso:
Após otimizar os custos computacionais, a Abstergo pode avançar para a redução dos custos de armazenamento com o Amazon S3 Intelligent-Tiering. Essa ferramenta analisa automaticamente os padrões de acesso aos dados e move os arquivos entre camadas de armazenamento mais econômicas quando o acesso diminui.
Relatórios antigos, registros regulatórios e históricos de vendas podem ser armazenados de forma mais barata, sem impacto na disponibilidade. Dessa forma, o Intelligent-Tiering complementa as etapas anteriores ao otimizar um dos principais custos remanescentes da infraestrutura em nuvem: o armazenamento.

## Conclusão

A adoção estratégica das ferramentas AWS apresentadas neste projeto demonstra como a computação em nuvem pode ser utilizada não apenas como um recurso tecnológico, mas como um instrumento de otimização financeira no setor farmacêutico.

A implementação em etapas — iniciando com a análise de custos por meio do AWS Cost Explorer, seguida pela otimização da infraestrutura com o Amazon EC2 Auto Scaling e finalizando com a redução de gastos em armazenamento utilizando o Amazon S3 Intelligent-Tiering — permite uma abordagem progressiva, integrada e eficiente de controle de custos.

Essa estratégia garante maior visibilidade sobre os gastos, uso inteligente dos recursos e adaptação automática às demandas do negócio, resultando em redução de desperdícios, maior previsibilidade financeira e aumento da eficiência operacional.

Dessa forma, a empresa Abstergo passa a contar com uma infraestrutura em nuvem mais sustentável, escalável e alinhada às necessidades do mercado, fortalecendo sua competitividade e capacidade de crescimento a longo prazo.

Assinatura do Responsável pelo Projeto:

Gabriel Felix Alexandre dos Santos
