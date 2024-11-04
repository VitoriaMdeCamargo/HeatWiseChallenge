# HeatWise

HeatWise é uma solução de análise de produtividade focada em dados de interações de usuários em sistemas e softwares. Ele permite que as empresas transformem esses dados em insights acionáveis, otimizando a performance e eficiência de suas equipes.

## Índice

- [Descrição](#descrição)
- [Funcionalidades](#funcionalidades)
- [Como Usar](#como-usar)
- [Deploy no Azure](#deploy-no-azure)


## Descrição

HeatWise coleta, processa e analisa dados de produtividade de interações em softwares. A plataforma foi desenvolvida para atender a necessidade de transformar dados brutos em informações valiosas que auxiliam no aumento da eficiência dos negócios.

## Funcionalidades

- Coleta de dados de interações de usuários em diferentes sistemas
- Análise de dados com métricas de produtividade
- Geração de relatórios e gráficos detalhados
- Integração com diferentes plataformas de software
- Interface intuitiva para visualização de dados em tempo real

## Como Usar 
Após a instalação, a aplicação estará disponível localmente no endereço da porta configurada no Azure.

## Deploy no Azure

O processo de deploy no Azure foi realizado usando o Azure Repos. Primeiro, clonei meu repositório para o Repos da minha organização `https://github.com/VitoriaMdeCamargo/HeatWiseChallenge.git`. Em seguida, criei uma aplicação web no Azure e configurei-a para se conectar ao repositório.

Depois, atualizei as variáveis de ambiente, definindo o nome `ASPNETCORE_ENVIRONMENT` com o valor `Development`. Com todas as configurações concluídas, finalizei o processo de deploy. Para verificar o resultado, acessei o domínio padrão da minha aplicação web no Azure.
