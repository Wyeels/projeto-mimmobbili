<h1>Apresentação</h1>
<p>Este repositório é apenas um repositório de exposição de um software recentemente criado para atender as demandas de vendas de móveis de um cliente. O projeto final está salvo em outro local devido suas credenciais. Ressalto também que no projeto final faltaram a implementação de algumas coisas devido ao conhecimento, solicitação do cliente e a espera da resposta real. Além disso, projeto também serviu de base para relembrar e aprender algumas coisas relacionadas a programação e implementação de API's, após alguns meses sem nenhum contato devido a rotina apertada.</p>
<P>Dito isso, segue em anexo as imagens com cada área do projeto e as devidas explicações.</P>

<h2>Tela principal do projeto</h2>
<p>Logo abaixo estará uma print da tela inicial do projeto rodado em uma tela full-hd full-screen. A tela principal é composta pelo <strong>Menu</strong>, <strong>Logo da Indústria</strong>, <strong>Carrinho</strong> e <strong>Ícone de Login</strong>. O header com o background da imagem principal da empresa e o catálogo de itens logo abaixo em formato de vitrine responsiva que se locomove para o lado em alguns segundos caso o usuário não clique em nenhum item ou deixe seu mouse em cima de algum dos produtos.</p>
<img width="1872" height="922" alt="paginaPrincipal" src="https://github.com/user-attachments/assets/ed7a6829-015a-4c5c-9537-91fe35cca6fd" />
<p>Além disso, também foi implementado um menu superior que se fixa a parte superior da página enquanto o usuário desliza para verificar todos os itens disponíveis.</p>
<img width="1872" height="922" alt="paginaPrincipalComMenuSuperior" src="https://github.com/user-attachments/assets/7772e797-0299-451e-bc19-98860306b3f9" />
<p>Pra finalizar a apresentação principal, o rodapé com as informações de <strong>Suporte</strong>, <strong>Métodos de Pagamento</strong> e <strong>Créditos finais de direitos autorais</strong>.</p>
<img width="1872" height="921" alt="rodape" src="https://github.com/user-attachments/assets/ebc77479-60bb-497a-9a14-0ab5d64de49c" />

<h2>Navegação</h2>
<p>Devido a quantidade de opções disponíveis, optei por deixar o menu superior em todos os tamanhos de tela, contando com o redirecionamento para cada seção de produtos (na página principal), consultar suporte, conta/perfil e produtos adquiridos.</p>
<img width="1870" height="920" alt="PaginaPrincipalMenuAberto" src="https://github.com/user-attachments/assets/0945dd59-7c30-4ca8-b2ab-db639c0adb60" />
<p>Em cada seção, adicionei um texto superior que funciona como um link para redirecionar o usuário para uma área exclusiva de cada produto, para que ele não tenha que ficar esperando a roleta de produtos girar para ver os outros produtos, além de poder conferir todos os produtos disponíveis.</p>
<img width="1869" height="921" alt="telaProdutos" src="https://github.com/user-attachments/assets/ad1f7e29-a940-46f4-80dd-c877efc394ad" />

<h2>Funcionalidades e Acompanhamento</h2>
<p>Adicionei a tela de pagamentos para que o usuário verifique todos os itens que havia adicionado ao carrinho anteriormente, podendo excluir individualmente ou de forma geral caso necessário (botão de lixeira e botão de limpar carrinho), ou confirmar sua compra onde seria redirecionado para outra página para realizar o pagamento a depender do valor total dos itens dentro do carrinho, calculados por uma função no código principal.</p>
<img width="1872" height="923" alt="carrinhoAbertoVazio" src="https://github.com/user-attachments/assets/07fae9ef-41a6-41c1-91a5-b5822bcaf649" />
<img width="1871" height="920" alt="carrinhoAberto" src="https://github.com/user-attachments/assets/2aa210c3-66de-48dd-a5f6-26d1b90bcf32" />
<p>Além disso, adicionei um botão pra suporte, onde o usuário poderia enviar um ticket para atendimento complexo e autoatendimento para soluções simples. Nessa parte eu poderia ter usado as API's da Google Gemni, OpenAI, Cloud ou até mesmo a nova biblioteca "Transformers.js" para processar dados e entregar uma IA mais forte e eficiente, porém, optei por apenas adicionar mensagens prontas com apoio de text includes com palavras chaves apenas para um auxilio simples, justamente porque não iria utilizar o projeto para produção para clientes reais ainda.</p>
<img width="1869" height="921" alt="suporteAberto" src="https://github.com/user-attachments/assets/9f07c1a0-8120-4479-b79e-919c24f1b1b6" />
<img width="1869" height="919" alt="suporteTicketAberto" src="https://github.com/user-attachments/assets/38982617-5586-4d5c-b92d-8fff09f3d50b" />
<img width="1870" height="918" alt="suporteAutoatendimentoAberto" src="https://github.com/user-attachments/assets/d74793ec-2da8-43b0-978c-81b5c80d0349" />
<br>
<p>Por fim, tela de perfil com dados básicos do usuário e opção de <strong>sair da conta</strong> e a tela de produtos, para verificar os produtos já comprados.</p>
<img width="1868" height="919" alt="perfilAberto" src="https://github.com/user-attachments/assets/f019eb11-6a80-4b6d-b432-b5147b105912" />
<img width="1230" height="921" alt="telaMeusProdutosAberta" src="https://github.com/user-attachments/assets/730588d5-0b51-451e-a889-a1bf8fc68cfe" />

<h2>Informações de Criação</h2>
<p>Para criação deste projeto, utilizei a implementação de localStorage para armazenar dados no navegador enquanto o usuário não está logado, mas garantindo que quando ele logue, tudo que foi feito anteriormente continue na conta adicionada, como produtos no carrinho e etc. Utilizei Node.JS pela primeira vez para apoiar no banco de dados e sistema de pagamentos; Utilizei o supabase como ferramenta principal de armazenamento de dados, com tabelas para usuários, produtos e pedidos. Para sistema de pagamento utilizei o MP com as funcionalidades de Webhook, com funções criadas com Node (Supabase CLI) para gerenciar as notificações de confirmação de compra e para solicitar os dados que seriam usados na tela de pagamento, tudo feito de maneira transparente e automática, além de respostas rápidas graças ao uso do realtime.</p>
