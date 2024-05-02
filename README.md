# Este repositório demonstra como é um modelo de visão computacional simples pelo google colab/google teachable machine.

# GitPage: https://bernardoliveirafiap.github.io/GITvisaocomput/


# Explicativo:
Importação de bibliotecas necessárias: As bibliotecas necessárias para a execução do código são importadas. Isso inclui cv2 para processamento de imagem, numpy para manipulação de array, keras para carregar o modelo de aprendizado de máquina e google.colab.patches para exibir imagens.

Carregamento do modelo: O modelo de aprendizado de máquina previamente treinado é carregado. Este modelo é usado para fazer previsões sobre a imagem fornecida.

Carregamento das etiquetas: As etiquetas que o modelo foi treinado para reconhecer são carregadas. Estas etiquetas são usadas para interpretar a saída do modelo.

Leitura da imagem: A imagem é lida do caminho fornecido. Se a imagem não puder ser carregada, uma mensagem de erro será impressa.

Processamento da imagem: Se a imagem for carregada com sucesso, ela será redimensionada para o tamanho que o modelo espera (224x224 pixels) e normalizada para ter valores entre -1 e 1.

Previsão: O modelo faz uma previsão sobre a imagem processada. A previsão é um array de probabilidades, uma para cada etiqueta que o modelo foi treinado para reconhecer.

Interpretação da previsão: A etiqueta com a maior probabilidade é selecionada como a previsão do modelo. A pontuação de confiança da previsão é calculada como a probabilidade da etiqueta prevista.

Exibição dos resultados: A imagem original e a previsão do modelo são exibidas. A previsão inclui a etiqueta prevista e a pontuação de confiança.

Espera por entrada do teclado: O script aguarda a entrada do teclado do usuário. Se a tecla ‘esc’ for pressionada, todas as janelas de imagem abertas serão fechadas.

![image](https://github.com/BernardoliveiraFiap/Visao_Computacional/assets/126569987/48c02f6e-93f1-4eb6-8876-5edeae09cee0)



# Integração do Tensorflow.js com Html e Css: 
https://github.com/BernardoliveiraFiap/GITvisaocomput
