# Calculadora Interativa em C

Uma aplicação de terminal (CLI) simples e eficiente desenvolvida na linguagem de programação **C**. O programa oferece um menu interativo para realizar as quatro operações aritméticas fundamentais.

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Language: C](https://img.shields.io/badge/Language-C99-blue.svg)
![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen.svg)

---

## 1. Título e Descrição

### Sobre o Projeto
A **Calculadora Interativa em C** é uma ferramenta de linha de comando projetada para executar cálculos matemáticos básicos de forma direta e intuitiva.

### Principais Funcionalidades
- **Operações aritméticas básicas:** soma (`+`), subtração (`-`), multiplicação (`*`) e divisão (`/`).
- **Menu interativo:** permite realizar múltiplas operações em sequência.
- **Entrada de dados:** solicita dois números para cada operação.
- **Validação de divisão por zero:** identifica e bloqueia tentativas de divisão por zero.
- **Opção de encerramento:** sai do programa por meio da opção `5` no menu.

---

## 2. Demonstração

Exemplo do fluxo textual de interação no terminal:

```text
==================================================
           CALCULADORA INTERATIVA EM C
==================================================
  [1] Adição (+)
  [2] Subtração (-)
  [3] Multiplicação (*)
  [4] Divisão (/)
  [5] Sair
==================================================
Escolha uma opção: 1

Digite o primeiro número: 12.5
Digite o segundo número: 7.5

--------------------------------------------------
Resultado: 12.50 + 7.50 = 20.00
--------------------------------------------------
```

## 📸 Demonstração

![Demonstração do Terminal](assets/demo.png)

---

## 3. Instalação e Pré-requisitos

### Pré-requisitos
Para compilar e executar o código em C, é necessário ter um compilador C instalado, como o **GCC** (GNU Compiler Collection).

#### Como verificar a instalação do GCC
Abra o terminal e execute:

```bash
gcc --version
```

Se a instalação estiver correta, o comando exibirá a versão do compilador.

### Compilação
No diretório do projeto, compile o arquivo principal em C:

```bash
gcc src/main.c -o calculadora
```

Execute o comando no diretório raiz do projeto.

### Execução
No Linux/macOS:

```bash
./calculadora
```

No Windows (Prompt de Comando ou PowerShell):

```bash
calculadora.exe
```

---

## 4. Como Usar

Ao iniciar o programa, o menu abaixo será exibido:

```text
==================================================
           CALCULADORA INTERATIVA EM C
==================================================
  [1] Adição (+)
  [2] Subtração (-)
  [3] Multiplicação (*)
  [4] Divisão (/)
  [5] Sair
==================================================
Escolha uma opção:
```

### Exemplos de uso
- Digite `1` para somar dois números.
- Digite `2` para subtrair.
- Digite `3` para multiplicar.
- Digite `4` para dividir.
- Digite `5` para encerrar a aplicação.

O programa solicita os dois operandos e, em seguida, mostra o resultado da operação selecionada. A divisão por zero é bloqueada com uma mensagem de erro. A leitura dos operandos não verifica se a entrada numérica foi bem-sucedida; portanto, informe números válidos.

---

## 5. Estrutura do Projeto

```text
calculadora-c/
├── src/
│   └── main.c             # Código-fonte principal da calculadora
├── assets/                # Arquivos visuais e imagens de demonstração
│   └── demo.png
├── LICENSE                # Licença MIT do projeto
├── README.md              # Documentação do projeto
└── ...
```

---

## 6. Licença

Este projeto está licenciado sob a licença **MIT**. Consulte o arquivo [LICENSE](LICENSE) para obter mais detalhes.

A licença MIT permite o uso, cópia, modificação, fusão, publicação, distribuição e venda do software, desde que a licença e o aviso de copyright sejam mantidos.

---