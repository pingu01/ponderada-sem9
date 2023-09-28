# ponderada-sem9

# Fomentando o Aprendizado Contínuo em Sistemas Conversacionais

## Introdução

Trabalhos recentes mostraram que Modelos de Linguagem, como T5 (Raffel et al., 2019) e GPT-3 (Brown et al., 2020), tem a capacidade de armazenar uma quantidade tremenda do conhecimento do mundo nos seus parâmetros quando pré-treinados em um grande corpo de texto (Petroni et al., 2019). Esses modelos pré-treinados mostraram potencial para servir como bases de conhecimento quando sondados para conhecimento do mundo sem nenhum ajuste fino através da tarefa "Language Model Analysis (LAMA)", que requer sondar Modelos de Linguagem para o conhecimento da humanidade, de uma maneira zero-shot (informações que não foram vistas no treino), através de preenchimento de slots, e resultados promissores utilizando o conhecimento do mundo codificado, quando refinados em vários "Knowledge Intensive Language Tasks" (KILT) (Petroni et al., 2021). 

Embora o conhecimento do mundo armazenado nos Modelos de Linguagem tenha diversos casos de uso, ele pode rapidamente ficar desatualizado à medida que o mundo evolui, e os modelos de linguagem precisam renovar frequentemente de acordo com a evolução da sociedade. Por exemplo, é impossível sondar por novas informações como "quem ganhou a eleição dos EUA 2020" do T5 original (Raffel et al., 2019), que foi pré-treinado com o corpo da web C4 de abril de 2019.

## Solução Proposta

### Diagrama de Blocos

![Diagrama de Blocos](link_para_imagem_do_diagrama.png)



## Conclusão

## Referências Bibliográficas

1. JANG, Joel et al. Towards continual knowledge learning of language models. arXiv preprint arXiv:2110.03215, 2021.