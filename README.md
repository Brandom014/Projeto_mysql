# CRUD com Mysql + Python + Streamlit

Este projeto é um exemplo prático de CRUD usando:
 - Banco de dados **MYSQL**
 - Conexão com o **mysql.connector**
 - Interface web com **Streamlit**

 ## Como executar

 ### 1. Clonar o repositório

 ```bash
 git clone https://github.com/Brandom014/Projeto_mysql.git
 ```

 ### 2. Instalar dependências
 ```bash
 pip install -r requirements.txt
 ```

 ### 3. Configurar as variáveis de ambiente
 crie um arquivo .env na raiz do seu projeto com:
 ```bash
 DB_PASSWORD=sua_senha
 DB_HOST=localhost
 DB_USER=seu_usuario
 DB_NAME=seu_DB
 ```

 ### 4. Rodar aplicação
 ```bash
 python -m streamlit run app.py 
 ```

 ### 5. Funcionalidades

  - Inserir registros no db

  - Listar registros no db

  - Atualizar registros no db

  - Deletar registros no db

  - Interface simples com Streamlit