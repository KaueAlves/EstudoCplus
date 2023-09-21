# EstudoCplus

## Problemas

    1. Problema em rodar utilizando o Developer command prompt, o programa só executava arquivos na raiz e gerada muito lixo.
    2. Só executa 1 arquivo de cada vez
    3. Build não sendo executado ao apertar f5
    4. Não sei buildar um projeto com muitas pastas e arquivos .cpp dentro das subpastas


## Soluções ou Contornos

    1. Instalado o Mingw-x64 windows - https://code.visualstudio.com/docs/languages/cpp#_example-install-mingwx64-on-windows (Instalação e adição do C:\msys64\mingw64 e C:\msys64\ucrt64\bin )
    2. Alterado o tasks.json, trocando o nome do arquivo por *.cpp
    3. Existe um comando especifico para executar programas em c++, adicionei a hotkey Ctrl+f6 para executar o projeto.