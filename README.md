**Phantom Apresenta:** Projeto Integrador, Fatec Prof. Jessen Vidal - 2022. 5° Semestre <br>
**Cliente:** <a href="https://www.midall.com.br//">MidAll</a>

<br><p align="center">
 <a href="https://www.midall.com.br/"><img src="https://cdn.discordapp.com/attachments/887890002741170176/10864manu42721377517698/download-removebg-preview.png"/></a>
</p>

<p align="center"> 
 <img src="https://img.shields.io/badge/Status%3A-Building-orange"/>
 <a href="https://www.java.com/pt-BR/"><img src="https://img.shields.io/badge/Language%3A-JAVA-red"/></a>
 <a href="https://vuejs.org/"><img src="https://img.shields.io/badge/Language%3A-VUE.js-green"/></a>
 <a href="https://www.midall.com.br/"><img src="https://img.shields.io/badge/Client%3A-MidAll-purple"/></a>
 <a href="http://fatecsjc-prd.azurewebsites.net/"><img src="https://img.shields.io/badge/Institution%3A-Fatec-red"/></a>
</p>

<p align="center">
 <a href="#executando-o-programa">Executando o Programa</a> |  <a href="#tecnologias-utilizadas">Tecnologias</a> |  <a href="#cronograma">Cronograma</a> 
 |  <a href="#equipe-phantom">Equipe</a>
</p>

<h3 align="center">Problema</h3>
<p align="justify">
Automatizar a jornada de download dos arquivos, armazenados em uma plataforma de vídeos,
realizando essa transferência para cloud, através do desenvolvimento de uma aplicação como
serviço, tendo como funcionalidade com o usuário somente um menu de configuração, que terão
os parâmetros necessários para que o serviço de download processe automaticamente, gerando
alertas caso ocorra erro no processamento. Salvar os metadados dos arquivos, para construção de
um dashboard para acompanhamento da execução do serviço e posterior análise de resultados e
indicadores (ex: quantidade de arquivos transferidos, quantidade de bytes transferidos, tempo de
transferência e etc).
</p>


<br>

## Tabela de Conteúdos

 - [O Projeto](#subiter-call)
 - [Tecnologias](#tecnologias-utilizadas)
 - [Requisitos](#requisitos)
 - [Product Backlog](#product-backlog)  
 - [Execução do Programa](#executando-o-programa)
 - [Cronograma](#cronograma)
 - [Equipe](#equipe-phantom)

<br>

## Tecnologias Utilizadas

<p align="center">
  <img src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D"/>
  <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=gold"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white"/>

  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"/>
  <img src="https://img.shields.io/badge/maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white"/>
  <img src="https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white"/>
</p>
 
<br>

## Requisitos

### 📌 Requisitos Funcionais

#### Aplicação 1:

 - Construir uma aplicação que rodará servidor local para configuração e parametrização do serviço.
 - Nessa aplicação, criar tela para configuração do sistema (com todas as configurações que a aplicação atual já tem) incluindo também a limitação de consumo de banda de rede e tempo para verificação de novos arquivos para download
 - Criar também, tela para configuração da conta de acesso a api (guardar de um jeito seguro).
 - Emitir alerta no S.O. avisando que novos arquivos foram baixados
 - Criar tela de histórico de arquivos baixados

#### Aplicação 2:

 - Construir uma API que será o serviço que buscará os arquivos que devem ser enviados para Cloud
 - Conectar com a api de arquivos (utilizar outro fornecedor, diferente do usado no requisito anterior. Pode ser Google Drive, AWS S3, Dropbox e etc.)
 - Realizar o download dos arquivos, seguindo as configurações realizadas na aplicação 1.
 - Criar dashboard para acompanhamento das execuções (pode ser construído em alguma ferramenta de BI, movendo os dados do banco locar para outro)

### 📌 Requisitos Não Funcionais

#### Aplicação 1:

 - Criar mecanismo de autenticação com a aplicação 2, hospedada na nuvem (para não aceitar requisição de locais não autorizados)

<br>

## Product Backlog

<p align="center"> 
<img src="https://user-images.githubusercontent.com/80851038/190932627-dec3b2eb-fcb7-486d-a563-6096a2e1e7ec.png" width="300"/> <br>
| <a href="https://apisubiter.atlassian.net/jira/software/projects/MID/boards/2/backlog">Product Backlog </a> |
</p>
 
<br>

## Executando o programa 
Acesse o passo a passo de como executar o programa clicando [AQUI](https://github.com/PhatomFatec/datatransfer-back/blob/8cf60c91e62dfdb093f0172d0c382152d15f3e91/Readme.md).

<br>

## Cronograma

| Eventos         | Início   | Fim      | Status |
|-----------------|----------|----------|--------|
| **Kick off**    | 13/02/23 | 03/03/23 |   ✔️ Realizado      |
| **Sprint 01**   | 13/03/23 | 02/04/23 |   ⚙ Em progresso       |
| **Sprint 02**   | 03/04/23 | 23/04/23 |   ❌ Realizado      |
| **Sprint 03**   | 24/04/23 | 14/05/23 |   ❌ Realizado      |
| **Sprint 04**   | 15/05/23 | 04/06/23 |   ❌ Realizado      |
| **Apresentação final + Feira de Soluções** | 13/06/23 | 14/06/23 |   ❌ Realizado  |

<br>

## Equipe Phantom

* **DEV** - Marcus Rocha &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;&nbsp;
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white&color=black"/>](https://www.linkedin.com/in/mvarocha/)
[<img src="https://img.shields.io/badge/github%20-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white&color=black"/>](https://github.com/mvarocha)


* **DEV** - Igor Ribeiro Silva &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; 
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white&color=black"/>](https://www.linkedin.com/in/igor-ribeiro-8571a6210/)
[<img src="https://img.shields.io/badge/github%20-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white&color=black"/>](https://github.com/IgorRibeiro-S)

* **MASTER** - Lucas Guiraldelli da Silva &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white&color=black"/>](https://www.linkedin.com/in/lucasguiraldelli/)
[<img src="https://img.shields.io/badge/github%20-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white&color=black"/>](https://github.com/LucasGuiraldelli)

* **PO** - Lara Oliveira Leal &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white&color=black"/>](https://www.linkedin.com/in/lara-leal-527b7020a/)
[<img src="https://img.shields.io/badge/github%20-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white&color=black"/>](https://github.com/lara-leal)
