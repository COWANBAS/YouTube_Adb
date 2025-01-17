Este script de usuário é projetado para melhorar a experiência de visualização no YouTube, removendo anúncios, avisos de erro e shorts. Aqui está uma visão geral de como funciona:

*Remoção de Avisos de Erro*

O script monitora a página em busca de elementos específicos que indicam a presença de mensagens de erro relacionadas ao uso de bloqueadores de anúncios.
Quando um elemento de mensagem de erro é detectado, ele é substituído por um iframe que carrega e reproduz o vídeo do YouTube sem exibir a mensagem de erro.

*Bloqueio de Anúncios*

O script define uma série de seletores CSS que correspondem a diferentes tipos de anúncios no YouTube.
Em seguida, ele cria estilos CSS que ocultam esses elementos, efetivamente removendo anúncios da página.
Além disso, o script monitora eventos de mutação no DOM para detectar e pular automaticamente anúncios em vídeo, além de fechar sobreposições promocionais.

*Remoção de Shorts*

O script utiliza um observador de mutações para monitorar a inserção de elementos na página.
Sempre que um elemento relacionado a shorts é detectado, ele é removido da página.
O script também se reconecta a eventos de navegação para garantir que os shorts sejam removidos mesmo após a navegação para uma nova página no YouTube.

*Funcionalidades de Reprodução Automática*

O script inclui funções para gerenciar o estado de reprodução automática de vídeos, permitindo ativar ou desativar a reprodução automática e ajustar botões de interface correspondentes.
Ele também observa o final dos vídeos e, caso a reprodução automática esteja ativada, inicia o próximo vídeo na fila.

*Manutenção e Execução*

O script se certifica de que suas funções só sejam executadas uma vez por sessão, usando flags de execução.
Ele também garante a execução das suas funcionalidades principais quando o DOM estiver totalmente carregado.
Em resumo, este script melhora significativamente a experiência de visualização no YouTube ao remover elementos indesejados, automatizar a reprodução de vídeos e garantir uma navegação mais limpa e sem interrupções.
