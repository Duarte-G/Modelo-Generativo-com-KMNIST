# Modelo Generativo com KMNIST
Este repositório contém a implementação de um modelo de redes GANs utilizando o dataset KMNIST, que inclui caracteres da escrita japonesa. O objetivo do projeto foi gerar novas amostras de caracteres a partir de um espaço latente, com o gerador criando imagens realistas e o discriminador avaliando a autenticidade dessas imagens.

## Resultados
O modelo foi treinado por 200 épocas. Durante o treinamento, foi observada uma melhoria progressiva na qualidade das imagens geradas. No entanto, algumas amostras ainda apresentaram ruídos, como mostrado na imagem de exemplo:

<p align="center">
  <img src="https://github.com/user-attachments/assets/3cbc4dae-a941-436a-aeae-a5e9b2dc1366">
</p>

Embora os resultados não sejam perfeitos, este projeto serviu como um exercício extra para reforçar os conceitos de GANs. Considerando o número relativamente baixo de épocas, estou satisfeito com os resultados obtidos. O foco foi mais na compreensão da arquitetura GAN do que na perfeição das gerações. Há, no entanto, espaço para melhorias com ajustes nos hiperparâmetros, aumento das épocas de treinamento e otimizações no design das redes geradora e discriminadora.

## Como Usar
 - Clone o repositório para sua máquina local.
 - Instale as bibliotecas necessárias no código.
 - Execute o .ipynb para explorar o código e resultados.
 - Sinta-se à vontade para realizar melhorias ou alterar a base de dados.
