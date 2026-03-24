## 📌 Calculadora em Shell Script

Este projeto contém um script simples de calculadora desenvolvido em Bash, que permite realizar operações básicas diretamente pelo terminal Linux.

---

## ⚙️ Pré-requisitos

Antes de executar, certifique-se de ter:

- Sistema Linux ou terminal compatível
- Bash instalado
- Utilitário `bc` instalado (para cálculos)

Instalar o `bc` (caso não tenha):

sudo apt install bc

---

## 📂 Arquivos do projeto

- `calculadora.sh` → Script principal da calculadora  
- `comandos.txt` → Lista de comandos utilizados para execução  

---

## 🚀 Como usar

### 1. Criar ou baixar o arquivo

Caso esteja criando manualmente:

nano calculadora.sh

Cole o conteúdo do script e salve.

---

### 2. Dar permissão de execução

chmod 744 calculadora.sh

Permissões aplicadas:
- Dono: leitura, escrita e execução
- Outros: apenas leitura

---

### 3. Executar o script

./calculadora.sh

---

## 🧮 Funcionalidades

O script permite realizar:

- Adição (+)
- Subtração (-)
- Multiplicação (*)
- Divisão (/)

O usuário informa:
1. Primeiro número
2. Segundo número
3. Operação desejada

---

## 📌 Exemplo de uso

Digite o primeiro número:
10

Digite o segundo número:
5

Escolha a operação: + - * /

+

Resultado: 15

---

## 📝 Observações

- A divisão retorna até 2 casas decimais
- Caso uma operação inválida seja inserida, o script exibirá erro
- O script é executado via terminal
