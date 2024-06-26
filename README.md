<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="static/img/logoW.pn" alt="Bot logo"></a>
</p>

<h3 align="center">Aplicação WEB: <i>KingFungi</i></h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![Platform](https://img.shields.io/badge/platform-reddit-orange.svg)](https://www.reddit.com/user/Wordbook_Bot)
[![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> 🤖 Bem vindos, amigos pesquisadores!!
    <br> 
</p>

## 📝 Sumário

- [Sobre ](#about)
- [Exemplo de fasta](#demo)
- [Sofwares](#working)
- [Configurações](#usage)
- [Instruções](#getting_started)
- [Execução](#deployment)
- [Autores](#authors)
- [Referências](#acknowledgement)

## 🧐 Sobre <a name = "about"></a>
O <strong> KingFungi</strong>   é uma Aplicação Web desenvolvida pelo discente e pesquisador Sr. Reinilson Bispo de Assis Souza, como requisito para a conclusão do curso de Bacharelado em Sistemas de Informação pela Universidade do Estado da Bahia. O <strong> KingFungi</strong> tem como objetivo analisar proteomas fúngicos a partir de arquivos .fasta e identificar proteínas transmembranares com capacidade de se ligar a íons metálicos.

## Exemplo de arquivo .fasta <a name = "demo"></a>

 <img width=1000px height=270px src="static/img/fasta.png" alt="Bot logo"></a>

## 💭 Sofwares  <a name = "working"></a>


**Software 1 :**

O DeepTMHMM é um algoritmo inovador baseado em aprendizado profundo e modelo de linguagem de proteínas, que oferece uma precisão sem precedentes na detecção e previsão da topologia de proteínas transmembranares, tanto hélices alfa quanto barris beta, em todos os domínios da vida.

**Disponível em:** https://dtu.biolib.com/DeepTMHMM





**Software 2 :** 

O MeBiPred (Metal Binding Predictor) é uma ferramenta computacional que utiliza aprendizado de máquina para prever o potencial de ligação de metais em proteínas.

**Disponível em:** https://pypi.org/project/mymetal/




Esses são utilizados para implementar um pipeline que funcionará na aplicação web.

##  Configurações <a name = "usage"></a>

O Kf foi desenvolvido utilizando Python 3.10.12 em um sistema operacional Ubuntu 22.04 64bits. Para o gerenciamento das requisições, utilizamos o Celery, que permite a execução assíncrona e escalável de tarefas em segundo plano. O RabbitMQ atua como sistema de mensagens, facilitando a comunicação eficiente e confiável entre os serviços e o Celery.

O arquivo <strong>requirements.txt</strong> possui todas as bibliotecas necessárias para a execução do KF, incluindo o Celery. Instale-as utilizando o comando abaixo:

```
pip install -r requirements.txt
```

The first part, i.e. "!dict" **is not** case sensitive.

The bot will then give you the Oxford Dictionary (or Urban Dictionary; if the word does not exist in the Oxford Dictionary) definition of the word as a comment reply.

### Example:

> !dict what is love

**Definition:**

Baby, dont hurt me~
Dont hurt me~ no more.

**Example:**

Dude1: Bruh, what is love?
Dude2: Baby, dont hurt me, dont hurt me- no more!
Dude1: dafuq?

**Source:** https://www.urbandictionary.com/define.php?term=what%20is%20love

---

<sup>Beep boop. I am a bot. If there are any issues, contact my [Master](https://www.reddit.com/message/compose/?to=PositivePlayer1&subject=/u/Wordbook_Bot)</sup>

<sup>Want to make a similar reddit bot? Check out: [GitHub](https://github.com/kylelobo/Reddit-Bot)</sup>

## 🏁 Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them.

```
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running.

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo.

## 🚀 Deploying your own bot <a name = "deployment"></a>

To see an example project on how to deploy your bot, please see my own configuration:

- **Heroku**: https://github.com/kylelobo/Reddit-Bot#deploying_the_bot

## ⛏️ Built Using <a name = "built_using"></a>

- [PRAW](https://praw.readthedocs.io/en/latest/) - Python Reddit API Wrapper
- [Heroku](https://www.heroku.com/) - SaaS hosting platform

## ✍️ Autor <a name = "authors"></a>

- [@rey4ssis](https://github.com/rey4ssis)- Rey Assis
- [@G2BC](https://github.com/G2BC/KingFungi) - Grupo de Pesquisa em Bioinformática e Biologia Computacional


## 🎉 Referências <a name = "acknowledgement"></a>

- **Artigo:** https://www.biorxiv.org/content/10.1101/2022.04.08.487609v1
- **Artigo:** https://academic.oup.com/bioinformatics/article/38/14/3532/6594112?login=false


