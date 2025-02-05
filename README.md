# python_background_subtraction

Este repositório contém um Jupyter Notebook que demonstra a técnica de subtração de fundo utilizando a filtragem mediana temporal com a biblioteca OpenCV. O notebook é otimizado para execução no **Google Colab**, permitindo testar e visualizar os resultados diretamente na nuvem.

---

## Notebook

### `temporal_median_filtering.ipynb` [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KauaHenSilva/python_background_subtraction/blob/main/temporal_median_filtering.ipynb)

**Funcionalidade:** Subtração de fundo utilizando a filtragem mediana temporal.

Este notebook implementa a técnica de filtragem mediana temporal para subtração de fundo em vídeos.

#### Principais Funcionalidades:
- Carregamento de vídeos armazenados no Google Drive.
- Cálculo da mediana temporal dos quadros do vídeo.
- Subtração de fundo utilizando a mediana temporal.
- Exibição dos resultados diretamente no notebook.

---

## Como Usar no Google Colab

Para executar o notebook no Google Colab, siga os passos abaixo:

1. **Acesse o Google Colab:**
  - Abra o [Google Colab](https://colab.research.google.com/).

2. **Carregue o Notebook:**
  - Clique em `Arquivo` > `Abrir notebook`.
  - Escolha a aba `GitHub` e insira o link deste repositório.
  - Selecione o notebook `temporal_median_filtering.ipynb`.

3. **Conecte ao Google Drive (se necessário):**
  - O notebook exige acesso ao Google Drive para carregar vídeos.

4. **Execute as Células:**
  - Conecte-se ao ambiente clicando em `Conectar` no canto superior direito.
  - Execute as células sequencialmente para processar o vídeo e visualizar os resultados.

5. **Teste com seus Próprios Vídeos (Opcional):**
  - Faça o upload de um vídeo diretamente no Google Colab usando:
    ```python
    from google.colab import files
    uploaded = files.upload()
    ```
  - Substitua o caminho do vídeo no notebook pelo arquivo enviado.

---