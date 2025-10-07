# Configurando a Fonte JetBrains Mono no VS Code

Este é um guia rápido para instalar e configurar a fonte **JetBrains Mono**, otimizada para desenvolvedores, no seu VS Code.

---

### Download

Primeiro, baixe a fonte diretamente do site oficial:

* **Link para Download:** [JetBrains Mono](https://www.jetbrains.com/pt-br/lp/mono/)

---

### Passos para Instalação

1.  **Abra a pasta `fonts`**
    * Após descompactar o arquivo, entre na pasta `fonts`.
    <br/>
    <img src="https://github.com/user-attachments/assets/719dab8d-8d68-4e33-a511-3d0cab46f8fa" width="80" />

2.  **Acesse a pasta `ttf`**
    * Dentro da pasta `fonts`, localize e abra a pasta `ttf` que contém os arquivos da fonte TrueType.
    <br/>
    <img src="https://github.com/user-attachments/assets/d6e0ff8c-eabd-496d-b775-998f72326086" width="80" />

3.  **Instale as fontes**
    * Selecione todos os arquivos (use o atalho `Ctrl + A`), clique com o botão direito e escolha a opção **Instalar**.
    <br/>
    <img src="https://github.com/user-attachments/assets/15d0d80c-30ec-4f6f-8b06-680e11e642b0" width="500" />

---

### Configuração no VS Code

1.  **Abra as Configurações do Usuário (JSON)**
    * No VS Code, pressione `Ctrl + Shift + P` para abrir a paleta de comandos.
    * Digite `open user settings json` e selecione a primeira opção.
    <br/>
    <img src="https://github.com/user-attachments/assets/bba9942d-dabc-4273-ae46-69210db67ed3" width="400" />

2.  **Adicione o código de configuração**
    * Copie o código abaixo e cole dentro do seu arquivo `settings.json` para definir a `JetBrains Mono` como a fonte padrão e habilitar os *font ligatures*.

    ```json
    {
        "editor.fontFamily": "JetBrains Mono",
        "editor.fontLigatures": true,
        "editor.fontSize": 14
    }
    ```
    <br/>
    <img src="https://github.com/user-attachments/assets/a752cf3b-04cb-4efe-b20c-6830cfcebf5e" width="350" />

Pronto! Agora seu VS Code está configurado com a nova fonte.

