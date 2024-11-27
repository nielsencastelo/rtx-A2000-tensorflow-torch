# Configuração de GPU RTX A2000 para TensorFlow e PyTorch no Windows 11

Este guia descreve como configurar uma GPU NVIDIA RTX A2000 para uso com bibliotecas de aprendizado profundo, como TensorFlow e PyTorch, no ambiente Windows 11. A configuração inclui a instalação de drivers necessários, ferramentas CUDA e cuDNN, além de instruções para validação do funcionamento das bibliotecas.

## Os dois notebooks fornecidos apresentam uma série de passos detalhados para configurar e utilizar a GPU NVIDIA RTX A2000 no ambiente Windows 11 para executar tarefas de aprendizado profundo utilizando TensorFlow e PyTorch.

Cada notebook guia o usuário pela instalação e configuração de ferramentas essenciais, incluindo:

- Instalação e Configuração de CUDA e cuDNN:
    - Ambos os notebooks detalham como configurar o CUDA Toolkit (versão 11.6) e o cuDNN (versão 8.6.0) para que a GPU seja utilizada de forma eficiente.

    - Instalação das Dependências Necessárias:
        São listadas bibliotecas específicas para cada framework, como tensorflow-gpu para TensorFlow e torch para PyTorch, além de outras ferramentas auxiliares para análise e visualização de dados, como pandas, scikit-learn e matplotlib.

    - Execução de Scripts de Validação:
        Ambos incluem códigos práticos para testar e validar se a GPU está sendo utilizada corretamente por cada biblioteca:
            No TensorFlow, um script básico de operações com tensores é utilizado.
            No PyTorch, um script verifica a disponibilidade da GPU e exibe informações sobre o dispositivo.

Esses notebooks fornecem uma base sólida para configurar o ambiente e executar tarefas de aprendizado profundo, garantindo que sua GPU RTX A2000 esteja corretamente integrada aos frameworks de IA mais populares.