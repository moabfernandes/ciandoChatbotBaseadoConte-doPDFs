# meu-chatbot-pdf
Criando um Chatbot Baseado em Conteúdo de PDFs


Este projeto cria um chatbot inteligente que responde perguntas com base no conteúdo de arquivos PDF. 
Utilizando IA generativa, embeddings e buscas vetoriais.
---

## 🚀 Objetivo do Projeto

- Carregar e indexar arquivos PDF ou .txt
- Utilizar embeddings para representar semântica
- Usar busca vetorial para recuperar trechos relevantes
- Gerar respostas com IA usando modelo da OpenAI
- Criar interface interativa com Streamlit

---

## 🗂 Estrutura do Projeto

```bash
chatbot-pdf-ia/
├── inputs/              # Arquivos PDF ou texto
├── app.py               # Arquivo principal do chatbot
├── requirements.txt     # Bibliotecas necessárias
├── .env                 # Chave da OpenAI
├── README.md            # Este arquivo
```

### 📸 Captura de Tela - Criação da Estrutura



---

## 🧪 Etapa 1: Ambiente Virtual e Instalação

### 1.1 Criar ambiente virtual e ativar:

```bash
python -m venv venv
source venv/bin/activate  # (Windows: venv\Scripts\activate)
pip install --upgrade pip
```

### 1.2 Criar o arquivo `requirements.txt` com:

```txt
langchain
openai
faiss-cpu
tiktoken
pdfplumber
python-dotenv
streamlit
```

### 1.3 Instalar as dependências:

```bash
pip install -r requirements.txt
```

### 📸 Captura de Tela - Instalação de Dependências



---

## 🔐 Etapa 2: Configuração da API da OpenAI

1. Crie um arquivo `.env` com o seguinte conteúdo:

```env
OPENAI_API_KEY=sua-chave-aqui
```

2. No `app.py`, adicione no topo:

```python
from dotenv import load_dotenv
import os

load_dotenv()
openai_api_key = os.getenv("OPENAI_API_KEY")
```

### 📸 Captura de Tela - Arquivo .env e código



---

## 🔄 Etapas Futuras

-

---

## 🚀 Como Rodar o Projeto

```bash
streamlit run app.py
```

---

## 📊 Insights e Aprendizados

- IA generativa pode ser aplicada a conteúdo próprio, não só web
- Embeddings são poderosos para busca semântica
- Organização em chunks melhora respostas

---

## 📚 Inspiração

Projeto proposto pela [DIO - Digital Innovation One](https://www.dio.me) no desafio de IA aplicada para estudantes de Engenharia de Software.

ok, preciso baixar o arquivo completo com o passo a passo e imagem de cada passo

