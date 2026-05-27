          # requisitos funcionais 
RF01 – Cadastro de produtos
O sistema deve permitir cadastrar produtos com código, descrição, unidade de medida, categoria, fornecedor e estoque mínimo.

RF02 – Entrada de materiais
O sistema deve registrar entradas de itens no estoque com data, quantidade, fornecedor e documento de origem.

RF03 – Saída de materiais
O sistema deve registrar retiradas de materiais com usuário solicitante, setor, quantidade e finalidade.

RF04 – Consulta de estoque
O sistema deve permitir consultar o saldo atual dos itens em tempo real.

RF05 – Movimentações de estoque
O sistema deve registrar histórico de entradas, saídas, ajustes e transferências.

RF06 – Atualização automática de saldo
O sistema deve atualizar automaticamente o estoque após movimentações.

RF07 – Alertas de estoque mínimo
O sistema deve emitir alertas quando o estoque atingir o nível mínimo.

RF08 – Relatórios
O sistema deve gerar relatórios de consumo, entradas, saídas e estoque crítico.

RF09 – Usuários e permissões
O sistema deve permitir cadastro de usuários com perfis de acesso.

RF10 – Solicitação de materiais
O sistema deve permitir solicitação de materiais para aprovação.





            #requisitos não funcionais
RNF01 – Desempenho
O sistema deve responder consultas em até 2 segundos.

RNF02 – Disponibilidade
O sistema deve ter disponibilidade de 99% em horário comercial.

RNF03 – Segurança
O sistema deve ter autenticação e controle de acesso por perfil.

RNF04 – Integridade dos dados
O sistema deve garantir consistência dos dados de estoque.

RNF05 – Usabilidade
O sistema deve permitir uso com treinamento mínimo.

RNF06 – Escalabilidade
O sistema deve suportar aumento de usuários e produtos.

RNF07 – Backup
O sistema deve realizar backups automáticos diários.

RNF08 – Compatibilidade
O sistema deve funcionar em navegadores modernos.



         #Regras de negócio
RN01 – Autorização obrigatória
Nenhuma saída de material pode ocorrer sem autorização.

RN02 – Estoque mínimo
Não é permitido saldo negativo.

RN03 – Unidade de medida
Todo produto deve possuir unidade de medida.

RN04 – Registro obrigatório
Toda movimentação deve ser registrada.

RN05 – Aprovação de solicitações
Solicitações acima de limite devem ser aprovadas.

RN06 – Produtos inativos
Produtos inativos não podem ser movimentados.

RN07 – Setor solicitante
Toda saída deve estar vinculada a um setor.

RN08 – Rastreabilidade
Toda movimentação deve registrar usuário e data/hora.