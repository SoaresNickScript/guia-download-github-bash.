# Guia Completo: Automatize seus Downloads do GitHub com Bash

Este tutorial ensina como usar um script Bash para automatizar downloads de arquivos e repositórios do GitHub, economizando tempo e esforço.

## Introdução

Baixar arquivos e repositórios do GitHub manualmente é trabalhoso. Este tutorial apresenta um script Bash que simplifica este processo, permitindo downloads rápidos e eficientes.

## Pré-requisitos

* **Sistema Operacional:** Linux (testado em Ubuntu, Debian, Kali)
* **Bash:** Shell Bash (geralmente instalado por padrão)
* **wget:** Instale com `sudo apt install wget` (ou o comando equivalente para sua distribuição).
* **gh CLI (Opcional):** Para clonar repositórios. Instale com `gh auth login` (veja a documentação da `gh` para instruções).

## Instalação

1. **Clone este repositório:**
   ```bash
   git clone https://github.com/[seu_nome_de_usuario]/meu-script-github.git
