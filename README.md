#Youtube ADB

Este script de usuário é projetado para melhorar a experiência de visualização no YouTube, removendo anúncios, avisos de erro. Aqui está uma visão geral de como funciona:

*Remoção de Avisos de Erro*

O script monitora a página em busca de elementos específicos que indicam a presença de mensagens de erro relacionadas ao uso de bloqueadores de anúncios.
Quando um elemento de mensagem de erro é detectado, ele é removido

*Bloqueio de Anúncios*

O script cria um element para bloquear items especificos relacionados a anúncios na tela inicial do youtube, em video ele observa se não esta rodando um anúncio com o botão de pular, se tiver o botão de pular automaticamente e clicado nele, se o anúncio não tiver esse botão o video e mutado na mesma hora e começa a rodar em uma velocidade muito rápida e também força pular para o final do video o quanto antes.

*Manutenção e Execução*

O script contém um gerador de flags para garantir que so esteja sendo rodado uma vez por sessão no navegador assim evitando um consumo maior de mémoria ram, fica constantemente em verificação para ver se a página não removeu o element para retirar os anuncios da tela inicial e durante a execução do video garantindo a remoção deles.
