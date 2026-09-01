🛒 Central de Compras
Plataforma acadêmica para gerenciamento de lojistas e fornecedores, permitindo automatizar pedidos, campanhas promocionais e condições comerciais regionais.

Este projeto é parte do trabalho da disciplina de Gerenciamento de Dados e Desenvolvimento de Aplicações.

📌 Objetivo
Desenvolver um MVP (Produto Mínimo Viável) que possibilite:

Cadastramento e gerenciamento de lojas, fornecedores e produtos.
Geração automática de credenciais para cada entidade cadastrada.
Comunicação eficiente entre lojas e fornecedores através de pedidos e campanhas.
Definição de condições comerciais específicas por estado (cashback, prazo de pagamento, acréscimos/descontos).
🚀 Funcionalidades
🔑 Administrador
Cadastrar lojas, fornecedores e produtos.
Gerar automaticamente usuários e senhas.
Gerenciar credenciais de televendas (opcional).
🏬 Lojas
Login com credenciais.
Visualização de fornecedores por categoria.
Realização e consulta de pedidos.
Edição de dados cadastrais.
🏭 Fornecedores
Login com credenciais.
Visualização e atualização de pedidos recebidos.
Cadastro e edição de produtos.
Criação de campanhas promocionais:
Por valor (ex: acima de R$100 → cashback).
Por quantidade (ex: acima de 10 unidades → brinde).
Definição de condições de pagamento.
Condições comerciais por estado:
Cashback personalizado.
Prazo de pagamento diferenciado.
Acréscimos/descontos por unidade.
🛠️ Tecnologias Utilizadas
Frontend:

React 18

Vite (build tool)

React Query (TanStack Query v5) - gerenciamento de estado e cache

React Router - navegação

Tailwind CSS - estilização

shadcn/ui - componentes UI

Lucide React - ícones

Sonner - notificações toast

Backend:

Node.js

Express - framework web

PostgreSQL - banco de dados

pg (node-postgres) - driver PostgreSQL

Resend - serviço de email

dotenv - variáveis de ambiente

Arquiterura:

API RESTful

Autenticação com sessões

Upload de arquivos (Multer)

Sistema multi-tenant (Admin, Lojas, Fornecedores)
