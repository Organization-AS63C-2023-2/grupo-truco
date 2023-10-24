# 1. História de Usuário

A Tabela 3 a seguir contém as Histórias de Usuárias elicitadas. 

<table>
    <thead>
        <tr style="background-color: purple; color: white">
            <th style="border-style: solid; border-width: 1px; text-align: center">ID</th>
            <th style="border-style: solid; border-width: 1px; text-align: center">História de Usuário</th>
            <th style="border-style: solid; border-width: 1px; text-align: center">Critérios de Aceitação</th>
            <th style="border-style: solid; border-width: 1px; text-align: center">Prioridade</th>
            <th style="border-style: solid; border-width: 1px; text-align: center">RF/RNF relacionado</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">US01</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">Eu, como um cliente, quero poder buscar as roupas disponíveis para compra.</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">
                <ol>
                    <li>Ao entrar na aplicação, os produtos devem aparecer na página inicial.</li>
                    <li>Os componentes de produtos devem ser responsivos.</li>
                    <li>A exibição dos produtos deve funcionar em diferentes plataformas.</li>
                    <li>Os produtos devem ser exibidos em formatos de Grid Table.</li>
                </ol>
            </td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">Alta</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">RF01, RF04, RF05, RF06, RF07, RF08, RF23</td>
        </tr>
        <tr>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">US02</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">Eu, como um cliente, desejo ter acesso aos rastreamentos de pedidos realizados.</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">
                <ol>
                    <li>O usuário precisa estar autenticado para a aplicação buscar as informações do requisitante.</li>
                    <li>A aplicação não deve permitir buscar pedidos de outros usuários.</li>
                </ol>
            </td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">Alta</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">RF19</td>
        </tr>
        <tr>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">US03</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">Eu, como um cliente, preciso me registrar na aplicação para realizar compras.</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">
                <ol>
                    <li>Somente usuários autenticados poderão completar o fluxo de compra (checkout).</li>
                </ol>
            </td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">Alta</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">RF01</td>
        </tr>
        <tr>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">US04</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">Eu, como um cliente, quero poder adicionar produtos ao carrinho e visualizá-lo dinamicamente.</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">
                <ol>
                    <li>A aplicação deve permitir adicionar produtos ao carrinho.</li>
                    <li>A aplicação deve permitir remover produtos do carrinho.</li>
                    <li>A aplicação deve calcular o preço do carrinho com base nos produtos adicionados ou removidos.</li>
                    <li>Os usuários podem visualizar o resumo do carrinho antes da finalização da compra.</li>
                </ol>
            </td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">Alta</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">RF08, RF10, RF11, RF12, RF13, RF14</td>
        </tr>
        <tr>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">US05</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">Eu, como um cliente, desejo receber recomendações personalizadas de produtos com base no meu histórico de compras e preferências.</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">
                <ol>
                    <li>A aplicação deve coletar e analisar o histórico de compras do usuário.</li>
                    <li>Com base no histórico de compras, a aplicação deve gerar recomendações de produtos relacionados.</li>
                    <li>As recomendações devem ser exibidas de forma clara e acessível na página inicial.</li>
                    <li>Os produtos recomendados devem ser clicáveis, direcionando o usuário para a página do produto.</li>
                </ol>
            </td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">Média</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">RF18, RF22</td>
        </tr>
        <tr>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">US06</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">Eu, como um cliente, desejo ter a opção de salvar produtos em uma lista de desejos para compra futura.</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">
                <ol>
                    <li>Na página do produto, o usuário deve ter a opção de adicionar o produto à lista de desejos.</li>
                    <li>A lista de desejos deve estar acessível a partir do perfil do usuário.</li>
                    <li>O usuário deve ser capaz de remover produtos da lista de desejos, se necessário.</li>
                    <li>Os produtos na lista de desejos devem exibir informações detalhadas, incluindo preço e disponibilidade.</li>
                </ol>
            </td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">Média</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">RF15, RF16, RF24</td>
        </tr>
        <tr>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">US07</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">Eu, como um administrador do sistema, desejo ter a capacidade de gerenciar o catálogo de produtos.</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">
                <ol>
                    <li>O administrador deve ter acesso a uma interface de administração.</li>
                    <li>O administrador deve ser capaz de adicionar novos produtos, especificando detalhes como nome, descrição, preço e imagens.</li>
                    <li>O administrador deve ser capaz de atualizar informações de produtos existentes, se necessário.</li>
                    <li>O administrador deve ser capaz de remover produtos do catálogo.</li>
                    <li>Todas as alterações feitas pelo administrador devem ser refletidas na aplicação do cliente.</li>
                </ol>
            </td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">Alta</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">RF24</td>
        </tr>
        <tr>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">US08</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">Eu, como um cliente, desejo ter a opção de redefinir minha senha se eu a esquecer.</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">
                <ol>
                    <li>A aplicação deve fornecer uma opção de "Esqueceu a senha" na tela de login.</li>
                    <li>O usuário deve receber um e-mail com um link seguro para redefinir sua senha.</li>
                    <li>O link deve expirar após um período de tempo para fins de segurança.</li>
                </ol>
            </td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">Média</td>
            <td style="border-style: solid; border-width: 1px; text-align; vertical-align: middle">RF02</td>
        </tr>
        <tr>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">US09</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">Eu, como um cliente, desejo receber notificações por e-mail sobre promoções e ofertas especiais.</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">
                <ol>
                    <li>Os usuários devem ter a opção de optar por receber e-mails promocionais durante o registro.</li>
                    <li>Os usuários podem alterar suas preferências de notificação em seus perfis.</li>
                    <li>Os e-mails promocionais devem incluir informações sobre ofertas, descontos e produtos em destaque.</li>
                </ol>
            </td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">Média</td>
            <td style="border-style: solid; border-width: 1px; text-align; vertical-align: middle">RF01</td>
        </tr>
        <tr>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">US10</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">Eu, como um cliente, desejo poder avaliar e deixar comentários sobre os produtos que comprei.</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">
                <ol>
                    <li>Os usuários devem poder avaliar produtos após a compra.</li>
                    <li>Os usuários podem deixar comentários e classificações (por exemplo, estrelas) nos produtos.</li>
                    <li>Os comentários devem ser exibidos na página do produto para outros clientes.</li>
                </ol>
            </td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">Alta</td>
            <td style="border-style: solid; border-width: 1px; text-align; vertical-align: middle">RF20</td>
        </tr>
         <tr>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">US11</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">Eu, como um cliente, desejo poder visualizar o histórico completo de todos os meus pedidos anteriores.</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">
                <ol>
                    <li>Os usuários devem ter acesso a uma seção de histórico de pedidos em seus perfis.</li>
                    <li>Os detalhes de cada pedido, incluindo produtos, data de compra e status de entrega, devem ser exibidos.</li>
                    <li>Os usuários podem selecionar um pedido para obter mais informações, como número de rastreamento.</li>
                </ol>
            </td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">Alta</td>
            <td style="border-style: solid; border-width: 1px; text-align; vertical-align: middle">RF15, RF16</td>
        </tr>
         <tr>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">US12</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">Eu, como um administrador do sistema, desejo receber notificações sobre estoque baixo de produtos para que eu possa reabastecer o estoque a tempo.</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">
                <ol>
                    <li>O sistema deve monitorar automaticamente os níveis de estoque.</li>
                    <li>Se o estoque de um produto atingir um limite crítico, o administrador deve receber uma notificação por e-mail.</li>
                    <li>O e-mail de notificação deve conter informações sobre o produto com estoque baixo.</li>
                </ol>
            </td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">Alta</td>
            <td style="border-style: solid; border-width: 1px; text-align; vertical-align: middle">RF19</td>
        </tr>
        <tr>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">US13</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">Eu, como um cliente, desejo ter uma lista de favoritos onde posso salvar produtos que pretendo comprar no futuro.</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">
                <ol>
                    <li>Os usuários devem poder adicionar produtos aos seus favoritos a partir das páginas de produtos.</li>
                    <li>Os usuários podem visualizar a lista de produtos favoritos em seus perfis.</li>
                    <li>Os produtos marcados como favoritos devem ser destacados na loja.</li>
                </ol>
            </td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">Média</td>
            <td style="border-style: solid; border-width: 1px; text-align; vertical-align: middle">RF15, RF16</td>
        </tr>
        <tr>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">US14</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">Eu, como um cliente, desejo poder rastrear o status da entrega do meu pedido em tempo real.</td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">
                <ol>
                    <li>Os usuários devem poder acessar informações de rastreamento a partir de seus históricos de pedidos.</li>
                    <li>As informações de rastreamento devem ser atualizadas em tempo real e incluir a localização atual do pedido, a data prevista de entrega e outras informações relevantes.</li>
                </ol>
            </td>
            <td style="border-style: solid; border-width: 1px; text-align: center; vertical-align: middle">Alta</td>
            <td style="border-style: solid; border-width: 1px; text-align; vertical-align: middle">RF19</td>
        </tr>
    </tbody>
</table>

<div style="text-align: center">
    <p>Tabela 3: Histórias de Usuário</p>
</div>

## 5. Referências bibliográficas
