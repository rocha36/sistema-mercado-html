# Mercadinho Ideal - Projeto Fudamentos do Sistemas Web

## Visão Geral

Este projeto foi desenvolvido como parte da atividade da faculdade de Análise e Desenvolvimento de Sistemas da PUCRS, com foco no desenvolvimento dos fundamentos do sistema web. O objetivo foi criar a estrutura básica de um sistema web para um minimercado, sem customizações visuais utilizando CSS ou JavaScript. O foco foi exclusivamente na organização do conteúdo em HTML, garantindo uma estrutura funcional e bem definida para futuras implementações.

O projeto recebeu o nome fictício de **Mercadinho Ideal**, e uma identidade visual inicial foi criada, incluindo um logotipo representativo para reforçar a marca. Para auxiliar na organização e definição da estilização do mercado, foi criado um protótipo no Figma. Esse protótipo serviu como base para planejar a tipografia, a paleta de cores e a disposição dos elementos e conteúdo na interface. Isso facilita tanto a primeira fase de marcação de texto em HTML, quanto para próxima fase de estilização, onde será aplicada a personalização visual utilizando CSS.

## Objetivo do Sistema

O principal objetivo do **Mercadinho Ideal** é oferecer praticidade e comodidade aos clientes, permitindo:

- **Acesso rápido às ofertas semanais.**
- **Criação e personalização de listas de compras.**
- **Integração com o WhatsApp para facilitar pedidos.**
- **Sugestões de receitas com possibilidade de adicionar ingredientes diretamente à lista de compras.**
- **Informações institucionais sobre o mercadinho e formas de contato.**

## Arquitetura do Sistema

Nesta fase inicial, o sistema é estático, baseado apenas em HTML. A estrutura da página está organizada da seguinte maneira:

### Estrutura HTML

O código HTML é organizado em três seções principais:

- **Cabeçalho (Header):** Contém a logo do mercadinho, slogan e menu de navegação.
- **Corpo Principal (Main):** Exibe as ofertas da semana, busca de produtos e sugestões de receitas.
- **Rodapé (Footer):** Contém informações de contato, formas de pagamento e redes sociais.

A estrutura das páginas foi construída utilizando as seguintes tags principais:

- `<header>`: Contém a navegação principal.
- `<nav>`: Inclui os links de navegação entre as páginas.
- `<main>`: Área principal de conteúdo da página.
- `<select>` + `<option>`: Para criar um menu suspenso onde o usuário pode selecionar uma opção.
- `<section>`: Divisão das informações dentro das páginas.
- `<article>`: Utilizado para exibir receitas e detalhes de produtos.
- `<footer>`: Contém informações de contato, redes sociais e formas de pagamento.
- `<form>`: Usado nas páginas de cadastro e login.
- `<input>`: Para entrada de dados do usuário.
- `<button>`: Para ações como confirmar, criar conta, entrar etc.
- `<img>`: Exibição de imagens e ícones.
- `<a>`: Links para outras páginas e encarte em PDF.

### Navegação do Sistema

As páginas principais do sistema são:

- **Home:** Página principal com ofertas e receitas.
- **Lista de Compras:** Ferramenta para criação de listas.
- **Encarte:** Exibição do encarte da semana.
- **Ofertas:** Página específica para promoções.
- **Quem Somos:** Informações institucionais.
- **Cadastro/Login:** Registro de clientes para o sistema de fidelidade.
- **Receitas:** Sugestões de pratos e ingredientes.

## Requisitos Funcionais

- O sistema deve permitir a navegação entre as páginas principais.
- O usuário deve conseguir visualizar ofertas e receitas.
- O cliente deve conseguir criar e personalizar lista de compras.
- Uma seção na página inicial mostrando os pontos e conversão dos pontos em saldo para usar como desconto nas próximas compras.
- As listas de compras devem permitir impressão ou envio via WhatsApp.
- A página de receitas deve permitir adicionar ingredientes à lista de compras.

## Descrição das Funcionalidades

### Cabeçalho (Header)

- **Exibição da logo do mercadinho.**
- **Slogan:** "É PREÇO BOM, É PRATICIDADE, É MERCADINHO IDEAL!"
- **Um painel de benefícios na página inicial que possibilita que o cliente visualize de forma imediata os pontos acumulados e a conversão dos pontos em reais.**
- **Menu de navegação com links para todas as páginas.**

### Corpo Principal (Main)

- **Seção de Ofertas da Semana:**
  - Exibição dinâmica dos produtos em promoção.
  - Informações de preços e disponibilidade.
  - Os pontos e conversão dos pontos em saldo.
- **Busca de Produtos:**
  - Campo de busca para facilitar a localização de produtos.
- **Sugestões de Receitas:**
  - Listagem de receitas com tempo de preparo e categoria (almoço, jantar, etc.).
  - Exibição de ingredientes com opção de adicionar à lista de compras.

### Rodapé (Footer)

- **Cadastro de Clientes:**
  - Formulário para cadastro via CPF.
  - Integração com a página de registro.
- **Informações de Contato:**
  - Endereço, telefone e e-mail.
- **Formas de Pagamento:**
  - Visa, Mastercard, Pix.
- **Redes Sociais:**
  - Links para Instagram, Facebook e WhatsApp.

## Fluxo de Navegação

1. O cliente acessa a página **Home** e visualiza as ofertas da semana.
2. Pode buscar um produto específico na barra de pesquisa.
3. Pode acessar a página de **Lista de Compras** para criar uma lista personalizada.
4. Na página de **Receitas**, pode selecionar uma receita e ver os ingredientes e modo de preparo.
5. A lista pode ser impressa ou enviada para o WhatsApp para solicitar entrega.
6. O cliente pode acessar a página de **Cadastro/Login** para se registrar e acumular pontos.

## Próximos Passos

- **Estilização com CSS:** A próxima fase do projeto incluirá a aplicação de estilos visuais utilizando CSS, seguindo o protótipo criado no Figma.
- **Implementação de JavaScript:** Adicionar interatividade e funcionalidades dinâmicas ao sistema.
- **Desenvolvimento Mobile:** Adaptar o sistema para dispositivos móveis, garantindo uma experiência de usuário responsiva e acessível.

## Contribuições

Este projeto foi desenvolvido como parte de uma atividade acadêmica, mas contribuições e sugestões são bem-vindas.
