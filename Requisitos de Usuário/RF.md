| ID  | Requisito | Prioridade | Requisitos Relacionados
| ------------- | ------------- |------------- |------------- |
| [RF01] | A aplicação deve permitir que usuários não autenticados possam se registrar com informações pessoais | Alta | - |
| [RF02] | Um usuário não autenticado pode alterar a própria senha através do fluxo de "Esqueceu a senha" | Média | RF01 |
| [RF03] | Um usuário não autenticado pode realizar a autenticação na aplicação. | Alta | RF01 |
| [RF04] | Um usuário autenticado pode realizar pesquisas de produtos por categoria, tipo de roupa, marca, tamanho, cor, etc. | Alta | RF01 |
| [RF05] | Um usuário não autenticado pode realizar pesquisas de produtos por categoria, tipo de roupa, marca, tamanho, cor, etc. | Alta | - |
| [RF06] | A aplicação deve ter um filtro avançado para refinar os resultados da pesquisa. | Média | RF04, RF05 |
| [RF07] | A aplicação deve exibir informações detalhadas de produtos, incluindo imagens, preços, descrições e disponibilidade. | Alta | - |
| [RF08] | A aplicação poderá ter classificação por popularidade, preço, avaliações dos clientes, etc. | Média | - |
| [RF09] | Um usuário autenticado pode adicionar itens ao carrinho | Alta | RF01 |
| [RF10] | Um usuário não autenticado pode adicionar itens ao carrinho | Alta | - |
| [RF11] | Um usuário autenticado pode remover itens do carrinho | Alta | RF01 |
| [RF12] | Um usuário não autenticado pode remover itens do carrinho | Alta | - |
| [RF13] | A aplicação deve calcular automaticamente o total da compra. | Alta | RF09, RF10, RF11, RF12 |
| [RF14] | Usuários podem visualizar o resumo do carrinho antes da finalização da compra. | Alta | RF09, RF10, RF11, RF12, RF13 |
| [RF15] | A aplicação deve coletar as informações de envio e pagamento. | Alta | RF01 |
| [RF16] | Somente um usuário autenticado pode finalizar o processo de compra (checkout) | Alta | RF01 |
| [RF17] | A aplicação deve gerar números de pedidos e confirmações de compra por e-mail. | Alta | RF01 |
| [RF18] | Um usuário autenticado pode visualizar o histórico de pedidos feitos. | Média | RF01 |
| [RF19] | Um usuário autenticado pode obter detalhes do rastreamento de pedidos em tempo real. | Alta | RF01 |
| [RF20] | Um usuário autenticado pode realizar o cancelamento de pedidos antes do envio. | Alta | RF01 |
| [RF21] | A aplicação deve atualizar em tempo real o estoque de produtos. | Alta | - |
| [RF22] | A aplicação deve notificar quando o estoque está baixo para administradores. | Alta | - |
| [RF23] | A aplicação deve possuir um sistema de Comentários e Avaliações. | Alta | RF01 |
| [RF24] | Somente usuários cadastrados podem deixar avaliações e comentários sobre produtos. | Alta | RF01 |
| [RF25] | Somente administradores pode gerir o conteúdo da aplicação | Alta | - |
| [RF26] | A aplicação deve recomendar produtos com base no histórico de compras e preferências do cliente. | Média | RF01 |
| [RF27] | Somente um usuário autenticado pode favoritar produtos | Média | RF01 |
