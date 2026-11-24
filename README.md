
# API de Chamados de Suporte

**Estudante:** Thalyson de Sousa Batista Maia

## Objetivo do Projeto

Desenvolver a estrutura inicial de uma API de chamados de suporte utilizando Python, Flask e uv para gerenciamento do ambiente e das dependências.

Nesta primeira etapa, foi implementada uma rota inicial para verificar o funcionamento da API.

## Tecnologias Utilizadas

- Python
- Flask
- uv
- Git e GitHub

## Instalação das Dependências

Para instalar as dependências do projeto, execute:

```bash
uv sync --locked
```

## Como Executar

Execute o seguinte comando:

```bash
uv run flask --app app run --host=0.0.0.0 --port=5000
```

## Rota Inicial

**Método:** GET

**Endereço:** http://localhost:5000/

## Resposta Esperada

Código HTTP: 200

```json
{
  "mensagem": "API de chamados em funcionamento"
}
```

## Status do Projeto

Etapa 01: Estrutura inicial da API implementada.
