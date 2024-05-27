# Azure-AI-Search

> [!NOTE]
> O passo a passo é a partir da criação dos recurso, não antes disso.

>[!WARNING]
>Documentacao para preenchimento (https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html)

Acesse o link [speech](https://speech.microsoft.com/)

## Faca o login

Na categoria AI + machine learning 

Selecione Azure AI Studio
![studio](./assets/1AiSearch.PNG)

No cabecalho selecione a opcao **+ Create**
![homeCreate](./assets/2AiSearch.PNG)

Preencha os campos conforme a documentacao
![create](./assets/3Create.PNG)

> [!NOTE]
> A opcao deve ser a **BASIC**
![price](./assets/4SelectPrice.PNG)

De volta ao home na aba lateral selecione **+ Create a resource**

Selecione **Azure AI Service**
![service](./assets/5AiService.PNG)

Crie o servico conforme a documentacao
![createService](./assets/6CreateService.PNG)

Verifique se na home do Servico foi criado
![homeService](./assets/7HomeService.PNG)

De volta ao home na aba lateral selecione **Storage Account**
![storage](./assets/8StorageAccount.PNG)

Seelcione Create preencha os campos conforme a documentacao
![createStorage](./assets/9CreateStorageAccount.PNG)

Verifique se na home do Storage foi criado
![homeStorage](./assets/10HomeStorageAccount.PNG)

Selecione o storage que voce criou

Na opcao que ira apresentar, preencha os campos conforme a documentacao
![createContainer](./assets/11CreateContainer.PNG)

> [!NOTE]
> Nas configuracoes habilite a opcao **Allow Blob anonymous**

> Conforme a imagem
![sotageConfig](./assets/11StorageConfig.PNG)

Em uma nova guia do navegador, baixe **zipped coffee reviews** e extraia os arquivos para a pasta de avaliações.

No portal do Azure, selecione o **coffe-reviews** contêiner. No contêiner, selecione **Upload**.
![upload](./assets/12UploadStorage.PNG)
