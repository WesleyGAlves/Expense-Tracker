# Expense Tracker

O **Expense Tracker** é uma aplicação web interativa projetada para gerenciar transações financeiras de forma prática e eficiente. Ele permite aos usuários adicionar, visualizar e excluir transações, acompanhando em tempo real o saldo total, receitas e despesas. É uma ferramenta simples, ideal para quem busca um controle básico de suas finanças.

## Funcionalidades

- **Registro de Transações**:
  - Adição de transações financeiras, incluindo descrição, valor e categoria.
  - Atualização dinâmica das informações no painel principal após cada transação.

- **Visualização de Dados**:
  - Exibição clara do saldo total, das receitas acumuladas e das despesas totais.
  - Interface simples para listar todas as transações realizadas.

- **Gerenciamento de Transações**:
  - Remoção de transações específicas diretamente da interface.
  - Reorganização automática do saldo e dos valores exibidos após exclusões.

---

## Tecnologias Utilizadas


- **ASP.NET Core MVC**:
  - Estruturação do back-end com controllers, views e models.
  - Processamento de requisições HTTP para adicionar, listar e excluir transações.
    
- **HTML5**:
  - Estruturação semântica da interface, com elementos como tabelas, listas e formulários.

- **SQL Server**:
  - Banco de dados relacional utilizado para armazenar as transações financeiras.
  
- **CSS3**:
  - Design responsivo e estilização com uso de classes.
  - Layout agradável e moderno, com uso de cores para destacar receitas e despesas.

- **JavaScript**:
  - Manipulação do DOM para exibir dinamicamente as transações.
  - Métodos para adicionar, excluir e calcular valores de forma automática.

---

## Metodologia do Projeto

### Métodos e Lógica Utilizada:

1. **Adição de Transações**:
   - Um formulário captura os dados inseridos pelo usuário (descrição e valor).
   - A função JavaScript valida os dados, atualiza o DOM com a nova transação e recalcula o saldo total.

2. **Exclusão de Transações**:
   - Cada item listado possui um botão "x" que remove a transação correspondente.
   - O JavaScript recalcula o saldo total, receitas e despesas após a exclusão.

3. **Cálculo do Saldo Atual**:
   - O saldo é calculado como a diferença entre o total de receitas e despesas.
   - Atualizações automáticas acontecem a cada interação do usuário.

4. **Atualização Dinâmica**:
   - A manipulação do DOM garante que os dados no painel principal sejam sempre consistentes com as transações listadas.

---

## Como Executar

1. Clone o repositório para o seu computador:
   ```bash
   git clone https://github.com/WesleyGAlves/Expense-Tracker.git

### Autor

Wesley Goncalves Alves - Desenvolvedor C#/.NET

- [LinkedIn](https://www.linkedin.com/in/wesley-gon%C3%A7alves-alves-3b95472ab/)
- [GitHub](https://github.com/WesleyGAlves)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# ENGLISH

# Expense Tracker

The **Expense Tracker** is an interactive web application designed to manage financial transactions practically and efficiently. It allows users to add, view, and delete transactions while tracking the total balance, income, and expenses in real-time. It is a simple tool, ideal for those seeking basic financial control.

## Features

- **Transaction Logging**:
  - Add financial transactions, including description, value, and category.
  - Dynamically updates the main dashboard after each transaction.

- **Data Visualization**:
  - Clear display of the total balance, accumulated income, and total expenses.
  - Simple interface to list all recorded transactions.

- **Transaction Management**:
  - Remove specific transactions directly from the interface.
  - Automatically reorganizes the balance and displayed values after deletions.

---

## Technologies Used

- **ASP.NET Core MVC**:
  - Back-end structure with controllers, views, and models.
  - Handles HTTP requests to add, list, and delete transactions.

- **HTML5**:
  - Semantic structuring of the interface using elements like tables, lists, and forms.

- **SQL Server**:
  - Relational database used to store financial transactions.

- **CSS3**:
  - Responsive design and styling with class usage.
  - Modern and pleasant layout with colors to highlight income and expenses.

- **JavaScript**:
  - DOM manipulation to dynamically display transactions.
  - Methods to add, delete, and automatically calculate values.

---

## Project Methodology

### Methods and Logic Used:

1. **Adding Transactions**:
   - A form captures user-entered data (description and value).
   - JavaScript functions validate the data, update the DOM with the new transaction, and recalculate the total balance.

2. **Deleting Transactions**:
   - Each listed item includes an "x" button to remove the corresponding transaction.
   - JavaScript recalculates the total balance, income, and expenses after deletion.

3. **Calculating the Current Balance**:
   - The balance is calculated as the difference between total income and expenses.
   - Automatic updates occur with every user interaction.

4. **Dynamic Updates**:
   - DOM manipulation ensures that the data on the main dashboard remains consistent with the listed transactions.

---

## How to Run

1. Clone the repository to your computer:
   ```bash
   git clone https://github.com/WesleyGAlves/Expense-Tracker.git

### Author

Wesley Goncalves Alves - C#/.NET Developer

- [LinkedIn](https://www.linkedin.com/in/wesley-gon%C3%A7alves-alves-3b95472ab/)
- [GitHub](https://github.com/WesleyGAlves)
