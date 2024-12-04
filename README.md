# Dupla55-Ciencia_de_Dados_Projeto-10
IMPLEMENTAÇÃO E ANÁLISE DE CLASSIFICAÇÃO COM REDES CONVOLUCIONAIS E O DATASET CUFS

Descrição do Projeto:

O presente relatório técnico descreve a implementação e avaliação de redes convolucionais (CNNs) para a tarefa de classificação de imagens. Utilizando o dataset CUHK Face Sketch Database (CUFS), buscamos classificar imagens faciais de acordo com o sexo biológico (masculino ou feminino).

Instalação: O projeto pode ser implementado por meio de qualquer compilador Python. as bibliotecas apresentadas no código devem ser instaladas, e devem ser feitas alterações no diretório dos arquivos csv caso seja implementada em outro notebook do COLAB, ou outros compilador.

Como Executar: Utilize um compilador Python, como o COLAB ou Vs Code.

Estrutura dos Arquivos: O programa em Python está armazenado na pasta do drive: https://drive.google.com/drive/folders/1uqVFDFJtmxeD29SF7mNU1TOWYFBDDZkx ou Meu Drive/Colab Notebooks

e utliza os arquivos localizado no seguinte diretório: https://drive.google.com/drive/folders/1esutBj5u6hTOvZa8qul238ZTj7CyUoMe

Tecnologias Utilizadas: O programa foi escrito na linguagem Python
Versão do Python: 3.10.12

Bibliotecas utilizadas:

Foram utilizadas as bibliotecas TensorFlow/Keras, Pandas, NumPy, Matplotlib, Scikit-learn, Google Colab Drive, Shutil e ImageDataGenerator.

Conclusões e reflexões sobre os resultados obtidos:

O modelo final alcançou uma acurácia de 71,05%, com AUC-ROC de 0,6859, indicando uma moderada capacidade de separação entre as classes. O F1-Score foi de 0,6154, demonstrando uma melhora significativa no equilíbrio entre precisão e recall. O ajuste no limiar de classificação contribuiu para essa melhoria nas métricas, mostrando que o modelo respondeu bem às otimizações realizadas nos hiperparâmetros e no treinamento. Os resultados  pode ser considerados moderados. Dataset limitado e com classes desbalanceadas foi um  desafio, muitos ajustes forma nescessários para atingir esse resultado.

Uma solução para melhorar o modelo, dado o dataset limitado e sem expansão, seria utilizar inputs dinâmicos com rotulação manual, permitindo supervisão humana no ajuste de erros e padrões difíceis. Esse processo envolve revisão de imagens classificadas, ajustes no modelo com base em erros e documentação das correções para validar melhorias. Além disso, intervenção direta no treinamento pode auxiliar no ajuste de pesos e otimização dos hiperparâmetros. Essa abordagem combina supervisão humana e aprendizado automático para maximizar o desempenho em cenários desafiadores.

Autores e Colaboradores: Leonardo dos Santos Vaz Ivanildo Gomes da Silva
