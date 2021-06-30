# TCC2

## Baseado no trabalho realizado por,
ANTIPOV, G.; BACCOUCHE, M.; DUGELAY, J.-L. **Face aging with conditionalgenerative adversarial networks.2017 IEEE International Conference onImage Processing (ICIP)**, IEEE, p. 2089–2093, Sept. 2017. Disponível em:<https://ieeexplore.ieee.org/document/8296650>.


## Base de dados utilizada:

ROTHE, R.; TIMOFTE, R.; GOOL, L. V. Dex: Deep expectation of apparent agefrom a single image. In:**2015 IEEE International Conference on ComputerVision Workshop (ICCVW)**. IEEE, 2015. p. 252–257. Disponível em: <https://ieeexplore.ieee.org/document/7406390>.

- URL para o IMDB: https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/
}


## Modelo baseado pelo proposto pela comunidade:
https://github.com/Vishal-V/GSoC-TensorFlow-2019/tree/master/face_app

### Versionamento:
**Versionamentos com relação ao que esta sendo executado na minha máquina**

**Python**
- Versão 3.7.3
- No repositório mantido pela comunidade não foi informado o versionamento da versão python

**Tensorflow**
- Versão 2.0.0b1

**Keras**
- A versão utilizada é a mesma instalada automáticamente com o tensorflow ao realizar o comando `pip install tensorflow==2.0.0b1`
- Porém, observando os arquivos da biblioteca. Pude observar que no arquivo __ init __.py o versionamento 1.1.2

### Dependências
- Dependências que estão sendo utilizadas inicialmente (As mesmas utilizadas pela comunidade):
```
tensorflow==2.0.0b1
absl_py==0.7.0
numpy==1.16.4
matplotlib==2.2.3
scipy==1.1.0
```

- Para instalar as dependências foi utilizado o arquivo `dependencias.txt`, executando o seguinte comando:
```
pip install -r dependencias.txt
``` 


### Dataset
- O dataset inicialmente esta sendo testado com o original, sem nenhuma alteração. O mesmo pode ser baixado pelo script realizado pela comunidade.
- Basta executar o arquivo `download_dataset.py`
```
python download_dataset.py
```


### Execução do modelo
- Tendo as dependências instaladas e o dataset baixado e no mesmo diretório, foi executado o comando:
```
python model.py
```
