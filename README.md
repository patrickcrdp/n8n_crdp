# n8n – Automação em Ambiente Cloud (Render)

## Descrição do Projeto

Este projeto utiliza o **n8n**, uma ferramenta de automação de código aberto, com o objetivo de executar fluxos de automação de forma contínua (24/7) sem custos financeiros.

Para isso, foi configurada a imagem do n8n para rodar na plataforma **Render**, explorando o plano gratuito como alternativa de hospedagem.

---

## Objetivo

- Executar automações de forma contínua (24 horas por dia, 7 dias por semana)
- Utilizar uma solução open source
- Evitar custos com infraestrutura e servidores pagos
- Testar a viabilidade de automações em ambiente cloud gratuito

---

## Abordagem Técnica

- Uso da imagem oficial do n8n
- Deploy em ambiente cloud gratuito (Render)
- Configuração básica para execução de fluxos de automação
- Testes de disponibilidade e estabilidade do serviço

---

## Limitações Encontradas

Apesar de funcionar inicialmente, a solução apresentou limitações importantes:

- O servidor do Render entra em modo de suspensão após um período sem movimentação
- Caso não haja execuções frequentes nas automações, o serviço é desativado automaticamente
- Isso impede a execução contínua real em ambiente gratuito

Essas limitações tornam a solução inviável para uso totalmente contínuo (24/7) sem estratégias adicionais, como:
- Execuções periódicas artificiais
- Uso de planos pagos
- Migração para servidores próprios (VPS)

---

## Aprendizados

- Compreensão prática sobre deploy de aplicações open source
- Entendimento das limitações de ambientes cloud gratuitos
- Importância de considerar disponibilidade e uptime em projetos de automação
- Experiência com infraestrutura básica e automação em nuvem

---

## Observação

Este projeto teve caráter experimental e educacional, contribuindo para o aprendizado em automação de processos, infraestrutura cloud e análise de viabilidade técnica de soluções sem custo.

---

## Tecnologias Utilizadas

- n8n (Open Source)
- Docker / Imagem oficial do n8n
- Render (plataforma cloud)
