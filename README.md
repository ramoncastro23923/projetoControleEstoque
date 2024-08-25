# Projeto de Controle de Estoque

## Descrição

Este projeto é uma solução de controle de estoque que visa otimizar a gestão de inventário por meio de uma arquitetura moderna e práticas de desenvolvimento eficientes. O sistema integra diversas tecnologias e estratégias para garantir um desempenho robusto e uma experiência de usuário fluida.

## Tecnologias Utilizadas

- **Node.js**: Para o backend e consumo eficiente de APIs.
- **Angular**: Framework para a construção do frontend.
- **PrimeNG e PrimeFlex**: Bibliotecas para componentes e estilização.
- **PrimeChart/ChartJs**: Para a criação de gráficos e visualizações de dados.
- **Prisma**: Ferramenta ORM para a persistência de dados.
- **Formulários Reativos**: Para gerenciar formulários de forma eficiente.
- **Estratégias de Memória**: Implementação de medidas para evitar problemas de Memory Leak.

## Arquitetura

- **Backend**: Implementado com Node.js, rodando na porta `3333`.
- **Frontend**: Aplicativo Angular, executado na porta `4200`.
- **Persistência de Dados**: Utiliza o ORM Prisma para armazenamento em banco de dados.

## Funcionalidades

- **Controle de Estoque**: Gerencia e controla o inventário de produtos.
- **Arquitetura Modularizada**: Estrutura organizada para fácil manutenção e escalabilidade.
- **Componentes e Gráficos**: Utiliza PrimeNG e PrimeChart/ChartJs para uma interface rica e interativa.
- **Formulários Reativos**: Gerencia formulários com validação e controle de estado.

## Configuração

1. **Instale as Dependências**:
   - No diretório do projeto, execute `npm install` para instalar todas as dependências do backend e do frontend.

2. **Configure o Banco de Dados**:
   - Certifique-se de que o banco de dados esteja configurado e acessível.
   - Configure o Prisma conforme necessário para o seu ambiente.

3. **Inicie o Servidor Backend**:
   - No diretório do backend, execute `npm start` para iniciar o servidor na porta `3333`.

4. **Inicie o Aplicativo Angular**:
   - No diretório do frontend, execute `ng serve` para iniciar o aplicativo Angular na porta `4200`.

## Acesso

- **API Backend**: Acessível em `http://localhost:3333`
- **Aplicativo Frontend**: Acessível em `http://localhost:4200`
