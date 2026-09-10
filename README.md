# EGV Usadosbr — Jornada da Corretora

Quadro Kanban para acompanhar o onboarding de corretoras no funil Usadosbr × C6 — da reunião comercial até produção.

**Link do quadro (GitHub Pages):** https://danielsilva-bit.github.io/jornada_corretor/

## O que o quadro faz

- Kanban com as 12 etapas do funil (Reunião → Formalização → Status Pagamento → Disponibilização de Número → Configuração Meta → Ativação do Número na Meta → Criação Perfil CRM → Criação Template/Comunicação → Envio da Base → Disparo Base → Treinamento → Produção), cada uma com o responsável (Usadosbr, C6 ou Corretora) e um ícone **i** com um resumo do que acontece ali (passe o mouse ou clique).
- Arrastar e soltar corretoras entre etapas, com histórico de entrada/saída de cada uma.
- Botão **Agrupar** para ver as etapas mescladas nas 3 fases do funil (Kickoff, Ativação, Capacitação e Start), coloridas por fase, com opção de abrir uma fase por vez.
- Filtros por responsável, busca e "somente atrasadas".
- Aba **Dashboard SLA**: prazo ideal x real por etapa, com gráfico e tabela.
- Exportação do relatório em CSV.
- Prazos de SLA por etapa são os valores oficiais publicados neste link — aparecem iguais para todo mundo que acessar e continuam os mesmos ao recarregar a página. Para mudar um prazo oficialmente, é preciso atualizar e publicar uma nova versão do arquivo (não dá pra editar direto pelo link).

## Atualizações recentes

- Ícone de informação (i) em cada etapa, com resumo do que é feito ali.
- SLA por etapa passou a ser sempre o valor oficial publicado (não fica mais preso ao navegador de quem acessa).
- Visual mais suave: cantos mais arredondados, sombras leves, brilho no botão principal e gráfico do SLA com gradiente — mantendo a identidade visual da C6 (preto, cinza, branco e laranja).
- Agrupamento de colunas por fase (Kickoff / Ativação / Capacitação e Start), com título horizontal, cor por fase e opção de expandir uma fase por vez.
- Dados reais das corretoras forçados no link público (sem risco de aparecer dado fictício de cache antigo do navegador).

## Como atualizar

O quadro é um único arquivo (`index.html`, sem dependências externas). Qualquer alteração deve ser pedida diretamente — evite editar ou subir arquivos manualmente pela tela do GitHub, para não sobrescrever o conteúdo por engano.
