# 100 Dias de Código - Log

### Dia 0: 02 de Janeiro de 2018

**Progresso(s) do Dia:** Preparei o ambiente e as ferramentas para utilização
durante o desafio. Blog em português (Pelican/Python), blog em inglês 
(Medium), repositórios de acompanhamento e da aplicação e um quadro de 
acompanhamento no Trello.

**Reflexões:** Além do desafio de codificar durante 100 dias, com um objetivo 
definido, acredito relevante aliar ao desafio de manter blogs, em português e 
inglês, onde posso praticar outras habilidades.

Os blogs foram criados e inaugurados com postagens sobre o desafio, mas se 
propõem a continuar depois dessa primeira rodada com artigos pessoais, 
traduções, e possíveis rodadas subsequentes do #100DaysOfCode.

**Link(s):** 
1. [Blog (versão em português)](https://hilam.github.io)
2. [Blog (versão em inglês)](https://medium.com/itfacets)
3. [Repositório de acompanhamento do desafio](https://github.com/hilam/100-days-of-code)
3. [Repositório do aplicativo](https://github.com/hilam/armazem)
5. [Quadro no Trello](https://trello.com/b/zKO1ooa0/100daysofcode)

### Dia 1: 03 de Janeiro de 2018

**Progresso(s) do Dia:** Primeiro commit no repositório da aplicação.

**Reflexões:** Comecei a leitura de alguns livros sobre assuntos relacionados
 ao aplicativo:
 
* Flask by example
* Learning Flask framework
* Flash framework cookbook
* Github Essentials

A partir dos capítulos iniciais de cada um deles e do tutorial novo de Flask 
do Full Stack Python, codifiquei bem mais que uma hora, mas ficou um bom 
boilerplate inicial, eu espero.

**Link(s):** 
1. [Primeiro commit](https://github.com/hilam/armazem/commit/454cc003a1fe2819300650eaa8c9c9ad68d4f4f8)

### Dia 2: 04 de Janeiro de 2018

**Progresso(s) do Dia:** Contratei um Cloud Server no Host1Plus, onde já 
tinha um domínio. Primeiras configurações do servidor Ubuntu 16.04.3, que 
será a plataforma de produção. Instalação do git e do nginx.

**Reflexões:** É relativamente simples adquirir um cloud server a um bom 
preço. Basta que você tenha um cartão de crédito internacional. No Brasil, os
 preços continuam proibitivos. Não postei no Twitter nem no Github.

**Link(s):** 

### Dia 3: 05 de Janeiro de 2018

**Progresso(s) do Dia:** 

* Continuação das leituras;
* Definição de codificar no Windows, utilizando PyCharm Community como IDE;
* Conclusão do treinamento que comecei antes do desafio: Git e Github para 
iniciantes <https://www.udemy.com/git-e-github-para-iniciantes>; 
* Continuação dos estudos do curso "Python para Data Science e Machine 
Learning" <https://www.udemy.com/python-para-data-science-e-machine-learning>; 
* Me registrei e iniciei assistindo aulas do curso de "Probabilidade e 
Estatítica" <https://veduca.org/courses/enrolled/140140>;

**Reflexões:** Não postei no Twitter, nem commitei a tempo no Github.

**Link(s):** 

### Dia 4: 06 de Janeiro de 2018

**Progresso(s) do Dia:** 
* Atualizei o Docker Toolbox para Windows
* Criei uma máquina virtual Ubuntu Server 16.04.3, local, para homologar 
builds e mudanças no servidor da nuvem

**Reflexões:** O plano vai se formando: codificar no Windows, com o PyCharm 
Community, num ambiente virtual criado com Anaconda e Python 3.6; utilizar 
containers Docker (ainda não decidi qual SO do container do aplicativo: 
Alpine ou Ubuntu?); containers para bancos de dados, testes e homologação 
(servidor local); criar mecanismo de espelhamento de configurações do servidor 
local para o servidor remoto; criar mecanismo de deploy automatizado para a  
produção (servidor remoto); questionamento: devo usar uma distribuição Python 
ou Conda nos servidores? Miniconda resolve? A ser testado. Para a versão 1.0 
está tudo praticamente definido no documento de características do aplicativo.

**Link(s):** 

### Dia 5: 08 de Janeiro de 2018

**Progresso(s) do Dia:** Continuei as leituras; codifiquei o modelo de 
dados primário daaplicação, utilizando SQAlchemy. Definições: banco de dados 
de desenvolvimento será SQLite. o de produção será PostgreSQL.

**Reflexões:** SQLAlchemy me pareceu bastante burocrático.

**Link(s):** 
<https://github.com/hilam/armazem/commit
/153968e6f72f4d4524fb19ab87a1e064bf82f6a2>

### Dia 6: 09 de Janeiro de 2018

**Progresso(s) do Dia:** Continuei as leituras, incluindo na lista o livro "BDD
 in Action"; primeira aula do curso "M101P: MongoDB for Developers", no site
  da [University MongoDB](https://university.mongodb.com/). Dúvida: a 
característica do aplicativo se beneficiaria com banco de dados 
não-relacional (NoSQL)?

**Reflexões:** Talvez o aplicativo se beneficie ao usar banco de dados 
não-relacional

### Dia 7: 10 de Janeiro de 2018

**Progresso(s) do Dia:** Continuação das leituras; pesquisa sobre BDD + 
Python, então eu encontrei behave, pytest-bdd e pytest-flask. Eu usarei no 
projeto do meu aplicativo. Definição: usarei NoSQL MongoDB com pymongo; vou 
descrever o aplicativo usando a técnica BDD.

**Reflexões:** 

