

---

# **NeoStock - Sistema CRM para Gestão de Estoque**

## Descrição

O **NeoStock** é um sistema CRM (Customer Relationship Management) desenvolvido para empresas que necessitam de uma solução prática e eficiente para gerenciar seu estoque de produtos. Com funcionalidades como o controle de validade, quantidade, código de barras e localização de produtos, o NeoStock oferece uma plataforma intuitiva para facilitar o gerenciamento do estoque e melhorar a organização da empresa.

## Funcionalidades

- **Cadastro de Produtos:**  
  O sistema permite o cadastro completo de produtos, com informações como nome, preço, quantidade, código de barras, validade, localização e imagem.

- **Controle de Estoque:**  
  Monitore o nível de estoque dos produtos, identifique itens com baixa quantidade e faça o gerenciamento eficiente das reposições.

- **Validade de Produtos:**  
  Controle a validade dos produtos no estoque e receba alertas para evitar perdas de itens perecíveis.

- **Código de Barras e Localização:**  
  Atribua códigos de barras e organize os produtos por localização no estoque, facilitando a consulta e movimentação dos itens.

- **Imagens de Produtos:**  
  Associe imagens aos produtos para melhorar a identificação visual e a organização do estoque.

## Tecnologias Utilizadas

- **Frontend:**  
  - React.js ou Angular para criar uma interface de usuário moderna e responsiva.
  - Bootstrap ou Tailwind CSS para o design e layout responsivo.

- **Backend:**  
  - Java com Spring Boot para desenvolvimento da API RESTful.
  - PostgreSQL ou MySQL para gerenciamento do banco de dados.

- **Segurança:**  
  - Autenticação com JWT para garantir a segurança das informações.

- **Leitura de Código de Barras:**  
  - Integração com sistemas de leitura de código de barras para facilitar a inserção e atualização dos produtos no estoque.

- **Notificações de Validade:**  
  - Alertas por e-mail ou notificação dentro do sistema para avisar sobre a validade dos produtos.

## Como Rodar o Projeto

### Requisitos

Antes de executar o projeto, certifique-se de ter os seguintes softwares instalados:

- JDK 11 ou superior.
- Node.js (para o frontend).
- Banco de Dados: PostgreSQL ou MySQL.

### Backend

1. Clone o repositório do backend:
   ```bash
   git clone https://github.com/seu-usuario/neo-stock-backend.git
   ```

2. Navegue até o diretório do backend:
   ```bash
   cd neo-stock-backend
   ```

3. Compile e execute o backend com Maven:
   ```bash
   mvn spring-boot:run
   ```

4. O backend estará rodando na porta 8080 por padrão.

### Frontend

1. Clone o repositório do frontend:
   ```bash
   git clone https://github.com/seu-usuario/neo-stock-frontend.git
   ```

2. Navegue até o diretório do frontend:
   ```bash
   cd neo-stock-frontend
   ```

3. Instale as dependências:
   ```bash
   npm install
   ```

4. Execute o frontend:
   ```bash
   npm start
   ```

5. O frontend estará acessível em `http://localhost:3000`.

## Estrutura do Projeto

### Backend

O backend é desenvolvido com **Java e Spring Boot**. Ele gerencia a comunicação com o banco de dados e fornece uma API RESTful para o frontend consumir.

### Frontend

O frontend foi desenvolvido com **React.js** (ou Angular, dependendo da escolha), utilizando **Bootstrap** ou **Tailwind CSS** para um design moderno e responsivo.

## Como Contribuir

1. Faça um fork do projeto.
2. Crie uma nova branch para suas alterações:
   ```bash
   git checkout -b minha-nova-funcionalidade
   ```
3. Faça as mudanças necessárias e faça commit:
   ```bash
   git commit -m "Adicionando nova funcionalidade"
   ```
4. Envie as alterações para o seu repositório:
   ```bash
   git push origin minha-nova-funcionalidade
   ```
5. Abra um pull request com suas alterações.

## Licença

Distribuído sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---
