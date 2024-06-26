# Como configurar/instalar/usar o `tar.gz` ou `tgz` no `Linux Ubuntu`

## Resumo

Neste documento estão contidos os principais comandos e configurações para configurar/instalar/usar o `tar.gz` ou `tgz` no `Linux Ubuntu`.

## _Abstract_

_In this document are contained the main commands and settings to set up/install the `tar.gz` ou `tgz` on `Linux Ubuntu`._


## Descrição [2]

### `tar.gz` ou `tgz`

O formato de arquivo tar.gz, ou tgz, é uma maneira comum de compactar e arquivar vários arquivos em um único pacote. O "tar" é responsável por agrupar os arquivos juntos, enquanto o "gzip" é usado para comprimi-los, resultando em um arquivo menor. Esse formato é amplamente utilizado em sistemas Unix e Linux para distribuir e armazenar coleções de arquivos, como programas, bibliotecas e conjuntos de dados. Ele oferece uma forma eficiente de organizar e transferir dados, mantendo a integridade dos arquivos originais.


## 1. Como configurar/instalar/usar o `tar.gz` ou `tgz` no `Linux Ubuntu` [1]

Para configurar/instalar/usar o `tar.gz` ou `tgz` no `Linux Ubuntu`, você pode seguir estes passos:

1. Abra o `Terminal Emulator`. Você pode fazer isso pressionando: `Ctrl + Alt + T`

2. Certifique-se de que seu sistema esteja limpo e atualizado.

    2.1 Limpar o `cache` do gerenciador de pacotes APT. Especificamente, ele remove todos os arquivos de pacotes (`.deb`) baixados pelo APT e armazenados em `/var/cache/apt/archives/`. Digite o seguinte comando: `sudo apt clean` 
    
    2.2 Remover pacotes `.deb` antigos ou duplicados do cache local. É útil para liberar espaço, pois remove apenas os pacotes que não podem mais ser baixados (ou seja, versões antigas de pacotes que foram atualizados). Digite o seguinte comando: `sudo apt autoclean`

    2.3 Remover pacotes que foram automaticamente instalados para satisfazer as dependências de outros pacotes e que não são mais necessários. Digite o seguinte comando: `sudo apt autoremove -y`

    2.4 Buscar as atualizações disponíveis para os pacotes que estão instalados em seu sistema. Digite o seguinte comando e pressione `Enter`: `sudo apt update -y`

    2.5 Para ver a lista de pacotes a serem atualizados, digite o seguinte comando e pressione `Enter`:  `sudo apt list --upgradable`

    2.6 Realmente atualizar os pacotes instalados para as suas versões mais recentes, com base na última vez que você executou `sudo apt update -y`. Digite o seguinte comando e pressione `Enter`: `sudo apt full-upgrade -y`

    2.7 Remover pacotes que foram automaticamente instalados para satisfazer as dependências de outros pacotes e que não são mais necessários. Digite o seguinte comando: `sudo apt autoremove -y`

    2.8 Remover pacotes `.deb` antigos ou duplicados do cache local. É útil para liberar espaço, pois remove apenas os pacotes que não podem mais ser baixados (ou seja, versões antigas de pacotes que foram atualizados). Digite o seguinte comando: `sudo apt autoclean`

Para instalar um arquivo `.tar.xz` ou `.tgz`, você geralmente precisará descompactar o arquivo e, dependendo do conteúdo, compilar e instalar os programas ou bibliotecas. Vou detalhar os passos para ambas as extensões, considerando que você está utilizando um sistema baseado em Linux:

### 1.1 Para um arquivo `.tar.xz`:

1. Abra um terminal.

2. **Descompacte o arquivo usando o comando `tar`:** `tar -xf arquivo.tar.xz`

3. Substitua `arquivo.tar.xz` pelo nome do seu arquivo.

4. **Navegue até o diretório descompactado:** `cd nome_do_diretorio`

    Substitua `nome_do_diretorio` pelo nome do diretório criado após a descompactação.

5. Leia qualquer arquivo de instrução como `README` ou `INSTALL` para entender o processo de instalação específico do software.

6. Geralmente, você seguirá os passos de configuração, compilação e instalação:

    ```
    ./configure
    make
    sudo make install
    ```

### 1.2 Para um arquivo .tgz:

O processo é similar ao `.tar.xz`:

1. Abra um terminal.

2. Descompacte o arquivo: `tar -zxvf arquivo.tgz`

3. Substitua `arquivo.tgz` pelo nome do seu arquivo.

4. Navegue até o diretório descompactado: `cd nome_do_diretorio`

    Troque `nome_do_diretorio` pelo nome do diretório resultante.

5. Leia qualquer `README` ou `INSTALL` disponível.

6. **Execute os comandos de instalação (os mesmos do `.tar.xz`):** 

    ```
    ./configure
    make
    sudo make install
    ```

É importante notar que esses passos assumem que você tem as permissões necessárias e as ferramentas de compilação instaladas. Se encontrar erros durante o processo ./configure ou make, eles geralmente indicam a falta de dependências ou problemas de ambiente que precisam ser resolvidos.

## 2. Código completo para configurar/instalar/usar

Para configurar/instalar/usar o `tar.gz` ou `tgz` no `Linux Ubuntu`sem precisar digitar linha por linha, você pode seguir estas etapas:

1. Abra o `Terminal Emulator`. Você pode fazer isso pressionando: `Ctrl + Alt + T`

2. Digite o seguinte comando e pressione `Enter`:

    ```
    NÂO há.
    ```


## Referências

[3] OPENAI. ***Instalar arquivos tar.xz/tgz.*** Disponível em: <https://chat.openai.com/c/0ce53031-41c5-4185-93d7-0156e1d2cb2a> (texto adaptado). Acessado em: 13/03/2024 13:47.

[2] OPENAI. ***Vs code: editor popular.*** Disponível em: <https://chat.openai.com/c/b640a25d-f8e3-4922-8a3b-ed74a2657e42> (texto adaptado). Acessado em: 13/03/2024 13:48.


