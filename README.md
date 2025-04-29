# 📊 Projeto Temático 1 – Sistema de Gerenciamento de Dados com Python

Este repositório contém o código-fonte de um sistema de gerenciamento de dados desenvolvido em Python, utilizando banco de dados MySQL. O projeto foi elaborado como parte das atividades acadêmicas do curso de Ciência da Computação da Universidade de Caxias do Sul (UCS).

## 🚀 Funcionalidades

- Conexão com banco de dados MySQL
- Operações de CRUD (Create, Read, Update, Delete)
- Interface de linha de comando para interação com o usuário
- Estrutura modularizada para facilitar a manutenção e expansão

## 🛠️ Tecnologias Utilizadas

- **Linguagem de Programação**: Python
- **Banco de Dados**: MySQL
- **Bibliotecas**:
  - `mysql-connector-python`: para conexão e manipulação do banco de dados

## 📁 Estrutura do Projeto

```
projeto_tematico_1/
├── main.py
├── database/
│   ├── connection.py
│   └── setup.sql
├── models/
│   └── entity.py
├── controllers/
│   └── operations.py
├── utils/
│   └── helpers.py
└── README.md
```

- `main.py`: ponto de entrada do aplicativo
- `database/`: scripts relacionados à configuração e conexão com o banco de dados
- `models/`: definição das entidades utilizadas no sistema
- `controllers/`: lógica de negócios e operações
- `utils/`: funções auxiliares

## ⚙️ Configuração do Banco de Dados

Certifique-se de que o MySQL esteja instalado e em execução em sua máquina. As configurações padrão esperadas são:

- **Host**: `localhost`
- **Usuário**: `root`
- **Senha**: (vazia)

Caso seja necessário remover a senha do usuário `root`, execute o seguinte comando no prompt do MySQL:

```sql
SET PASSWORD FOR 'root'@'localhost' = '';
```

## ▶️ Executando o Projeto

1. Clone o repositório:

   ```bash
   git clone https://github.com/Eduardo-Bauer/projeto_tematico_1.git
   ```

2. Navegue até o diretório do projeto:

   ```bash
   cd projeto_tematico_1
   ```

3. Instale as dependências:

   ```bash
   pip install mysql-connector-python
   ```

4. Execute o aplicativo:

   ```bash
   python main.py
   ```

## 📌 Observações

- Este projeto foi desenvolvido com fins educacionais, visando a aplicação prática dos conceitos aprendidos em sala de aula.
- Contribuições e sugestões são bem-vindas para aprimorar o sistema.
