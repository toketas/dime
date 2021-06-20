# Proposta
## Arquitetura
Para as duas opções proponho um servidor para a comunicação com o banco de dados, foi adicionado um banco de dados a partir do momento que foi mencionado 'Armazenar os dados cadastrais de cada usuário, empresa, etc.'

O elemento 'Servidor' pode ser dividido em dois microsserviços: 
1. Processamento dos dados 
2. Interface do banco de dados. 
## 1. Plataforma Web
![GitHub Logo](/2021-06-18_18-30.png)
Prós:
 - Capacidade técnica (menos custo de desenvolvimento e manutenção - opinião pessoal)
 - Não requer baixar app e instalar
 - Configuração centralizada (em relação as alterações dos pesos), já reflete para todos os usuários
 - Mobile e Desktop (multi-plataforma)

Contras:
 - Somente on-line
 - Requer um domínio (apesar de que já seria necessário ter um)

## 2. App Mobile
![GitHub Logo](/2021-06-18_18-30_1.png)
Prós:

 - Funciona Offline (com algumas ressalvas)

 - Portabilidade é mais limitada (menos possilibidades -> menos trabalho)

Contras:

 - Requer instalação

 - Pra funcionar offline precisa garantir a sincronização das configurações de pesos, o que aumenta bastante a complexidade de desenvolvimento
## Linguagens (frameworks)
Mobile - React Native

Plataforma Web - Javascript -> React JS, NextJS

Servidor - Node -> Express

Banco de Dados - PostgreSQL / MongoDB

Infraestrutura - AWS ou DigitalOcean
## Considerações
Não inclui na proposta as ferramentas de SEO (Search Engine Optimization) nem análise de tráfego (Analytics).

Não inclui na proposta manutenção do sistema após entregue, a menos que seja acordado em ambas as partes.

A finalização do projeto se dá na entrega de todos os requisitos documentados pelo próprio contratante.
