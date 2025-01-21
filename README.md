# reduzindo_dimensionalidade_para_redes_neurais

# Processamento de Imagens com OpenCV e PIL

Este repositório contém um script em Python para realizar tarefas básicas de processamento de imagens utilizando bibliotecas como OpenCV, NumPy e PIL. O código foi projetado para ser executado em um ambiente Google Colab e interagir com o Google Drive para carregar e salvar arquivos de imagem.

## Funcionalidades

1. **Integração com Google Drive**: 
   - Montar o Google Drive para acessar imagens armazenadas na nuvem.

2. **Carregamento e Exibição de Imagens**: 
   - Carregar uma imagem do Google Drive utilizando o caminho do arquivo.
   - Exibir a imagem utilizando a biblioteca PIL.

3. **Conversão de Imagens**:
   - Converter a imagem para um formato compatível com OpenCV (formato BGR).
   - Salvar a imagem convertida para processamento posterior.

4. **Processamento de Imagens**:
   - Converter uma imagem colorida para escala de cinza.
   - Binarizar a imagem em escala de cinza (converter para preto e branco).
   - Exibir as imagens original, em escala de cinza e binarizada lado a lado usando Matplotlib.

## Pré-requisitos

Para utilizar este script, certifique-se de ter o seguinte:

- Python 3.12
- Google Colab
- Bibliotecas necessárias:
  - OpenCV
  - NumPy
  - PIL
  - Matplotlib

## Como Usar

1. **Clonar este Repositório**:
   ```bash
   git clone https://github.com/raphaelp-silva/reduzindo_dimensionalidade_para_redes_neurais
   ```

2. **Abrir o Script no Google Colab**:
   - Faça upload do script no Google Colab.

3. **Montar o Google Drive**:
   - Use o seguinte código para montar seu Drive:
     ```python
     from google.colab import drive
     drive.mount('/content/drive')
     ```

4. **Definir o Caminho do Arquivo**:
   - Atualize a variável `file_path_in_drive` com o caminho para seu arquivo de imagem no Google Drive.

5. **Executar o Script**:
   - Execute todas as células do notebook para:
     - Carregar e exibir a imagem.
     - Converter e processar a imagem.
     - Exibir os resultados.

## Estrutura de Arquivos

- `main.py`: O script principal para o processamento de imagens.
- `README.md`: Este arquivo.

## Exemplo de Saída

O script processa uma imagem de entrada e exibe os seguintes resultados:

1. Imagem colorida original.
2. Versão da imagem em escala de cinza.
3. Versão binarizada da imagem.

## Solução de Problemas

- **Imagem Não Encontrada**:
  - Certifique-se de que o caminho do arquivo está correto e que a imagem foi carregada no Google Drive.

- **Erros ao Importar Bibliotecas**:
  - Instale as bibliotecas ausentes usando pip:
    ```python
    !pip install opencv-python pillow matplotlib
    ```

## Licença

Este projeto está licenciado sob a Licença MIT. Fique à vontade para usar, modificar e distribuir este código.

## Contribuições

Contribuições são bem-vindas! Por favor, abra uma issue ou envie um pull request para qualquer melhoria ou correção de bugs.

## Autor

Raphael da Silva

