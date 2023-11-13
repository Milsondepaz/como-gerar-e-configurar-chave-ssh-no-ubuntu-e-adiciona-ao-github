# Como Gerar e Configurar Chave SSH no Ubuntu e Adicionar ao GitHub

Aprenda a proteger suas conexões com o GitHub e a simplificar seu fluxo de trabalho com este tutorial sobre a criação e configuração de chaves SSH no Ubuntu. 

Neste tutorial, vou guiar você passo a passo na criação e configuração de uma chave SSH no Ubuntu, essencial para garantir a segurança e autenticação ao utilizar o GitHub. Uma chave SSH é uma ferramenta fundamental para desenvolvedores que desejam colaborar em projetos e repositórios de código de forma segura, isso lhe permitirá a interagir com os seus repositório remoto no GitHub (Clonar, fazer Push ou Pull) sem ter que inserir nome de Usuário ou Palavra-Passe. 

## 1- Vizualizar chaves SSH já configuras
## 2- Gerar um par de chaves SSH
## 2- Adicionar a chave pública ao seu perfil do GitHub.

1. Passos de Instalação

    ```bash
    ssh-add -l
    ```

2. Gerar um par de chaves SSH:

    ```bash
    ssh-keygen -t rsa -b 4096 -C "seu-email@exemplo.com"
    ```

Boa sorte na sua jornada como Developer!!!
