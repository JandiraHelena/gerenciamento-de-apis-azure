# gerenciamento-de-apis-azure
Este repositório foi criado como parte do curso Gerenciamento de APIs com Azure API Management, com o objetivo de documentar o processo de criação, publicação e gerenciamento de APIs utilizando os recursos oferecidos pela plataforma da Microsoft.

Descrição do Projeto
O projeto consiste na criação de uma instância do Azure API Management (APIM) e na publicação de uma API exemplo, demonstrando as principais funcionalidades da plataforma, como políticas de segurança, monitoramento e versionamento.

Etapas Realizadas
Criação da Instância do APIM: Utilizando o portal do Azure, cria-se uma nova instância do Azure API Management, configurando os parâmetros básicos como nome, região e grupo de recursos.
Configuração de Políticas: Aplicação das políticas de segurança, como validação de tokens e limitação de chamadas (rate limiting), para proteger a API contra acessos não autorizados e abusivos.
Monitoramento com Application Insights: Integrando o APIM com o Application Insights, é possível coletar métricas e logs detalhados sobre o uso da API, auxiliando na identificação de possíveis problemas e no aprimoramento contínuo.
Publicação no Portal do Desenvolvedor: A API publicada no portal do desenvolvedor fornecido pelo APIM, permite que outros desenvolvedores descubram e testem a API de forma intuitiva.

Insights e Aprendizados
Facilidade de Gerenciamento: O Azure API Management oferece uma interface intuitiva para gerenciar APIs, facilitando tarefas como importação, versionamento e aplicação de políticas de segurança.
Segurança Robusta: A aplicação de políticas como validação de tokens JWT e limitação de chamadas permite proteger as APIs contra acessos indevidos e garantir a disponibilidade dos serviços.
Monitoramento Eficiente: A integração com o Application Insights proporciona uma visão detalhada do uso das APIs, permitindo identificar gargalos e otimizar o desempenho.
Experiência do Desenvolvedor: O portal do desenvolvedor oferece uma plataforma amigável para que outros desenvolvedores descubram, testem e integrem as APIs em seus aplicativos.

Possibilidades Futuras
Automatização com DevOps: Integrar o APIM com pipelines de CI/CD para automatizar o processo de publicação e atualização das APIs.
Monetização de APIs: Explorar os recursos de monetização do APIM para criar planos de assinatura e gerar receita com o uso das APIs.
Expansão para Microsserviços: Utilizar o APIM como gateway para uma arquitetura baseada em microsserviços, facilitando a gestão e a comunicação entre os serviços.
