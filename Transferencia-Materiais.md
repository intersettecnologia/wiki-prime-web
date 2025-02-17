# Transferencia de materiais

![image](https://github.com/user-attachments/assets/174a0152-1074-4bdb-a5a0-807928eef850)

É possivel transferir materiais de um centro de custo para outro nessa funcionalidade, funciona da seguinte forma:

* Código: automatico gerado pelo sistema
* Empresa saida: selecionar o centro de custo que vai sair os materiais.
* Empresa entrada: selecionar o centro de custo que vai receber os materiais.
* Data de criação: aumomatico
* Tipo movimentação: selecione um dos tipos (material eletrico, EPC, EPI, ferramentas ou  utilização empresa)
* Status: automatico
* Observação: campo facultativo caso seja necessario relatar alguma coisa.
* Novo produto: informe o código do material ou descrição (nº serie, CT, unidade e estoque atual são automaticos), informe a quantidade e clica em adicionar, repita esse processo para todos os materaias e clique em salvar.

## Consulta e status das transferencias

![image](https://github.com/user-attachments/assets/436ba29f-0ad4-4ef4-8f69-c8ee6e5b4945)

tela de consulta transferencias e status de cada etapa.

* Solicitado: usuário faz a solicitação de transferencia.
* Em aprovação: usuário que solicitou coloca neste status para submetar a aprovação do almoxarifado
* Em atendimento: almoxarifado recebe a solicitação e informa que está tratando a solicitação.
* Separado: almoxarifado verifica se possue os materiais solicitados e separa, tem a opção de não atender todo o solicitado por não possuir no estoque físico, separar somente os produtos e quantidades existentes.
* Atendido: pessoal do almoxarifado de destino pega os materiais para tranporto (em transito).
* Aguardando entrega: material está em transito e não foi recebido pelo centro de custo recebedor.
* Entregue: pessoal do centro de custo recebedor confere os materiais e recebe (caso esteja faltando algim material do que foi solicitado, ele recebe somente a quantidade conferida e recebida. o centro de custo que enviou os materiais recebe a transferencia de volta com observação das quantidades recebidas).
* Finalizado: o centro de custo de origem confere todas os itens e quantidades recebidas pelo centro de destino e finaliza, caso tenha quantidade ou material não recebido pela rigem, o mesmo abre uma auditoria para apurar o odorrido no transporte desses materiais.
* Cancelado: uma transferencia pode ser cancelada se estiver no status de solicitação.
