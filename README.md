# Portfolio - Pedro Vinícius Meerholz

## 📋 Pré-requisitos

- Python 3.12
- pip (gerenciador de pacotes Python)
- Git

## 🚀 Instalação

### 1. Clone o repositório
```bash
git clone https://github.com/pedromeerholz/profile.git
cd profile
```

### 2. Crie um ambiente virtual (recomendado)
```bash
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate
```

### 3. Instale as dependências
```bash
pip install -r requirements.txt
```

## 🛠️ Como executar o projeto

### Desenvolvimento local
Para visualizar o site localmente durante o desenvolvimento:
```bash
mkdocs serve
```
O site estará disponível em `http://127.0.0.1:8000` e será atualizado automaticamente quando você modificar os arquivos.

### Build para produção
Para gerar os arquivos estáticos do site:
```bash
mkdocs build
```
Os arquivos serão gerados na pasta `site/`.

## 📁 Estrutura do projeto

```
portfolio/
├── docs/                 # Páginas do site (Markdown)
│   └── index.md         # Página inicial
├── site/                # Site gerado (criado pelo build)
├── mkdocs.yml           # Configuração do MkDocs
├── requirements.txt     # Dependências Python
└── README.md           # Este arquivo
```

## 📝 Adicionando conteúdo

1. Crie novos arquivos `.md` na pasta `docs/`
2. Adicione as páginas ao menu editando `mkdocs.yml` na seção `nav:`
3. Execute `mkdocs serve` para visualizar as mudanças