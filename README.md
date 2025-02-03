# Flask API - Jano

Este repositório contém um projeto Flask que interage com o robô NAO, permitindo o envio de perguntas e o recebimento de respostas via IA.

## Tecnologias Utilizadas
- Python 3
- Flask
- Axios (para chamadas HTTP no front-end)
- Reconhecimento de fala (Web Speech API)

## Como Executar

### 1. Clonar o Repositório
```sh
git clone https://github.com/seu-usuario/jano-nao-api.git
cd jano-nao-api
```

### 2. Criar um Ambiente Virtual (A API está em modo de desenvolvimento)
```sh
python -m venv pynaoqi
source pynaoqi/bin/activate  # Para Linux/Mac
pynaoqi\Scripts\activate  # Para Windows
```

### 3. Instalar Dependências
```sh
pip install -r requirements.txt
```

### 4. Executar o Servidor Flask
```sh
python server.py
```
O servidor será iniciado em `http://127.0.0.1:5000/`.

## Endpoints Principais
- `POST /nao/ip` - Configura o IP do Jano
- `POST /nao/ask` - Envia a resposta para o Jano falar
- `POST /nao/shutdown` - Encerra a conexão do Jano

---

Feito com muito 💜🖤 pela Prometeus Tech Innovation! 😃