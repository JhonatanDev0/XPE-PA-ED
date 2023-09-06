# Previsão de Retenção de Alunos - TCC de Engenharia de Dados

Este repositório contém o Trabalho de Conclusão de Curso (TCC) desenvolvido como parte do curso de Engenharia de Dados. O projeto tem como objetivo criar um modelo de previsão de retenção de alunos em instituições de ensino superior, utilizando técnicas de engenharia de dados e aprendizado de máquina.

## Descrição do Projeto

O problema de retenção de alunos é crítico para instituições de ensino, pois afeta diretamente o sucesso acadêmico e financeiro da instituição. Este TCC aborda o problema da seguinte maneira:

- Coleta de Dados: Descrevo o processo de coleta de dados, incluindo as fontes de dados utilizadas, os métodos de extração e o processo de limpeza e transformação dos dados.

- Análise Exploratória de Dados: Apresento uma análise detalhada dos dados, incluindo visualizações e estatísticas descritivas que nos ajudaram a compreender melhor o problema.

- Engenharia de Recursos: Discuto as etapas de engenharia de recursos utilizadas para criar características relevantes para o problema de previsão de retenção de alunos.

- Modelagem Preditiva: Descrevo os modelos de aprendizado de máquina utilizados, suas configurações e avaliações de desempenho. Incluímos também informações sobre como otimizamos esses modelos.

## Estrutura do Repositório

O repositório está estruturado da seguinte forma:

- `data/`: Contém os conjuntos de dados brutos e os conjuntos de dados processados após a etapa de engenharia de recursos.

- `notebooks/`: Inclui Jupyter Notebooks que detalham as etapas do projeto, desde a coleta de dados até a modelagem preditiva.

- `scripts/`: Qualquer código Python auxiliar utilizado no projeto, como scripts de pré-processamento de dados ou funções personalizadas.

- `docs/`: Documentação adicional, se necessário, como manuais de uso do código ou relatórios adicionais.

## Configuração do Ambiente

Se você deseja replicar os resultados deste projeto, siga as instruções para configurar seu ambiente:

1. Clone este repositório:

```bash
git clone https://github.com/jhonatanDev0/XPE-PA-ED.git
```

2. Crie um ambiente virtual (recomendado) e instale as dependências:

```bash
cd XPE-PA-ED
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate
pip install -r requirements.txt
```

3. Execute os notebooks Jupyter para seguir as etapas do projeto.

## Contribuições

Contribuições são bem-vindas! Se você deseja contribuir para este projeto, siga estas etapas:

1. Faça um fork deste repositório.

2. Clone o seu fork para o seu ambiente local:

```bash
git clone https://github.com/JhonatanDev0/XPE-PA-ED;git
```

3. Crie uma branch para suas alterações:

```bash
git checkout -b minha-feature
```

4. Faça suas alterações e faça commit delas:

```bash
git commit -m "Adicionando funcionalidade X"
```

5. Envie suas alterações para o seu fork:

```bash
git push origin minha-feature
```

7. Crie um pull request para este repositório original.

## Autores

- Jhonatan Oliveira (https://www.linkedin.com/in/jhonatandev/)

## Licença

Este projeto está licenciado sob a Licença MIT - consulte o arquivo LICENSE para obter detalhes.

## Agradecimentos

Agradeço a todos que contribuíram para este projeto e à XP Educação por apoiar nossa pesquisa.
