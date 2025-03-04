<p align="center">
<img src="./assets/ciberseguranca-logo.png" alt="Phishing para captura de senhas do Facebook" width="150" /> <br /> <b>Phishing para captura de senhas do Facebook</b> <br /> <sub><sup><b>(PHISHING-FACEBOOK)</b></sup></sub> <br /> </p> <p align="center"> Este projeto cria uma página de login falsa do Facebook para capturar senhas, utilizando VirtualBox, Kali Linux e setoolkit. <br /> </p>

## Estrutura do Projeto

### Páginas Principais

- README.md: Documentação do projeto.

### Estrutura de Pastas

phishing-facebook
├── prints
│ ├── print-1.png
│ ├── print-2.png
│ ├── print-3.png
│ └── resultado.png
└── README.md

### Funcionalidades

- Captura de Credenciais: Criação de uma página de login falsa do Facebook para capturar senhas.
- Clonagem de Sites: Utiliza o setoolkit para clonar a página de login do Facebook.
- Relatórios Visuais: Imagens que mostram o processo e os resultados da captura de credenciais.

### Tecnologias e Ferramentas Utilizadas

- Kali Linux: Sistema operacional utilizado para testes de penetração.
- setoolkit: Ferramenta utilizada para criar o ataque de phishing.
- VirtualBox: Software de virtualização para rodar o Kali Linux.

### Como Funciona o Phishing

1. **Acesso root**: Utilize o comando `sudo su` para obter acesso root.
2. **Iniciando o setoolkit**: Execute `setoolkit` no terminal.
3. **Tipo de ataque**: Selecione `Social-Engineering Attacks`.
4. **Vetor de ataque**: Escolha `Web Site Attack Vectors`.
5. **Método de ataque**: Selecione `Credential Harvester Attack Method`.
6. **Método de ataque**: Escolha `Site Cloner`.
7. **Obtendo o endereço da máquina**: Utilize o comando `ifconfig` para obter o endereço IP.
8. **URL para clone**: Insira `http://www.facebook.com` como a URL a ser clonada.

### Resultados

<img src="./prints/print-1.png">
<img src="./prints/print-2.png">
<img src="./prints/print-3.png">
<img src="./prints/resultado.png">

### Licença

Este software é licenciado sob os termos da MIT License.

⌨️ Desenvolvido por [Seu Nome](https://github.com/seuusuario)