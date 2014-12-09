<Nome do Projeto>
=================
Plano de Gerenciamento de Configuração
======================================
Versão &lt;1.0&gt;
------------------

_[Observação: O template a seguir é fornecido para uso com o Rational Unified Process (RUP).  O texto exibido entre colchetes e em itálico foi incluído para orientar o autor e deve ser excluído antes da publicação do documento._

_Este documento utiliza a formatação da linguagem [Markdown] (http://daringfireball.net/projects/markdown/). Você pode encontrar um guia de referência rápido [aqui] (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).]_

Histórico de Versões
--------------------

|Data                |Versão       |Descrição               |Autor          |
|--------------------|-------------|------------------------|---------------|
|09/12/2014          |<1.0>        |Criação do Documento    |Iuri Farias    |
|_&lt;dd/mm/aaaa&gt;_|_&lt;1.1&gt;_|_&lt;Outra versão&gt;_  |_&lt;autor&gt;_|



1. Introdução
==============

O Plano de Gerenciamento de Configurações tem como objetivo principal controlar todas as mudanças realizadas ao longo do ciclo de vida do projeto, em todas as suas etapas.

1.1 Finalidade
---------------
Garantir confiabilidade, estabilidade e indentificar todas as alterações realizadas durante a execução do projeto.

1.2 Escopo
----------
A cada versão deve-se ter a identificação das alterações realizadas.

1.3 Definições, Acrônimos e Abreviações
---------------------------------------
GC - Gerência de COnfiguração

1.4 Referências
---------------
Pro Git (Chacon S. and Straub B.) - Second Edition - Apress

1.5 Visão Geral
---------------
O Plano de Gerenciamento de Configurações irá definir as responsabilidades do projeto bem como todas as nomenclaturas, estruturas, ambientes, processos e solicitações de mudanças inclusas.



2. Gerenciamento de Configuração de Software
============================================

2.1 Organização, Responsabilidades e Interfaces
------------------------------------------------
Gerente de Configuração: Iuri Farias - Estabelecer Políticas de GC; Escrever Plano de GC; Configurar ambiente de GC;
Gerente de Baselines: Neto Oliveira - Criar baselines.

2.2 Ferramentas, Ambiente e Infra-estrutura
-------------------------------------------
Ferramentas: 
Git - Controle de versão
SQL SERVER - Sistema Gerenciador de Banco de Dados
 

3. O Programa de Gerenciamento de Configuração
==============================================

3.1 Identificação da Configuração
---------------------------------
### 3.1.1 Métodos de Identificação
----------------------------------
Nomenclatura de criação de branches: Branch<NomeResponsável> ex: BranchJose, BranchMaria.
Nomenclatura de versionamento: ver_numVersão_DiaMesAno ex: ver_1.0_09122014

### 3.1.2 Itens de Configuração
_[Relacionar os artefatos ou grupos de artefatos, separando por tipo, modulo ou subsistema, responsável ou momento em que deverão ser incluídos em baselines._
* _“Inclusão em Baseline” em branco significa que o grupo de artefatos não participará de baseline. Pode ser expresso como uma data ou identificador de uma baseline, fase ou ponto de controle_
* _“Responsável”: indicar nominalmente, sempre que possível]_

| Item (ou Tipo de Item)                 | Responsável na equipe	     | Inclusão em Baseline |
|----------------------------------------|-----------------------------|----------------------|
|_&lt;grupo de itens de configuração&gt;_|_&lt;nome do responsável&gt;_|_&lt;momento a partir do qual o conjunto de artefatos será incluído em baseline&gt;_|


### 3.1.3 Baselines do Projeto

_[As baselines funcionam como um padrão oficial no qual os trabalhos subseqüentes são baseados. Somente mudanças autorizadas podem ser efetuadas nas baselines._
_Descreva em que pontos do ciclo de vida do projeto ou produto as baselines devem ser estabelecidas. As baselines mais comuns devem ser definidas ao final de cada uma das fases de Iniciação, Elaboração, Construção e Transição. Elas também podem ser geradas no final de iterações ocorridas dentro das várias fases ou com freqüência ainda maior._
_Descreva quem autoriza uma baseline e o que ela contém.]_

### 3.1.4 Estrutura do Repositório de Versões
_[Descreva a organização de diretórios do seu repositório e que itens/arquivos devem ser armazenados em cada diretório.]_

3.2 Controle de Configuração e Mudança
--------------------------------------

### 3.2.1 Processamento e Aprovação de Solicitações de Mudança
_[Descreva o processo pelo qual os problemas e as mudanças são submetidos, revisados e dispostos. Inclua como funciona a transição de estados de uma solicitação de mudança]_

### 3.2.2 Comitê de Controle de Mudança (CCB)
_[Descreva a participação e os procedimentos para processar solicitações e aprovações de mudança a serem seguidos pelo CCB. Informe quem são os membros do CCB e suas responsabilidades.]_



4. Padrões e Procedimentos
==========================
_[Descreva os padrões e procedimentos que devem ser seguidos no projeto. Crie subseções se achar necessário, para organizá-los melhor.]_



5. Treinamento e Recursos
=========================
_[Descreva as ferramentas de software, o pessoal e o treinamento necessários para implementar as atividades de CM especificadas.]_



6. Auditorias de Configuração
=============================
_[Descreva o cronograma das auditorias de configuração e o que será verificado. Informe também como serão reportados os problemas encontrados e onde sera feito o acompanhamento dos itens corretivos.]_
