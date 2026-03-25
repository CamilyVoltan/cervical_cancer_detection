# cervical_cancer_detection
Projeto desenvolvido na disciplina de Projeto Integrador IV, com o objetivo de auxiliar na detecção de anormalidades citológicas em amostras de exames para rastreio do câncer do colo do útero. Devido ao tratamento de dados sensíveis o código e a base de dados são restritos e abertos somente para as desenvolvedoras e orientador do projeto.

Cervical Cancer Detection - Ciência de Dados e Ética
📋 Descrição do Projeto
Projeto desenvolvido na disciplina de Projeto Integrador IV, focado no auxílio à detecção de anormalidades citológicas em amostras de exames para rastreio do câncer do colo do útero. O objetivo é aplicar algoritmos de inteligência artificial para identificar padrões que possam indicar a presença de células pré-cancerosas ou cancerosas.

⚖️ Conformidade Legal e Ética (LGPD)
Em conformidade com a Lei Geral de Proteção de Dados (Lei nº 13.709/2018), este projeto adota as seguintes diretrizes:

Privacidade por Design: O acesso ao dataset original e ao código-fonte de processamento é restrito aos desenvolvedores e orientador, dado que lidam com dados sensíveis de saúde (Art. 5º, II da LGPD).

Segurança da Informação: Medidas de controle de acesso foram implementadas para prevenir o nexo de causalidade em incidentes de segurança, mitigando riscos de responsabilidade civil.

Anonimização: Quaisquer resultados ou métricas exibidos publicamente passaram por processo de anonimização irreversível.

🛠️ Tecnologias e Metodologia
Linguagem: Python

Bibliotecas: Pytorch, Keras e Tensorflow, Numpy, Matplotlib

Hipóteses de Resolução: Redes Neurais Convolucionais para a segmentação de dados, Arquitetura U-net, Arquitetura SegNet, Arquitetura SRM, Arquitetura LeNet, YOLOv3 - Inceptionv3 e Mask R-CNN - ImageNet

Camadas: Batch normalization para a normalização, Filtro de max pooling para reduzir as características, Flatten para achatar os dados para serem aplicados nas camadas densas, Dropout para fazer os ajustes, como hiperparâmetro foi aplicado o otimizador Adam.

Métricas de Avaliação: Acurácia e Validação

Pré-Processamento: Seleção de imagens, Normalização e pesos, Técnica Min e Max (0 a 255)
