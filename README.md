# DP05-IA-Generativa-com-Copilot-e-OpenAI
## 1º Laboratório do Desafio 5
### Acessando Copilot 
Abra o Microsoft Copilot.https://copilot.microsoft.com
Digite um prompt: . Você verá um Pesquisando por:... e Gerando... aparecer antes da resposta. 

![image](https://github.com/acdolive/DP05-IA-Generativa-com-Copilot-e-OpenAI/assets/162451624/bd782ee1-87d0-44b9-b82f-4ec5d6202947)

![image](https://github.com/acdolive/DP05-IA-Generativa-com-Copilot-e-OpenAI/assets/162451624/045543da-a9a8-476e-b3f0-a7620cd347e4)

Exemplo de geração de imagem.

![image](https://github.com/acdolive/DP05-IA-Generativa-com-Copilot-e-OpenAI/assets/162451624/b67a9ba2-472c-4696-b6c6-022a90ac17be)

## 2º Laboratário do Desafio 5
### Explorando os Recursos de IA Generativa
Antes de começar você precisará de uma assinatura do Azure para acessar o serviço Azure OpenAI para modelos de texto e código e modelos de geração de imagem DALL-E.

- Para se inscrever em uma assinatura gratuita do Azure, visite https://azure.microsoft.com/free.
- Para solicitar acesso ao serviço Azure OpenAI, visite https://aka.ms/oaiapply.
- Provisionar um recurso do Azure OpenAI

Antes de poder usar modelos do Azure OpenAI,  provisionar um recurso do Azure OpenAI em sua assinatura do Azure.

Entre no portal do Azure.
Crie um recurso do Azure OpenAI com as seguintes configurações:
Assinatura: uma assinatura do Azure que foi aprovada para acesso ao serviço Azure OpenAI.
Grupo de recursos: escolha um grupo de recursos existente ou crie um novo com um nome de sua escolha.
Região: Leste dos EUA*
Nome: Um nome exclusivo de sua escolha
Nível de preços: Standard S0
* Diferentes regiões têm disponibilidade e cota diferentes para modelos. Neste exercício, você usará um modelo GPT-35-Turbo para geração de texto e um modelo DALL-E para geração de imagem, ambos fornecidos no leste dos EUA.

Aguarde a conclusão da implantação. Em seguida, vá para o recurso Azure OpenAI implantado no portal do Azure.
Explore Azure OpenAI Studio
Você pode implantar, gerenciar e explorar modelos em seu Serviço Azure OpenAI usando o Azure OpenAI Studio.

Na página Visão geral do recurso Azure OpenAI, use o botão Explorar para abrir o Azure OpenAI Studio em uma nova guia do navegador. Como alternativa, navegue até o Azure OpenAI Studio diretamente.

Quando você abre o Azure OpenAI Studio pela primeira vez, ele deve ser semelhante a este:
