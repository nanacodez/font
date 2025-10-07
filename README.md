# configurando a fonte jetbrains mono no vs code

este é um guia rápido para instalar e configurar a fonte **jetbrains mono**, otimizada para desenvolvedores, no seu visual studio code.

---

### download

primeiro, baixe a fonte diretamente do site oficial:

* **link para download:** [jetbrains mono](https://www.jetbrains.com/pt-br/lp/mono/)

---

### passos para instalação

1.  **abra a pasta `fonts`**
    * após descompactar o arquivo, entre na pasta `fonts`.
    <br/>
    <img src="https://github.com/user-attachments/assets/719dab8d-8d68-4e33-a511-3d0cab46f8fa" width="80" />

2.  **acesse a pasta `ttf`**
    * dentro da pasta `fonts`, localize e abra a pasta `ttf` que contém os arquivos da fonte truetype.
    <br/>
    <img src="https://github.com/user-attachments/assets/d6e0ff8c-eabd-496d-b775-998f72326086" width="80" />

3.  **instale as fontes**
    * selecione todos os arquivos (use o atalho `ctrl + a`), clique com o botão direito e escolha a opção **instalar**.
    <br/>
    <img src="https://github.com/user-attachments/assets/15d0d80c-30ec-4f6f-8b06-680e11e642b0" width="500" />

---

### configuração no vs code

1.  **abra as configurações do usuário (json)**
    * no vs code, pressione `ctrl + shift + p` para abrir a paleta de comandos.
    * digite `open user settings json` e selecione a primeira opção.
    <br/>
    <img src="https://github.com/user-attachments/assets/bba9942d-dabc-4273-ae46-69210db67ed3" width="400" />

2.  **adicione o código de configuração**
    * clique no link abaixo para acessar o arquivo com o código de configuração. copie todo o conteúdo dele e cole dentro do seu arquivo `settings.json`.

    * **link para o arquivo de configuração:** [**font.json**](./font.json)

pronto! agora seu vs code está configurado com a nova fonte.
