# Almoxarifado/SESMT

![image](https://github.com/user-attachments/assets/586b3a42-1c52-4a67-988d-74ec92188ae2)

## Requisição de materiais

![image](https://github.com/user-attachments/assets/6ed9429d-c8cf-4cd3-b12a-5925124d6617)

* Código: automático;
* Empresa/obra/estoque: selecionar o almoxarifado onde o material está disponível (de acordo com a entrada);
* Data saída: automática;
* Usuário: logado no sistema, automático;
* Status: automático de acordo com o caminhamento da requisição pelas áreas;
* Tipo movimentação: selecionar EPI ou EPC ou ferramenta (neste formulário não elabora saída para materiais elétricos);
* Tipo pedido: selecionar primeira entrega, troca ou devolução, sendo que:
   1. Primeira entrega: funcionário está solicitando o equipamento pela primeira vez;
   2. Troca: funcionário solicitou a troca de equipamento que já está com ele, o sistema pergunta  , ou seja, caso o funcionário não devolva o equipamento anterior o gestor poderá gerar um vale para ele e enviar ao RH. Obs.: para ver o vale gerado acesse menu: financeiro/vale funcionário/detalhado ou parcelas/consultar;
   3. Devolução: funcionário solicitou a devolução do equipamento que já está com ele, o sistema pergunta  , ou seja, caso o funcionário não devolva o equipamento anterior o gestor poderá gerar um vale para ele e enviar ao RH. Obs.: para ver o vale gerado acesse menu: financeiro/vale funcionário/detalhado ou parcelas/consultar;

## Vale Funcionário
![image](https://github.com/user-attachments/assets/b0a5de0f-ac3d-4568-9b55-200c879e1f3a)

* Recebedor/responsável: selecionar o funcionário que será atendido com a saída dos equipamentos;
* Código SAP: inserir o código ou consultar pelo nome do equipamento;
* Nome produto: selecione o nome do equipamento pelo início, meio ou fim;
* Estado: selecionar novo (equipamento novo) ou reaproveitado (troca de equipamento) ou aferição (devolução do equipamento);
* Estoque atual: o sistema vai mostrar se existe saldo no estoque para saída do equipamento, caso o saldo seja inferior ao solicitado o sistema não permitirá a saída do equipamento solicitado;
* Unidade: automático;
* Quantidade: inserir a quantidade solicitada (atentar-se ao saldo). Clicar em  para inserir o item no GRID. Caso seja necessário clicar em   para excluir a linha inserida no GRID. Clicar em salvar.
*Status da requisição: elaborado, aberto, separado, atendido, finalizado e cancelado!
* Botão salvar: salva o registro no bando de dados (não retira o equipamento do estoque);
* Botão consultar: consulta saídas já registradas no banco de dados;
* Novo: elabora nova saída de equipamento;
* Imprimir: imprime a requisição gerada para assinatura do responsável pela utilização;
* Aberta: segundo status da requisição de saída;
* Atendido: só será habilitado após clicar em aberto, somente o pessoal com permissão de almoxarifado poderá atender uma requisição;
* Finalizado: somente ficará habilitado após ser atendido a requisição, total ou parcial, somente o pessoal com permissão de almoxarifado poderá finalizar uma requisição;
* Cancelar: só pode cancelar uma requisição se não estiver finalizada e somente o responsável do almoxarifado, caso esteja no status de elaborado somente o usuário que gerou poderá cancelar.
* Imprimir: após atendida a requisição deverá ser impresso uma via do documento para assinatura dos responsáveis pela entrega e da utilização dos materiais;
