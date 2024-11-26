# Sistema de Autenticação e Gerenciamento de Usuários com Streamlit

Este projeto implementa um sistema de autenticação de usuários, registro e gerenciamento de dados utilizando **Streamlit** e um banco de dados PostgreSQL.

## Descrição dos Arquivos

### `main.py`
Este arquivo é responsável por:

- **Autenticação de usuários**:
  - Login e logout utilizando a biblioteca `streamlit_authenticator`.
  - Gerenciamento de sessões para manter estados entre páginas.

- **Registro de novos usuários**:
  - Interface para inserir nome, nome de usuário e senha.
  - Validação de senhas e verificação de duplicidade de usuários.

- **Dashboard**:
  - Área reservada que é exibida após um login bem-sucedido.

### `dependencies.py`
Contém as funções para interagir com o banco de dados PostgreSQL, utilizando `psycopg2` e variáveis de ambiente carregadas com `dotenv`.

## Configuração

### Dependências
Certifique-se de instalar os seguintes pacotes:
```bash
pip install streamlit, psycopg2, python-dotenv, streamlit-authenticator

