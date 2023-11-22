

<h1>PROJETO INTEGRADOR</h1>

<h2>Sistema de Reserva de Salas</h2>

Em um ambiente de trabalho, muitas vezes as equipes precisam de um espaço
privado para que consigam discutir melhor seus projetos sem se preocupar em
atrapalhar as demais pessoas e assim conseguir ter foco na tarefa. Porém nem
sempre é fácil conseguirmos esses espaços sem planejamento.
Sendo assim, foi solicitado à equipe de desenvolvimento a criação de um
sistema de reservas de salas, na qual os funcionários devidamente cadastrados
pudessem verificar a disponibilidade dos espaços e assim agendar o seu uso.
Organização do Projeto
#O que é esperado:
1. Elaboração do kanban (sugestão de utilização: Trello, Notion, etc)
2. Criação do backlog (com tarefas referente ao desenvolvimento Front-end e Banco
de dados)
3. Detalhamento descritivo das tarefas da squad dentro dos seus cards (e não
apenas com títulos genéricos no card)
4. Formatação do kanban padrão "to do, doing, done"
5. Definição de data de entrega das tarefas nos cards
6. Definição de responsável pelo card ou checklist de completude
7. Priorização dos cards (ex: tags com cores para maior relevância ou com títulos
descritivos para nível de importância na priorização)
Entregas Mínimas
1. Front-end:
a. Tela que permite aos funcionários fazer login/logout,
b. Tela para visualizar salas disponíveis e fazer reservas.
c. Página de registro de novos funcionários.
2. Back-end:
a. Banco de dados para armazenar informações sobre funcionários e salas
disponíveis.
b. Às entidades Funcionários e Salas devem conter o relacionamento de 1:1
c. API para lidar com a autenticação, reserva de salas e consulta de
informações.
d. Variáveis do tipo Date deve seguir o padrão UTC-3
3. FuncionalidadedeReserva:
a. Os funcionários devem poder selecionar uma sala disponível e fazer uma
reserva.
b. Verificação de conflitos de reserva para evitar sobreposições.
c. Os funcionários devem ser capazes de consultar, alterar e cancelar suas
próprias reservas.
4. GerenciamentodeSalas:
a. Uma interface de administração para adicionar, editar e excluir salas
disponíveis.
b. Validação para garantir que as informações da sala sejam preenchidas
corretamente.
5. Segurança:
a. Proteção contra acesso não autorizado.
b. Proteção contra injeção de SQL e outras vulnerabilidades de segurança.
Critérios de Avaliação
1. UsabilidadeeDesign:
a. A interface de usuário deve ser intuitiva e amigável.
b. A navegação deve ser clara e eficiente.
2. Funcionalidade:
a. O sistema deve permitir que os funcionários façam login, reservem salas e
gerenciem suas reservas.
b. As reservas devem ser registradas no banco de dados.
c. Conflitos de reserva devem ser tratados adequadamente.
3. AdministraçãodeSalas:
a. A administração de salas deve ser fácil de usar e permitir a gestão eficaz
das salas disponíveis.
4. QualidadedoCódigo:
a. O código deve ser organizado, legível e seguir as melhores práticas de
desenvolvimento.
b. Deve haver documentação adequada para explicar a estrutura e
funcionamento do sistema.
5. Performance
a. TempodeCarregamentodaPágina:Tempo de carregamento das
páginas em diferentes dispositivos e conexões de internet.
b. Responsividade:interface do usuário em dispositivos de diferentes
tamanhos para garantir que ela se adapte corretamente.
c. CompactaçãodeRecursos:Verificar se os recursos CSS e JavaScript são
compactados adequadamente para reduzir o tamanho.
d. MonitoramentodeDesempenho:Implementar ferramentas de
monitoramento de desempenho e usar dados para otimizar o front-end
conforme necessário.
6. Testes:
a. Deve haver testes unitários para garantir a funcionalidade correta do
sistema.
7. Documentação:
a. Deve haver documentação que explique como usar o sistema, incluindo
instruções para configurar o ambiente de desenvolvimento.
