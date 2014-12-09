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
Gerente de Baselines: José Oliveira - Criar baselines.

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


| Item (ou Tipo de Item)                 | Responsável na equipe	     | Inclusão em Baseline |
|----------------------------------------|----------------------------|----------------------|
|Criação dos Casos de Uso                |José Oliveira               |Quando uma versão de Caso de Uso for criada ou alterada|
| Criação dos Casos de Teste             |Iuri Farias                 |Quando uma versão de caso de teste for criada ou alterada|
|Cronograma do Projeto                   |Iuri Farias                 |Quando houver alteração na data de entrega do projeto| 


### 3.1.3 Baselines do Projeto

Ciclo de vida do projeto deverá ser deifnido de acordo com o cronograma.
As baselines devem ser estabelecidas a cada ciclo de iteração em cada fase: Iniciação, Elaboração, Construção e Transição. Elas também podem ser geradas no final de iterações ocorridas dentro das várias fases ou com freqüência ainda maior definidas por José Oliveira.

### 3.1.4 Estrutura do Repositório de Versões
O projeto será dividido nas seguintes fases:
1- Criação
2- Levantamento de Requisitos
3- Desenvolvimento
4- Testes
5- Homologação
6- Implatação
7- Encerramento

3.2 Controle de Configuração e Mudança
--------------------------------------

### 3.2.1 Processamento e Aprovação de Solicitações de Mudança

O backup do repositório ser mantido e atualizado na view de desenvolvimeto. Os artefatos alterados durante a semana de trabalho serão salvos na view de integração de acordo com o fluxo de trabalho e ordens de serviços. Apenas o Gerente de configuração poderá subir os artefatos para a view de integração (produção).

### 3.2.2 Comitê de Controle de Mudança (CCB)

O comitê de Controle de Mudanças (CCM) será formado pelo Gerente de Configuração e  Gerente de Projetos.

Gerente de Configuração  –  José Oliveira
Gerente de Projeto – Iuri Farias


4. Padrões e Procedimentos
==========================
_[Descreva os padrões e procedimentos que devem ser seguidos no projeto. Crie subseções se achar necessário, para organizá-los melhor.]_



5. Treinamento e Recursos
=========================
_[Descreva as ferramentas de software, o pessoal e o treinamento necessários para implementar as atividades de CM especificadas.]_



6. Auditorias de Configuração
=============================
_[Descreva o cronograma das auditorias de configuração e o que será verificado. Informe também como serão reportados os problemas encontrados e onde sera feito o acompanhamento dos itens corretivos.]_
