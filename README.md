Este projeto consiste em um chatbot de coleta de dados via WhatsApp desenvolvido para realizar pesquisas rápidas com participantes do Carnaval de Belo Horizonte.

O sistema utiliza automação conversacional para coletar respostas estruturadas e armazená-las automaticamente em uma planilha, permitindo posterior análise e visualização em dashboard.

A arquitetura foi projetada para ser leve, escalável e de baixo custo, utilizando serviços serverless e integrações via API.
🧠 Funcionalidades

O chatbot é capaz de:

Coletar respostas de usuários via WhatsApp

Validar entradas utilizando regex

Armazenar automaticamente as respostas em planilha

Gerar IDs de entrevistados

Registrar data e hora da resposta

Converter códigos numéricos em respostas textuais

Alimentar um dashboard analítico em tempo real

Exemplos de dados coletados:

gênero

blocos frequentados

gasto médio

avaliação da experiência

recomendação do evento

percepção sobre infraestrutura
Componentes principais:

WhatsApp Business – canal de interação com usuários

Twilio Studio – orquestração do fluxo conversacional

Google Apps Script – processamento e armazenamento das respostas

Google Sheets – banco de dados leve

Dashboard em Sheets – visualização e análise dos dados
Este repositório contém o código-fonte para fins de demonstração técnica e arquitetural. Por questões de contrato e confidencialidade, a redistribuição deste software não é permitida.
