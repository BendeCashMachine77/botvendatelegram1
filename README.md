# Perfume Store

Este é um projeto de uma loja de perfumes com uma aplicação Flask e integração com banco de dados SQLAlchemy. O projeto inclui uma estrutura modular para facilitar a manutenção e expansão.

## Estrutura do Projeto

- **`app/`**: Código da aplicação principal.
  - **`__init__.py`**: Configuração e inicialização da aplicação Flask.
  - **`config.py`**: Configurações da aplicação (banco de dados, chave secreta, etc.).
  - **`models/`**: Modelos de banco de dados (ex: Perfume, Usuário, Pedido).
  - **`routes/`**: Rotas da aplicação (ex: listar perfumes, finalizar compras).
    - **`main_routes.py`**: Rotas principais da aplicação.
  - **`services/`**: Lógica de negócio (ex: gerenciamento de estoque, processamento de pedidos).
  - **`utils/`**: Funções utilitárias (ex: validação de dados, formatação).
- **`instance/`**: Dados de instância (ex: banco de dados local).
- **`tests/`**: Testes automatizados para a aplicação.
- **`venv/`**: Ambiente virtual Python para isolar as dependências do projeto.
- **`requirements.txt`**: Lista de dependências do projeto.
- **`run.py`**: Script principal para executar a aplicação.
- **`README.md`**: Documentação do projeto.

## Como Executar

### Pré-requisitos

- Python 3.8 ou superior.
- Git (opcional, para clonar o repositório).

### Passos para Configuração

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/BendeCashMachine77/Perfume-Store.git
   cd Perfume-Store