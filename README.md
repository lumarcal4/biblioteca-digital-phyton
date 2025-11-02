# biblioteca-digital-phyton
Sistema de gerenciamento de documentos digitais para biblioteca universitária
# Sistema de Gerenciamento de Biblioteca Digital

Este projeto foi desenvolvido como parte da disciplina de Programação para Ciência de Dados da PUCPR. O objetivo é criar um sistema em Python que facilite a gestão de documentos digitais em uma biblioteca universitária.

## Funcionalidades

- Listar documentos por tipo de arquivo (PDF, ePUB, etc.)
- Listar documentos por ano de publicação
- Adicionar, renomear e remover documentos
- Interface de linha de comando para uso dos bibliotecários

## Requisitos

- Python 3.10+
- Sistema de arquivos com estrutura organizada por tipo e ano

## Como usar

```bash
python main.py --listar-tipo
python main.py --listar-ano
python main.py --adicionar origem.pdf destino.pdf
python main.py --renomear antigo.pdf novo.pdf
python main.py --remover caminho.pdf
