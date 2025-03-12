Criar um Serviço no Azure(Ai search + AI service + storage account)

-Acesse o portal do Azure (portal.azure.com).

-No menu lateral, clique em Criar um recurso.

-Procurar por Azure AI Search e selecione a opção disponível.

-Clique em Criar e preencha os seguintes campos:

Nome do serviço: Um nome exclusivo para a instância.

Grupo de recursos: Escolha um grupo já existente ou crie um novo.

Nível de preço: Escolha o plano conforme a necessidade (Basic(ai-search) e standard(storage account).


-Após configurar storage account - você deve alterar as configurações de segurança para permitir acesso

anonimo de blob

-criar novo container com nome coffeereviews com : Nível de acesso anônimo

Blob (acesso de leitura anônimo somente para blobs)

-fazer download de arquivos na documentação e realizar upload no container criado - https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html#upload-documents-to-azure-storage


![image](https://github.com/user-attachments/assets/8f335f87-c0e1-4fb5-918b-99f3896e987b)

-Após realizar upload de arquivos, ir no recurso ai search e importar os dados do container

