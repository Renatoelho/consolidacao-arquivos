# Consolidando Arquivos com Múltiplos Layouts em uma Ùnica Base (OBT)

...

<!--
https://www.youtube.com/@renato-coelho


# Apresentação em vídeo

<p align="center">
  <a href="https://www.youtube.com/@renato-coelho" target="_blank"><img src="thumbnail/Consolidacao-Arquivos.png" alt="Vídeo de apresentação"></a>
</p>
-->

### Requisitos

+ ![Git](https://img.shields.io/badge/Git-2.25.1%2B-E3E3E3)

+ ![Ubuntu](https://img.shields.io/badge/Ubuntu-20.04%2B-E3E3E3)

+ ![Python](https://img.shields.io/badge/Python-3.8%2B-E3E3E3)


## Deploy da aplicação


### Clonando o repositório

```bash
git clone https://github.com/Renatoelho/consolidacao-arquivos.git consolidacao-arquivos
```


### Preparando o ambiente

+ Acessando o diretório clonado
```bash
cd consolidacao-arquivos/
```

+ Criando o ambiente virtual
```bash
python3 -m venv .venv
```

+ Ativando o ambiente virtual
```bash
source .venv/bin/activate
```

+ Instalando as dependências
```bash
pip install -U pip setuptools wheel --no-cache-dir && pip install -r requirements.txt --no-cache-dir
```

+ Ativando o Jupyter Lab
```bash
jupyter lab
```

Agora é só acessar o Notebook que será aberto em seu nevegador ou [http://localhost:8888/tree](http://localhost:8888/tree).


# Referências

...
