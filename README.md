# Detector de Emoções

## 1. Requisitos

Crie uma pasta nova no seu computador e coloque os arquivos Python e o arquivo de dados dentro dela.

Certifique-se de ter o Python instalado em sua máquina.

## 2. Configurações do projeto

No terminal:

1. Clone o repositório: `git clone https:\\...`.

2. Abra dentro da pasta que você baixou e digite: `cd {CAMINHO DA PASTA}`.

3. Crie um ambiente virtual: `python -m venv venv`.
  
4. Ative ele(windows): `.\venv\Scripts\activate`.
5. Ative ele(linux/mac): `source venv/bin/activate`.

6. Instale as dependências: `pip install -r requirements.txt`.

## 3. Como executar

Antes de usar o classificador, é necessário treinar a IA para que ela aprenda os padrões de sentimento.

Digite no terminal: `python treinamento_sklearn.py`

## 4. Como usar

Após o treinamento, você pode classificar qualquer música:

1. Crie um arquivo de texto (ex: `letra.txt`) na pasta do projeto.

2. Cole a letra da música (em inglês) dentro deste arquivo e salve

3. 3. No terminal, execute o comando apontando para seu arquivo : `python classificador_sklearn.py letra.txt`

4. O resultado aparecerá no terminal mostrando a classificação emocional verso a verso, a emoção predominante, a contagem de votos e a média de probabilidade



