# sistemas_operacionais2.0
*resposta(1)*
Finalidade:
top: foco técnico, monitoramento em tempo real via terminal.Monitor de Atividade e Gerenciador de Tarefas: foco no usuário comum, interface gráfica, uso geral.Forma de acessotop: linha de comando.Monitor de Atividade e Gerenciador de Tarefas: atalhos ou menus gráficos.
*resposta(2)*
Objetivo em todos os casos:Ordenar os processos pelo uso de CPU e ver qual está no topo — esse é o que mais consome recursos em tempo real.
*resposta(3)*
%MEM → Quanto da RAM total esse processo está usando
RES → RAM real em uso (mais confiável que VIRT)
VIRT → Total reservado, mas nem tudo está sendo usado
SHR → Parte da memória compartilhada (menos relevante isoladamente)
*resposta(4)*
Sistema	Ver PID em...	Encerrar processo pelo PID
macOS	Monitor de Atividade ou ps	kill PID ou kill -9 PID
Linux	top, htop, ps aux	kill PID ou kill -9 PID
Windows	Gerenciador (aba Detalhes)	taskkill /PID PID /F
*resposta(5)*
Mais visual: Monitor de Atividade e Gerenciador de Tarefas
Mais técnica, baseada em texto
*resposta(6)*
Sistema	Ferramenta/Comando	Mostra rede por processo?	Interface
macOS	Monitor de Atividade	✅ Sim	Gráfica
Windows	Gerenciador de Tarefas	✅ Parcialmente	Gráfica
Linux	nethogs	✅ Sim	Texto (Terminal)
*resposta(7) *
Sistema	Ferramenta	Mostra uso de disco por processo?	Interface
macOS	Monitor de Atividade	✅ Sim	Gráfica
Windows	Gerenciador de Tarefas	✅ Parcial (coluna "Disco")	Gráfica
Linux	iotop (não top)	✅ Sim	Texto
*resposta(8)*
Sistema	Hierarquia visível?	Como ver a hierarquia
macOS	Sim (janela “Processos em Árvore”)	Menu Janela > Processos em Árvore
Windows	Não direto na aba principal	Aba Detalhes > coluna PPID
Linux	Não no top, mas com ferramentas	Use pstree -p ou htop (F5 para árvore)

*resposta(9)**
Ambiente	Ferramenta recomendada
Desktop macOS	Monitor de Atividade
Desktop Windows	Gerenciador de Tarefas
Servidor Linux	top (ou htop, iotop, etc)
