# DoaBot
Repositório com arquivo .json para testar o DoaBot feito na plataforma LangFlow

Este repositório contém o DoaBot, um componente personalizado para o LangFlow. Ele foi desenvolvido como parte de um projeto de pesquisa por estudantes do IFMS Campus Nova Andradina, com o objetivo de criar um chatbot para conscientizar sobre a importância da doação de sangue.

## 📋 Descrição
O DoaBot é um assistente virtual projetado para:
- Informar sobre o processo de doação de sangue;
- Desmentir mitos e aliviar medos relacionados à doação;
- Incentivar a doação como um ato solidário que salva vidas;
- O componente utiliza prompts dinâmicos para adaptar as mensagens de acordo com as necessidades do usuário.

## 🛠️ Como Usar
Requisitos:
1. Ambiente Python configurado;
2. LangFlow instalado.

### Instale o Langflow com pip ou pipx

Instale o Langflow com uv:
```
uv pip install langflow
```

Instale o Langflow com pip:
```
python -m pip install langflow
```

Instale o Langflow com pipx usando o executável Python 3.10:
```
pipx install langflow --python python3.10
```

### Executar Langflow

Para executar o Langflow com uv, insira o comando a seguir.
```
uv run langflow run
```
Para executar o Langflow com pip, insira o comando a seguir.
```
python -m langflow run
```
Confirme se uma instância local do Langflow inicia visitando um navegador baseado em Chromium.

### Agora que o Langflow está em execução:
1. Abra o LangFlow.
2. Importe o arquivo .json do repositório.
3. Conecte o DoaBot no seu fluxo no LangFlow e interaja com ele.
