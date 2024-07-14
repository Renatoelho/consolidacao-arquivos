# Consolidação de Arquivos Diversos em uma OBT


Este projeto visa a consolidação de arquivos de múltiplas extensões, como ***.xlsx***, ***.txt***, ***.csv*** e ***.json***, cujos layouts são completamente diferentes, em uma única OBT (***One Big Table***). Utilizando a linguagem Python e bibliotecas como ***Pandas***, ***DuckDB***, ***Pydantic*** e ***Jupyter***, o projeto automatiza o processo de leitura, transformação e unificação dos dados. As etapas envolvem o mapeamento dos ***metadados***, onde os ***detalhes*** específicos de cada arquivo são identificados e definidos; a ***estruturação*** dos dados, que garante a conformidade e integridade das informações; e a ***consolidação*** final, onde todos os dados são integrados em uma base única e coerente. O resultado é uma base consolidada e um processo ***automatizado*** eficiente e escalável, facilitando a ***análise*** e o gerenciamento dos dados.


<!--
https://www.youtube.com/@renato-coelho
-->

# Apresentação em vídeo

<p align="center">
  <a href="https://youtu.be/_xYkcEWsui4" target="_blank"><img src="thumbnail/Consolidacao-Arquivos.png" alt="Vídeo de apresentação"></a>
</p>


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

Agora é só acessar o Notebook que será aberto em seu nevegador ou [http://localhost:8888/lab](http://localhost:8888/lab).


# Referências


Designing One Big Table (OBT), **Medium.** Disponível em: <https://leo-godin.medium.com/designing-one-big-table-obt-c1dd797d60ac>. Acesso em: 07 jul. 2024.

Jupyter Notebooks, **DuckDB.** Disponível em: <https://duckdb.org/docs/guides/python/jupyter>. Acesso em: 10 jul. 2024.

User Guide **Pandas.** Disponível em: <https://pandas.pydata.org/docs/user_guide/index.html#user-guide>. Acesso em: 10 jul. 2024.

Configuration, **DuckDB.** Disponível em: <https://duckdb.org/docs/configuration/overview#examples>. Acesso em: 10 jul. 2024.

Installation, **Pydantic.** Disponível em: <https://docs.pydantic.dev/latest/install/>. Acesso em: 09 jul. 2024.

Why use Pydantic?, **Pydantic.** Disponível em: <https://docs.pydantic.dev/latest/why/>. Acesso em: 09 jul. 2024.

Code Generation with datamodel-code-generator, **Pydantic.** Disponível em: <https://docs.pydantic.dev/latest/integrations/datamodel_code_generator/>. Acesso em: 09 junho. 2024.