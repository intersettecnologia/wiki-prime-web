# Almoxarifado/Elétrico

![image](https://github.com/user-attachments/assets/86fe0513-21d7-4a28-b9ad-687b41289464)

![image](https://github.com/user-attachments/assets/efa28103-a8fa-4db6-bbc4-dbf6475becf9)

* Código: automático;
* Empresa/obra/estoque: selecionar o almoxarifado onde está disponível os materiais.
* Veículo: informar a equipe/veiculo que irá retirar os materiais do almoxarifado.
* Usuário e data: automático.
* Número projeto/ordem: informar o número do projeto/OSE que utilizará os materiais, os projetos devem estar cadastrados no menu construção/controle de obras/consulta.
* Tipo obra: selecionar o tipo da obra particular ou manutenção ou construção ou máquina blindada ou emergencial ou comercial.
* Responsável utilização: selecionar quem será o responsável pela retirada dos materiais no almoxarifado.
* Status: automático.
“Os status são: elaborado, aberto, separado, atendido, finalizado e cancelado”.
* Observação: este campo deve é facultativo o preenchimento.
* Código SAP: inserir o código ou consultar pelo nome do equipamento;
* Nome produto: selecione o nome do equipamento pelo início, meio ou fim;
* Estado: selecionar novo (equipamento novo) ou reaproveitado (troca de equipamento) ou aferição (devolução do equipamento);
* Estoque atual: o sistema vai mostrar se existe saldo no estoque para saída do equipamento, caso o saldo seja inferior ao solicitado o sistema não permitirá a saída do equipamento solicitado;
* Unidade: automático;
* Quantidade: inserir a quantidade solicitada (atentar-se ao saldo). Clicar em + para inserir o item no GRID. Caso seja necessário clicar em lixeira  para excluir a linha inserida no GRID. 
* Clicar em salvar.
* Status da requisição: elaborado, aberto, separado, atendido, finalizado e cancelado!
* Botão salvar: salva o registro no banco de dados (não retira os materiais do estoque);
* Botão consultar: consulta saídas já registradas no banco de dados;
* Novo: elabora nova saída de material;
* Imprimir: imprime a requisição gerada para assinatura do responsável pela utilização dos materiais;
* Aberta: segundo status da requisição de saída;
* Atendido: só será habilitado após clicar em aberto, somente o pessoal com permissão de almoxarifado poderá atender uma requisição;
* Separado: o almoxarifado recebe a requisição, separa e em seguida entrega para a equipe, depois aguarda o retorno da equipe, ajusta o que for necessário e finaliza a requisição.
* Finalizado: somente ficará habilitado após ser separado e atendido a requisição, total ou parcial, somente o pessoal com permissão de almoxarifado poderá finalizar uma requisição.
* Cancelar: só pode cancelar uma requisição se não estiver finalizada e somente o responsável do almoxarifado, caso esteja no status de elaborado somente o usuário que gerou poderá cancelar.
* Imprimir: após atendida a requisição deverá ser impresso uma via do documento para assinatura dos responsáveis pela entrega e da utilização dos materiais;

## Almoxarifado/eletrico/almoxarifado

![image](https://github.com/user-attachments/assets/9aca98e5-c2b7-46e9-98c6-4fab47e819e5)

* Consultar requisições abertas (requisição que o usuário elaborou e alterou o status para aberto), todas aparecerão nessa tela.
* O responsável pelo almoxarifado deverá clicar em   para abrir a requisição para analise e atendimento se for o caso, ou clicar em   para imprimir a requisição para assinatura dos responsáveis pela utilização.

![image](https://github.com/user-attachments/assets/d2dc089a-b3a5-47bf-ad5e-b0a42c5cccd7)

* O responsável pelo almoxarifado deve abrir a requisição e realizar os devidos tratamentos e separar os materiais. 
* Os materiais requisitados aparecerão no GRID, na coluna “solicitado” o responsável pelo almoxarifado vai confirmar as quantidades ou não, pode zerar as quantidades ou cancelar toda a requisição.
* Em caso de confirmação das quantidades solicitadas, clicar em “salvar” e depois em “separado”.

![image](https://github.com/user-attachments/assets/8ff33582-0aa2-4262-99ca-5f384ba38522)

Atendido

![image](https://github.com/user-attachments/assets/220a9522-c9c2-4961-a9d0-b4c6d56edb1b)

Finalizado

![image](https://github.com/user-attachments/assets/8da32b74-43c6-42e7-976a-7b057f09a6b5)

* Qtde serviço mobile: os materiais utilizados pelas equipes de campo são retornados para a requisição para comparar o que foi atendido com o utilizado, a deiferença deverá ser devolvida ao almoxarifado.
* Qtde não utilizada: é a diferença entre o atendido com o utilizado no mobile, se positivo a equipe tem de devolver para o almoxarifado.
* Retorno ao estoque: a qtede não utilizada é devolvida para o estoque ao clicar em finalizar a requisição.

Requisição impressa para assinatura do responsavel pela equipe

![image](https://github.com/user-attachments/assets/868849b4-ea01-4d3c-bd94-b9fe06147403)

![image](https://github.com/user-attachments/assets/2e583d6a-1f58-4551-8078-a08b21555c36)

* ABA anexo: pode ser inserido todos os documento relativos a saida dos materiais, inclusive a requisição assinada.
* Serviço mobile: todos os materiais utilizados pela equipe em campo são visualizados nessa ABA vinculado ou tipo de documento e localização da execução.
