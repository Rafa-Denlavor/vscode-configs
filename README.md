# Configurando o VS Code para Desenvolvedores

Este guia detalha as etapas necessárias para configurar o VS Code como um ambiente de desenvolvimento minimalista.

### Pré-requisitos

1. **Instalar o VS Code:** Baixe e instale a versão mais recente do VS Code para o seu sistema operacional em [https://code.visualstudio.com/download](https://code.visualstudio.com/download).
2. **Criar uma conta Microsoft (opcional):** Uma conta Microsoft é necessária para instalar extensões da [VS Code Marketplace](https://marketplace.visualstudio.com/). Você pode criar uma conta gratuitamente ou usar sua conta existente.

### Etapas de Configuração

**1. Instalar Extensões:**

* **Extensões Essenciais:**
    * **[Live Server:](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)** Inicie automaticamente um servidor web para visualizar suas alterações em tempo real. Bom para projetos em HTML.
    * **Portuguese Language Pack:** Traduza a interface do VS Code para português.
    * **Emmet:** Aumente sua produtividade com atalhos para edição de código HTML, CSS e JavaScript.
    * **[JetBrains Mono. A typeface for developers​:](https://marketplace.visualstudio.com/items?itemName=NarasimaPandiyan.jetbrainsmono)** Irá conter as fontes que utilizaremos para personalizar os arquivos e terminal.
    * **[Min Theme​:]((https://marketplace.visualstudio.com/items?itemName=miguelsolorio.min-theme)o)** Tema dark utilizado pra personalizar a cor do VS Code e do código escrito.
    * **[Symbols:](https://marketplace.visualstudio.com/items?itemName=miguelsolorio.symbols)** Utilizado para adicionar ícones personalizados e modernos para cada pasta e arquivo do projeto.
    * **[tldraw:](https://marketplace.visualstudio.com/items?itemName=tldraw-org.tldraw-vscode)s)** Útil para realizar anotações e até mesmo fluxogramas simples para auxiliar em explicações ou organizar os pensamentos.
    * **[Prettier - Code formatter:](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)** Para formatar arquivos.
* **Outras Extensões Úteis:**
    * **[Thunder Client:](https://marketplace.visualstudio.com/items?itemName=rangav.vscode-thunder-client)** Similar o Postman, esta ferramenta possibilita criar requisições com poucas rapidamente para testar os novos endpoints do seu servidor.
* **Instalando Extensões:**
    * Abra a [VS Code Marketplace](https://marketplace.visualstudio.com/).
    * Pesquise por extensões por nome ou funcionalidade.
    * Clique na extensão desejada e depois em **Install**.
    * Reinicie o VS Code para que as extensões sejam carregadas.

**3. Configurar o Settings.json:**

* **Acesse o Settings.json:**
    * No menu **Code**, clique em **Preferences** > **Settings** (ou **Code** > **Settings** no macOS).
    * Na parte inferior esquerda, clique em **"{}"** para abrir o arquivo `settings.json`.
* **Adicionar Configurações:**
    * Adicione ou modifique as configurações JSON para personalizar ainda mais o VS Code.
    * Documentação completa sobre as configurações: [https://code.visualstudio.com/docs/getstarted/settings](https://code.visualstudio.com/docs/getstarted/settings)
    * Na raiz deste repositório, copie e cole o arquivo settings.json e cole no seu VS Code após instalar as extensões.
* **Exemplo de Configurações:**
    ```json
    {
    // Exemplo
    
        // Habilitar numeração de linhas
        "editor.lineNumber": true,

        // Definir tabulação como 4 espaços
        "editor.tabSize": 4,

        // Habilitar atalhos de teclado em modo Zen
        "zenMode.lint": true
    }
    ```

**4. Ajustes Adicionais:**

* **Integração com Ferramentas de Desenvolvimento:** Configure integrações com ferramentas de desenvolvimento que você usa, como gerenciadores de pacotes, linters e ferramentas de controle de versão.
* **Gerenciamento de Espaços de Trabalho:** Crie e gerencie múltiplos espaços de trabalho para diferentes projetos ou ambientes de desenvolvimento.
* **Extensões de Linguagem:** Instale extensões de linguagem para obter suporte a sintaxe, formatação e recursos específicos para linguagens de programação que você usa.

**5. Recursos Adicionais:**

* **Documentação do VS Code:** [https://code.visualstudio.com/docs](https://code.visualstudio.com/docs)
* **Tutoriais do VS Code:** [https://www.youtube.com/channel/UCs5Y5_7XK8HLDX0SLNwkd3w](https://www.youtube.com/channel/UCs5Y5_7XK8HLDX0SLNwkd3w)
* **Comunidade do VS Code:** [https://github.com/microsoft/vscode-discussions](https://github.com/microsoft/vscode-discussions)

Lembre-se que esta é uma configuração que me agrade, porém que pode sofrer alterações. Explore as diversas opções disponíveis para criar um ambiente de desenvolvimento ideal para você.

