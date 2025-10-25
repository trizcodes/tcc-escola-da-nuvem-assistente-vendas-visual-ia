# Assistente de Vendas Visual com Inteligência Artificial  
### [Planejamento e Arquitetura Serverless na AWS]

Este repositório apresenta o **planejamento estratégico e a arquitetura técnica** do projeto **Assistente de Vendas Visual com IA**, desenvolvido pela **Equipe 5** como parte do **Módulo RESTART** da **Escola da Nuvem**

O objetivo central é documentar a concepção, o escopo do MVP e a proposta arquitetural baseada em **serviços serverless da AWS**, com foco em inovação, acessibilidade e impacto real no varejo digital

![Status do Projeto](https://img.shields.io/badge/Status-Em%20Planejamento-blue)
![Gerenciamento](https://img.shields.io/badge/Trello-Equipe%205-0079BF?logo=trello)

---

## 1. Contexto e Definição do Problema

Muitos clientes — especialmente pessoas idosas — enfrentam **dificuldades para encontrar produtos** em lojas físicas e virtuais quando possuem **apenas uma imagem como referência**  
Os mecanismos tradicionais de busca baseados em texto não atendem bem a esse cenário, resultando em **frustração, perda de tempo e redução de conversões de venda**

**Stakeholders Principais:**  
Clientes, Equipes de Vendas, Gestores de E-commerce e a própria Empresa

**Motivação do Projeto:**  
Criar uma solução inovadora e inclusiva que simplifique a experiência de compra, **aumente a satisfação do cliente** e **impulsione a eficiência comercial** por meio da inteligência artificial e da automação na nuvem

---

## 2. Escopo do MVP (Produto Mínimo Viável)

O MVP será uma **aplicação web intuitiva**, onde o usuário poderá:

- Fazer **upload de uma imagem** de um produto  
- Ter a imagem **analisada por um modelo de IA** que identifica características visuais  
- Receber **sugestões de produtos semelhantes** disponíveis no catálogo
- Visualizar **detalhes completos** de cada item sugerido

A proposta combina **simplicidade de uso** com **tecnologia de ponta**, visando uma experiência fluida e acessível a todos os públicos

---

## 3. Arquitetura Proposta — AWS Serverless

A solução será construída sobre uma **arquitetura 100% serverless** na AWS, garantindo **escalabilidade automática**, **baixo custo operacional** e **alta disponibilidade**

### Principais Serviços AWS

| Componente | Serviço | Função |
|-------------|----------|--------|
| Reconhecimento de Imagem | **Amazon Rekognition** | Identifica objetos e atributos em imagens enviadas |
| Backend Serverless | **AWS Lambda** | Executa a lógica da aplicação sob demanda, sem servidor dedicado |
| Banco de Dados NoSQL | **Amazon DynamoDB** | Armazena metadados, resultados de análise e informações de produtos |

### Diagrama de Arquitetura