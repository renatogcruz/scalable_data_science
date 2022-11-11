# scalable data science

https://henriqueajnb.github.io/data-science-escalavel/README.html

## As ferramentas usadas nesse template são:

- [Poetry](https://python-poetry.org/): gerenciamento de pacotes e ambientes virtuais.

- [hydra](https://hydra.cc/docs/intro/): gerenciamento de arquivos de configuração.

- [plugins do pre-commit](https://pre-commit.com/): automação na formatação e revisão do código.

- [DVC](https://dvc.org/): versionamento de dados e experimentos.

- [pdoc](https://pdoc.dev/): criação de documentação automática para a API do seu projeto.

## Dependências e ambiente virtual

Este projeto usa o [Poetry](https://python-poetry.org/). O motivo é porque o Poetry nos permite:

- Separar as dependências principais das dependências indiretas em dois arquivos diferentes, ao invés de colocar todas elas em um único arquivo requirements.txt.

- Criar arquivos de dependência mais legíveis.

- Remover todas as dependências indiretas ao remover um pacote.

- Evitar instalar novos pacotes que são conflitantes com aqueles preexistentes.



