# A crise da habitação em Portugal

Documento aberto para informar, explicar e apoiar o debate público sobre a habitação em Portugal.

**Comece a ler em [docs/README.md](docs/README.md).** Todo o conteúdo está na pasta [`docs/`](docs/):

- [Diagnóstico](docs/diagnostico/00-sumario-executivo.md): o problema, com dados e fontes.
- [Soluções](docs/solucoes/README.md): objetivos, catálogo de 33 opções, fichas de evidência, avaliação e pacotes.
- [Referências](docs/referencias/fontes.md): fontes, questões em aberto, registo de verificação e glossário.

## Ver como site

O site é gerado com o [Zensical](https://zensical.org/) a partir dos mesmos ficheiros Markdown. A configuração está em [`zensical.toml`](zensical.toml).

```sh
python3 -m venv .venv
.venv/bin/pip install zensical
.venv/bin/zensical serve      # pré-visualizar em http://localhost:8000
.venv/bin/zensical build      # gerar o site na pasta site/
```
