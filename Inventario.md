# Almoxarifado/Inventario

![image](https://github.com/user-attachments/assets/b0807a8d-6d3c-45ce-9e59-7343a5fb176b)

![image](https://github.com/user-attachments/assets/f4b742f0-dffe-40e8-9d29-de6312428062)

## Criar inventário

* Código: automático pelo sistema
* Empresa/centro de custo: seleciona um centro de custo no qual será inventariado.
* Data invetário: Informe a data do inventário.
* Status: automatico
* tipo movimentação: selecione o tipo de movimentação, pode ser (material eletrico, EPC, EPI, ferramenta/eletronico ou utilização empresa).
* Responsável: selecione o responsável pelo inventário.
* Responsável contagem: Selecione quem serão os responsáveis pela contagem dos produtos, este campo é obrigatório.
* Observação geral: este campo é facultativo, serve para colocar alguma informação sobre o inventário.
* Clicar em salvar
* Inserir matrial/produto: informe o cód. SAP ou descrição, o sistema buscará nº de seria, CT e unidade, clicar em adicionar.
Adicionar todos os produtos: no sistema existe a possibilidade de buscar todos os produtos do centro selecionado, desde que possua entradas no estoque. O sistema vai mostrar todos os produtos na grid mesmo com saldo zero.

![image](https://github.com/user-attachments/assets/716ab28a-c70a-47e1-aa88-82860988b39b)

os produtos podem ser editados ou excluidos da grid depos de inseridos, somente se o status ainda estiver como solicitação.

* Clicar no botão solicitação para em aprovação.

Tela de consulta inventários em todos os status, são eles: elaboração, aberto, justificativa, finalizado e cancelado.

* Elaboração: mostra todos os inventarios solicitados no sistema.
* Aberto: neste status o solicitante não pode mais editar o invetario para alterações, é enviado para o almoxarifado para tratamento.
* Justificativa: o almoxarifado confere a contagem e preenche a tela de qtd contado.
* Finalizado: após inserir as quantidades contadas o almoxarifado finaliza o invetário, o sistema atualiza todo o estoque do centro inventariado.
* Cancelado: caso seja necessário o almoxarifado pode cancelar um solicitação de invetário. Somente o almoxarifado pode fazer esse cancelamento
* Exportar para Excel: o almoxarifado pode exportar a solicitação com os produtos para o Excel e preencher as colunas de quantidade contada e justificativa (essa por sua vez só é obrigatório se a contagem estiver divergente da quantidade do estoque atual).

![image](https://github.com/user-attachments/assets/0f8f4e16-a5a4-4115-a8ed-c4dcea5e7b9b)

* Importar Excel: após exportar para o excel e preencher os campos solicitados, o usuário salva a planilha e faz importação para o sistema (tela acima).
* Clicar no botão aberto para finalizado, o sistema atualiza todo op estoque do centro inventariado.
* Status: os status são automaticos de acordo com cada etapa alterada.
* Anexos: os usuário podem inserir anexos relativos ao inventario realizado para o centro.
