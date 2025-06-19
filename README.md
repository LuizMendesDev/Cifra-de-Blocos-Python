# Cifra-de-Blocos-Python
# 🔐 Projeto de Extensão: Algoritmo de Cifra de Blocos em Python

Este projeto apresenta o desenvolvimento de um **algoritmo de cifra de blocos simétrica**, criado como parte da disciplina **Projeto de Extensão VII** da **Universidade Veiga de Almeida**, sob orientação do professor **Fábio Contarini Carneiro**.

---

## 📌 Descrição do Projeto

O objetivo foi implementar um **algoritmo de criptografia de blocos de 32 bits**, utilizando **Python puro** (sem bibliotecas externas), com foco em proteger dados sensíveis, como arquivos de texto ou binários.

O sistema permite tanto **criptografar** quanto **decriptografar** arquivos, utilizando uma **chave de 32 bits**, com **3 rodadas de substituição e permutação**, garantindo **simetria** e um bom **efeito avalanche**.

---

## ⚙️ Funcionalidades

- Criptografia e decriptografia de arquivos
- Geração de subchaves por rotação da chave principal
- Operações de substituição (XOR) e permutação de metades
- Compatível com qualquer tipo de arquivo binário ou texto
- Testes demonstrando o efeito avalanche

---

## 🗂️ Arquivos do Repositório

| Arquivo | Descrição |
|---|---|
| `cifra_de_blocos.py` | Código-fonte principal do algoritmo |
| `teste_avalanche.py` | Script para teste do efeito avalanche |
| `mensagem.txt` | Exemplo de arquivo de texto original |
| `mensagem_crypt.bin` | Arquivo criptografado gerado pelo algoritmo |
| `mensagem_decrypt.txt` | Arquivo decriptografado (texto recuperado) |
| `Documentação_criptografia_projeto_de_extensão.pdf` | Documentação completa do projeto (em formato acadêmico) |

---

## 🖥️ Como Executar o Projeto

### Requisitos:
- Python 3.x

### Execução do programa:

**1. Executar o Menu de Criptografia/Decriptografia:**
```bash
python cifra_de_blocos.py
