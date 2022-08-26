 [![Badge ServeRest](https://img.shields.io/badge/API-ServeRest-green)](https://github.com/ServeRest/ServeRest/)
 
# Teste de Performace da API ServeRest com JMeter

## Script de teste para obter métricas e indicadores sobre a performace da API com a condição de 5 usuários virtuais simultâneos realizar requisição à API durante um período de 5 minutos. Além disso, é possível o acesso a análise técnica do teste de performace da autora.

### Tabela de conteúdos 

<!--ts-->
* [Sobre](#Sobre)
* [Tabela de Conteudo](#tabela-de-conteudo)
* [Como usar](#como-usar)
    * [Pre Requisitos](#pre-requisitos)
    * [Passo a passo](#passo-a-passo)
* [Tecnologias](#tecnologias)
* [Autor](#autor)
* [Licença](#licença)
<!--te-->

### Como usar
#### Pre Requisitos:
* Para realizar o teste de performance, é preciso ter instalado o JMeter;
* Ter instalado o Docker e executar o seguinte comando no terminal: docker run -p 3000:3000 paulogoncalvesbh/serverest:latest ;
* Realizar o download do arquivo .jmx contido nesse repositório: https://github.com/anaizaalencar/Teste-de-Performace-ServeRest/blob/main/ReportServeSrest.jmx. 

#### Passo a passo:
* Com o JMeter instalado, a ferramenta deve ser executada. Ao abrir a ferramenta, é preciso seguir os seguintes passos para abrir e executar o script:
  * Clicar em Arquivo;
  * Clicar em Abrir;
  * Selecionar o arquivo que contém o projeto baixado;
  * Clicar em Abrir;
  * Clicar em Iniciar.
* Após iniciar, é preciso aguardar um período de 5 minutos até que o teste finalize e assim, conseguir observar as variáveis de resposta.

Para mais informação sobre a API ServeRest consultar o site https://serverest.dev/. 

### Tecnologias 
* JMeter
* Docker

### Autor
<a href="https://linkedin.com/in/ana-iza-alencar-b5a33b123">
 <sub><b>Ana Iza Alencar</b></sub></a> <a href="https://linkedin.com/in/ana-iza-alencar-b5a33b123" title="Rocketseat">🚀</a>
 <br />

### Licença
Este projeto esta sobe a licença <"Licença">
