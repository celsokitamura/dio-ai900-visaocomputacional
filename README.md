
# Reconhecimento Facial e transformação de imagens em Dados no Azure ML

## Crie um recurso de serviços de IA do Azure

Abra o portal do Azure em https://portal.azure.com, entrando com a conta da Microsoft associada à sua assinatura do Azure.

Clique no botão ＋Criar um recurso e pesquise os serviços de IA do Azure. 

Selecione criar um plano de serviços de IA do Azure. 

Você será levado a uma página para criar um recurso de serviços de IA do Azure. 

Preencha os dados.

Selecione Revisar + criar e depois Criar e aguarde a conclusão da implantação.

## Conecte seu recurso de serviço de IA do Azure ao Vision Studio

Navegue até Vision Studio em https://portal.vision.cognitive.azure.com.

Entre com sua conta e certifique-se de usar o mesmo diretório onde você criou seu recurso de serviços de IA do Azure.

Na página inicial do Vision Studio, selecione Visualizar todos os recursos no título Introdução ao Vision.

Na página Selecione um recurso para trabalhar, passe o cursor do mouse sobre o recurso que você criou acima na lista e marque a caixa à esquerda do nome do recurso e selecione Selecionar como recurso padrão.

Feche a página de configurações selecionando o “x” no canto superior direito da tela.

## Detecte rostos no Vision Studio

Navegue até Vision Studio em https://portal.vision.cognitive.azure.com.

Na página inicial Introdução ao Vision, selecione a guia Face e, em seguida, selecione o bloco Detectar rostos em uma imagem.

No subtítulo Experimente, reconheça a política de uso de recursos lendo e marcando a caixa.

Selecione cada uma das imagens de amostra e observe os dados de detecção facial retornados.

## Ler texto no Vision Studio

### Extraia texto de imagens no Vision Studio

Navegue até Vision Studio em https://portal.vision.cognitive.azure.com.

Na página inicial Introdução ao Vision, selecione Reconhecimento óptico de caracteres e, em seguida, o bloco Extrair texto de imagens.

No subtítulo Experimente, reconheça a política de uso de recursos lendo e marcando a caixa.

No portal, selecione Procurar um arquivo e selecione um arquivo do seu computador com texto e selecione Abrir.

Agora revise o que é retornado:

Nos atributos detectados, qualquer texto encontrado na imagem é organizado em uma estrutura hierárquica de regiões, linhas e palavras.

Na imagem, a localização do texto é indicada por uma caixa delimitadora

## Analise imagens no Vision Studio

### Gerar legendas para uma imagem

Navegue até Vision Studio.

Na página inicial Introdução ao Vision, selecione a guia Análise de imagem e, em seguida, selecione o bloco Adicionar legendas às imagens.

Na página inicial do Vision Studio, a guia Análise de imagem é selecionada e destacada. O bloco Adicionar legendas às imagens está destacado.

No subtítulo Experimente, reconheça a política de uso de recursos lendo e marcando a caixa.

Carregue uma imagem arrastando-a para a caixa "Arrastar e soltar arquivos aqui" ou navegando até ela em seu sistema de arquivos.

Observe o texto da legenda gerado, visível no painel Atributos detectados à direita da imagem.

A funcionalidade Caption fornece uma frase em inglês única e legível que descreve o conteúdo da imagem.

Em seguida, use a mesma imagem para realizar legendas densas. Retorne à página inicial do Vision Studio e, como fez antes, selecione a guia Análise de imagem e, em seguida, selecione o bloco Legenda densa.

O recurso Dense Captions difere do recurso Caption porque fornece várias legendas legíveis para uma imagem, uma descrevendo o conteúdo da imagem e outras, cada uma cobrindo os objetos essenciais detectados na imagem. Cada objeto detectado inclui uma caixa delimitadora, que define as coordenadas dos pixels na imagem associada ao objeto.

Passe o mouse sobre uma das legendas na lista de atributos detectados e observe o que acontece na imagem.

Mova o cursor do mouse sobre as outras legendas da lista e observe como a caixa delimitadora muda na imagem para destacar a parte da imagem usada para gerar a legenda.

## Limpar

Se você não pretende fazer mais exercícios, exclua todos os recursos que não precisa mais. 

Isso evita acumular custos desnecessários.

Abra o portal do Azure em https://portal.azure.com e selecione o grupo de recursos que contém o recurso que você criou.

Selecione o recurso e selecione Excluir e depois Sim para confirmar. O recurso é então excluído.

