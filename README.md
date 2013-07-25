PDM-Documetation
================

Sistema de Ponto Digital
========================
Atualizado: 25/07/2013

Dados:
======

Sistema de planilha manual (google) - passivel a falha;
A planilha atual tem um campo que mostra as atualizações - alterações e quem as fez;

Planilha foi criada para marcar a presença dos membros na sede no devido horário alocado e suas atividades desempenhadas no
mesmo periodo.
Planilha de controle de horario apresentada semanalmente, baseada no horário disponível de cada membro. Elaborada de tal
forma a fim que os membros tenho um contato estratégico.
Importante ressaltar que toda e qualquer alteração é observada por quem faz o controle. (Preenchimento incompleto ou falta
dele).

Existe uma flexibilidade no seu preenchimento, sendo possivel o mesmo ser realizado ate as 23:59 do mesmo dia. As faltas 
podem ser justificadas em até 24 horas.

Requisitos necessários:
=======================

Relatorios estatísticos.
Avisos sobre faltas, atrasos (requisitado).
Ser prático. (Essencial)
Armazenamento de dados dos membros. (histórico)
Gerenciamento das informações será feito pela Diretoria de Gestão de Pessoas. 
Possibilidade de justificar faltas em até 24 horas. Após esse prazo, sistema "fecha".

Controle Horario - entrada e saida controlada pelo sistema ( não permitir preenchimento antes e depois).
(Esse ultimo está passivel a alteração).

1. Problemática
===============

Existe um sistema de ponto manual implantado, onde os membros preenchem seus horarios e suas atividades desempenhadas em
uma planilha do google. Este controle é gerenciado por duas pessoas (Diretora e consultora da GP), onde estas monitoram o
preenchimento indevido ou a falta dele. Elas são auxiliadas pela própria ferramenta web, está por sua vez responsável pelo
registro de hora, do usuário e do campo onde as alterações foram realizadas. Foi estabelecido que o preenchimento pode ser
realizado ate as 23:59 do dia corrente, passando desse prazo, seria registrado a falta. Considera-se também outras situa
ções que envolvem a falta de preenchimento:

- Causa justa: é registrado a falta, porém justificado posteriormente (48 horas).
- Troca de horário (*)

A planilha foi construida a partir de uma outra planilha, esta contendo dados preenchidos pelos próprios membros informan
do sua disponibilidade de tempo (os horários de suas atividades). A sua elaboração é pensada de tal forma que os membros
tenham contato com outros estrategicamente (Diretores, Analistas, Gerentes, Consultores).

2. Requisitos da Disciplina:
===========================

- Layout totalmente personalizado;
- Utilizar persistência em banco de dados;
- Aplicativo internacionalizado	em Inglês e Português;
- O aplicativo deve ter uma tela de Splash;
- Utilizar duas ou mais	das seguintes tecnologias:
	- GPS *
	- Bluetooth
	- Maps *
	- WI-FI *
	- Manipulação	de	Áudio	ou	Vídeo;
	- Integração	com	Facebook	ou	Twitter;

(* Possíveis tecnologias que serão usadas)

3. Proposta:
===========

Inicial: criar um aplicativo de assinatura de ponto, onde este só aplicará a assinatura se as coordenadas do GPS estiverem
indicando o local da Unisigma. Um banco seria consultado e se integraria ao aplicativo.
[To elaborando ainda rsrs aberto a sugestões]

4. Objetivos:
============

Gerais
------

- Informatizar o processo de ponto de modo a trazer conforto e agilidade para os usuários.
- Maior controle e segurança, proporcionando mais consistencia aos dados.

Específicos
-----------

- Substituir o serviço web por um próprio da unisigma.
- Aplicação de disciplina na "assinatura" do sistema de ponto.
- Facilidade na obtenção de estatisticas e relatórios.
- Registro de membros.
- 
 
5. Metas:
========
(Onde o projeto pretende chegar)

- Elaboração de um banco de dados para armazenamento dos dados de cada membro.
- Controle de presença e de suas atividades na sede.
- Emissão de relatórios e estatísticas de cada membro.

6. Requisitos do Projeto:
=========================

- Controle da assinatura do ponto, recolhendo hora do servidor.
- Registro do ponto e das faltas em um banco de dados.
- Visualização das estatísticas dos membros.

