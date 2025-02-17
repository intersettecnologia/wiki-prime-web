# Construção/controle de obras
![image](https://github.com/user-attachments/assets/7f1e40c8-bb3d-4f03-9994-ada3b1bf374c)

![image](https://github.com/user-attachments/assets/a6755dd6-7368-4af3-9680-4f4b4793112b)

* Código: automático pelo sistema
* Empresa: selecione a parceira contratada (esta deve estar cadastrada no sistema)
* Cliente: selecione a contratante para quual o serviço será prestado (esta deve estar cadastrada no sistema)
* Data cadastro: automatica pelo sistema
* Funcionario: automatico pelo sistema (usuário logado)
* Contrato: selecione o contrato (esta deve estar cadastrada no sistema)
* Tipo contrato: automatico, busca do contrato informado anteriormente
* Status: automatico, se altera de acordo com as etapas do projeto
* Tipo obra: selecionar um dos tipos disponíveis (comercial, construção, emergencia COI, esgotamento, estrutural, manutenção, medição blindada, particular, poço grande, regulador de tensão, regulares, regularização de gambiarras, robustecimento, trifaseamento ou universalização).
* Ativo: deixar marcado para o projeto aparecer no sistema, caso desmarque o projeto não será visualizado por nenhum uruário, porem continuará no banco de dados.
* Projeto: informar o numero do projeto/obra (Proj+ ou OSE).
* Ordem ODI: informe o numero da ordem ODI - investimento (ordem oriunda do SAP), utilizada para instalçaão de materiais que define UC - unidadde de cadastro de acordo com o MCPSE e MCSE da Aneel. 
* Ordem ODD: informe o numero da ordem ODD - ordem de desativação (ordem oriunda do SAP), utilizada para retirada de materiais que define UC - unidadde de cadastro de acordo com o MCPSE e MCSE da Aneel.
* Ordem ODS: caso exista informar
* Cidade: informar a cidade onde será executado o projeto (esta deve estar cadastrada no sistema).
* Fator territótio: busca do cadastro da cidade, automatico.
* Bairro: informar o bairro da cidade onde será executado o projeto (esta deve estar cadastrada no sistema)
* Prioridade: informar a prioridade, elas podem ser ( P0-urgente, P1-muito alto, P2-alto, P3-moderada, P4- baixo ou P5-muito baixo).
* Título: informe o tutulo da obra/projeto, estes podem ser (extensão de rede média tensão MT, extensão de rede baixa tensão BT, deslocamento de rede ou poste, complementação de rede, melhoria de rede, doação de materiais e serviços, iluminação, manutenção de emergencia, manutenção preventiva RDU/RDR, ordem de desativação ODD, ordem de manutenção ODM (despesa), ordem de serviço ODS, subestação em tensão ate 34,5 kV, transferencia de materiais e serviços, serviços comerciais medidores, serviços comercias cabos, elaboração de projeto, aprovação de projeto do grupo A e empreendimentos de muiltiplas UCs).
* Endereço: digite o endereço da obra/serviço.
* Setor solicitante: informe o setor/departamento responsável pela obra/projeto.
* Coordenador: informe o coordenador da obra/projeto (esta deve estar cadastrada no sistema).
* Fiscal: informe o fiscal responsável da obra/projeto (esta deve estar cadastrada no sistema).
* Supervisor: informe o supervisor responsavel da obra/projeto (esta deve estar cadastrada no sistema). 
* Interessado: informe o interessado pela obra/projeto.
* Clicar na ABA controle obra: informar o controle obra, pode ser (viável, inviável, etc... ou o numero da ETR caso exista).
* Data recebimento: informe a data que o projeto foi recebeido para analise de viabilidade técniva.
* Data vencimento: informar qual o prazo para executar a obra/projeto.
* Observação: campo facultativo, caso haja alguma informação relevante sobre o obra/projeto.
* Clicar no + para inserir a informação na grid, o sistema vai contar os dias a vencer a execução do projeto.
* Clicar no botão salvar.

![image](https://github.com/user-attachments/assets/7eeaca91-5a7c-4338-8990-7d7018fef80e)

ABA status:

![image](https://github.com/user-attachments/assets/0496d650-6ad9-45a1-a5b9-76413d0c1ea2)

Nessa aba é possível movimentar o projeto para que depois possamos medir o tempo de execução da obra/projeto atraves de BIs, os status são:

* Planejamento: obra recebida da concessionária para visita de pre execução para ver a viabilidadde da obra. 
* Viabilizado: obra visitada e viabilizada para execução, preparar a programação.
* Em execução: projeto visilizado e pronto para fazer as programações de execução.
* Executado: projeto programado e executado totalmente.
* Pendente de asbuilt: executado em campo, porem não asbuiltada pelo supervisor no sistema Proj+ ou CAD.
* Pedente de consumo material: obra executada, porem a concessionária não fez as requisições para consimir os materiais nas ordens.
* Consumo realizado: as requisições foram feitas e os materiais foram consumidos nas ordens.
* Acertado: obra/projeto foi acertado com a concessionaria/parceira e pode seguir para faturamento.
* Encerrado: projeto acertado os materiais e serviços, pode ser encerrado.
* Cancelado: o projeto pode ser cancelado caso tenha viabilidade para execução.
* Acesso impedido: projeto não pode ser executado por possuir algum impedimento técnico, ambiental ou juridico.
* Aguardando material: não possui material no estoque e tem de esperar chegar.
* Clicar em + para inserir cada etapa do status, pode ser inserido observação caso necessário.


ABA orçamento:

![image](https://github.com/user-attachments/assets/79be33de-4af4-4c60-81af-d89edc5cd634)

Nesta aba é possível realizar o orçamento da obra/projeto utilizando importação de planilhas, xml ou integração com outros sistemas, vejamos a seguir.

Upload orçamento

* Upload do xml OSE do G2M MAN: (sistema que utiliza PTP para manutenções preventivas), este sistema gera xml e envia para as parceiras para execução de manutenções preventivas na rede elétrica, este xml pode ser importado para o prime erp e separando materiais de serviços ODI e ODD caso exista.
* Upload xls Excel do G2M Proj+: (sistema utilizado para elaboração de projetos elétricos de investimento na tensão ate 34,5 kV), depois de elabora o projeto desenho é possível exportar planilha execel para importar no prime. O sistema está pronto para ser integrado ao Proj+ para ganhar mais agilidade ao processo.
* Upload xml do BD G2M Proj+: (sistema utilizado para elaboração de projetos elétricos de investimento na tensão ate 34,5 kV), depois de elaborado o projeto desenho é possível buscar o xml da pasta do projeto e importar para o prime. O sistema está pronto para ser integrado ao Proj+ para ganhar mais agilidade ao processo. 

Tela de busca no Windows do xml do projeto

![image](https://github.com/user-attachments/assets/28ef0d16-00c5-4d22-90ed-3a970e067483)

Tela do prime/orçamento de UPs depois de importado o xml

![image](https://github.com/user-attachments/assets/93f06e76-c906-44c0-91fa-cc7f72f2c9b7)

Tela do prime/materiais orçados depois de importado o xml
![image](https://github.com/user-attachments/assets/cac41750-3dee-4f8f-ad23-ca710190e495)

Tela do prime/serviços orçados depois de importado o xml
![image](https://github.com/user-attachments/assets/14be3ac8-c346-4f5b-a136-5ad1c5c388a2)

Sistema PROJ+ Offline

![image](https://github.com/user-attachments/assets/27d3f3f3-cd3e-49e5-956e-880c1b141390)

Sistema utilizado para elaboração de projeto de rede de distribuição de enercia elétrica na tensão ate 34,5kV, deste sistema é gerado atraves de integração os orçamentos de ODI e ODD para posterior aprovação, execução, fiscalização e imobilização dos projetos/obras.

Tela do prime/Asbuilt depois de executado o projeto e importado o xml

![image](https://github.com/user-attachments/assets/1571d899-9e24-451a-b45f-ab07aba0419f)

Tela do prime/Asbuilt materiais depois de executado o projeto e importado o xml

![image](https://github.com/user-attachments/assets/cac63022-e560-4705-8c6e-f3f49cdd1658)

Tela do prime/Asbuilt serviços depois de executado o projeto e importado o xml

![image](https://github.com/user-attachments/assets/f9090591-e71d-48d0-b1f2-2c8e02c33e4b)

Tela do prime/Asbuilt acerto depois de executado o projeto e importado o xml

![image](https://github.com/user-attachments/assets/43b37d2e-d23c-4388-b595-76c0775e066b)

Neste tela possui um resumo separando os valores de ODI - investimento, ODD - desativação e ODM - despesa (caso exista no asbuilt), alem do valor total de serviço a ser faturado/imobilizado nas ordens. Essa tela não é editável, ela é preenchida com o resultado das abas anteriores. Os dados de faturamento devem ser digitados em caso das parceiras que prestam serviços para as concessionárias, deve ser preenchida pela área de faturamento.

* Data faturamento: Informar a data que foi realizado o faturamento.
* Contrato: informar o contrato que foi realizado o faturamento.
* Tipo de ordem: selecionar a ordem que foi faturado.
* Valor faturado: informar o valor faturado (total ou parcial por ordem).
* Vencimento processo: informar a data de vencimento da NF faturada.
* Clicar em + para inserir as informações na grid e depois salvar.

ABA para anexar documento

![image](https://github.com/user-attachments/assets/44aa551a-b6ef-4e2e-828a-52e104285003)

Neste aba é possível anexar qualquer tipo de documento relativo a obra/projeto (PDF, Word, Excel, PNG, JPEG, etc...).

ABA para carregar as fotos do relatório de fiscalização de campo

![image](https://github.com/user-attachments/assets/93486d93-57f9-49a5-af44-b445945b6a07)

Nesta aba ficam as fotos enviadas pelo App mobile da fiscalização de campo, as fotos vem vinculadas por ponto/localização geografica e podem ser utilizadas para auditorias ou refiscalização in loco.

ABA para deixar observações

![image](https://github.com/user-attachments/assets/7ee67e82-aa24-4d38-9161-5de72faab358)

Neste aba pode ser inseridas observações relativas a obra/projeto.

Após finalizar todos o processo da obra/projeto, tais como: asbuilt, acerto de materiais, faturamento e atualização da base geografica GIS, o mesmo deverá ter seu status alterado para encerrado, desta forma todos os dados do projeto ficarão somente para leitura, não podendo mais fazer nenhuma edição. Somente o Adm do sistema poderá retorno o status de encerrado para executado caso seja necessário, o sistema vai gravar uma autidoria para mostrar quais alterações foram feitas, tendo em vista que a base geografica já foi atualizada.

## Botões do sistema

![image](https://github.com/user-attachments/assets/7fb478b8-2556-47ce-82e2-1748ba1ddb8a)

* Salvar: qualquer inserção ou alteração que algum dado deve ser salvo neste botão.
* Diponibilizado mobile: envia o projeto para o vistoriador pré execução para registrar a viabilidade de execução do projeto (enviar para o supervisor cadastrado na obra/projeto).
* Consultar: realizar consultas de projetos no sistema, existem varios filtros que podem ser selecionados antes da consulta.
* Novo: cadastrar novos projetos no sistema.
