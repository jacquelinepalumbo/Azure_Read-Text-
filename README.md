# Read text in Vision Studio

_Explore the optical character recognition capabilities of Azure AI Vision_

## Criar um recurso de serviços de _IA do Azure_

Você pode usar os recursos de OCR do Azure AI Vision com um recurso multisserviço dos **serviços de IA do Azure**. Se você ainda não tiver feito isso, crie um recurso de **serviços de IA do Azure** em sua assinatura do Azure.

1. Em outra guia do navegador, abra o **portal do Azure** em [https://portal.azure.com](https://portal.azure.com), entrando com a conta da Microsoft associada à sua assinatura do Azure.

2. Clique no botão **+Criar um recurso** e procure serviços de IA do Azure. Selecione **criar** um plano de **serviços de IA do Azure**. Você será levado a uma página para criar um recurso de serviços de IA do Azure. Configure-o com as seguintes configurações:

* **Assinatura**: sua assinatura do Azure.
* **Grupo de recursos**: selecione ou crie um grupo de recursos com um nome exclusivo.
* **Região**: Leste dos EUA.
* **Nome**: insira um nome exclusivo.
* **Nível de preços**: Standard S0.

3. **Ao marcar esta caixa, reconheço que li e entendi todos os termos abaixo**: _Selecionado_.
   
Selecione **Revisar** + **criar** e, em seguida, Criar e aguarde a conclusão da implantação.

## Conectar seu recurso de serviço de IA do Azure ao Vision Studio

Em seguida, conecte o recurso de serviços de IA do Azure provisionado acima ao Vision Studio.

1. Em outra guia do navegador, navegue até **o Vision Studio** em [https://portal.vision.cognitive.azure.com](https://portal.vision.cognitive.azure.com).

2. Entre com sua conta e verifique se você está usando o mesmo diretório em que criou seu recurso de serviços de IA do Azure.

3. Na home page do Vision Studio, selecione **Exibir todos os recursos** no cabeçalho **Introdução ao Vision**.

<img width="626" alt="image" src="https://github.com/jacquelinepalumbo/Azure_Detect-Faces/assets/119548193/5bb0961c-9003-4e29-872e-b7aae15e4fb5">

4. Na página **Selecione um recurso para trabalhar**, passe o cursor do mouse sobre o recurso criado acima na lista e marque a caixa à esquerda do nome do recurso e selecione **Selecionar como recurso padrão**.

<img width="933" alt="image" src="https://github.com/jacquelinepalumbo/Azure_Detect-Faces/assets/119548193/e6e8a1e0-ff03-4986-b6e1-a79d09d57481">

5. Feche a página de configurações selecionando o "x" no canto superior direito da tela.


# Extrair texto de imagens no Vision Studio

1. Em um navegador da Web, navegue até o **Vision Studio** em [https://portal.vision.cognitive.azure.com](https://portal.vision.cognitive.azure.com).

2. Na página inicial **Introdução ao Vision**, selecione **Reconhecimento óptico de caracteres** e o bloco **Extrair texto de imagens**.

3. No subtítulo **Experimentar**, reconheça a política de uso de recursos lendo e marcando a caixa.

4. Selecione [https://aka.ms/mslearn-ocr-images](https://aka.ms/mslearn-ocr-images)para baixar **ocr-images.zip**. Em seguida, abra a pasta.

5. No portal, selecione **Procurar um arquivo** e navegue até a pasta no computador em que você baixou **ocr-images.zip**. Selecione **advert.jpg** e selecione **Abrir**.

6. Agora reveja o que é devolvido:
   * Em **Atributos detectados**, qualquer texto encontrado na imagem é organizado em uma estrutura hierárquica de regiões, linhas e palavras.
   * Na imagem, a localização do texto é indicada por uma caixa delimitadora, como mostrado aqui:
  
     <img width="608" alt="image" src="https://github.com/jacquelinepalumbo/Azure_Read-Text-/assets/119548193/f24a3156-d48e-44ce-b4ef-e23e310f0120">

7. Agora você pode tentar outra imagem. Selecione **Procurar um arquivo** e navegue até a pasta onde você salvou os arquivos do GitHub. Selecione **letter.jpg**.

   <img width="592" alt="image" src="https://github.com/jacquelinepalumbo/Azure_Read-Text-/assets/119548193/36820b05-a999-4a03-9931-ace31937e308">



8. Analise os resultados da segunda imagem. Ele deve retornar o texto e as caixas delimitadoras do texto. Se tiver tempo, tente **note.jpg** e **receipt.jpg**.


   

    <img width="745" alt="image" src="https://github.com/jacquelinepalumbo/Azure_Read-Text-/assets/119548193/748ece9d-c8ba-49d4-b200-c979c894d0bc">
   
   
   
   <img width="782" alt="image" src="https://github.com/jacquelinepalumbo/Azure_Read-Text-/assets/119548193/6515c0b5-3305-4c4e-9707-13ed31214a09">
   


   <img width="838" alt="image" src="https://github.com/jacquelinepalumbo/Azure_Read-Text-/assets/119548193/b3ca0b1b-af88-4c20-897f-8df41188d604">
   



   <img width="796" alt="image" src="https://github.com/jacquelinepalumbo/Azure_Read-Text-/assets/119548193/7e563d78-c2e0-42ff-b9ed-ceca07249e10">




