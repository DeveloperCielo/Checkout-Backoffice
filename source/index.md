---
title: Backoffice Cielo

toc_footers:
  - <a href='/Checkout-Cielo/'>Manual Checkout Cielo</a>
  - <a href='/Checkout-FAQ/'>Perguntas Frequêntes</a>

search: true
---

# Backoffice Cielo

Na página principal da Cielo é possível acessar o Backoffice Cielo. Para isso, basta clicar em **[Acessar Minha Conta](https://www.cielo.com.br/minha-conta)**:

Ao clicar em **[Acessar Minha Conta](https://www.cielo.com.br/minha-conta)**, uma nova tela se abrirá onde será possível se logar, se cadastrar ou fazer o login voltado para a Consulta a um determinado pedido.

![Login Backoffice Cielo](/images/checkout-login.png)

No menu da sua área restrita, clique em “Vendas Online” e em seguida “Checkout Cielo”. Pronto! A partir daí você poderá gerenciar seus pedidos, capturar ou consultar suas vendas, realizar configurações técnicas, mandar e-mail para o suporte e muito
mais!

![Vendas online](/images/checkout-vendas-online.png)

## Páginas do Backoffice Cielo

O Backoffice é formado por 6 paginas diferentes de administração do Checkout Cielo. Elas são:

1. [DashBoard](#dashboard) - Pagina inicial onde são apresentadas informações sobre a sua conta e sobre o volume e tipo de transações que sua loja vem realizando vio Checkout Cielo.
2. [Pedidos](#pedidos) - Nessa pagina fica contida toda a listagem de transações realizadas por um determinado periodo de tempo no Checkout Cielo.
3. [Produtos](#produtos) - Nessa pagina são listados todos os produtos cadastrados no Checkout Cielo. Tambem é possivel fazer uma busca pelo nome do produto nesta pagina.
4. [Relatórios](#relatórios) - Nesta pagina é possivel gerar 03 tipos de relatorios: Relatório financeiro, Detalhado de vendas e Listagem de clientes.
5. [Suporte](#suporte) - Nesta pagina constam os manuais do Checkout Cielo, assim como a pagina de FAQ e de “Duvidas”, onde o lojista pode entrar em contato com a equipe de suporte Checkout Cielo.
6. [Configurações](#configurações) - Página onde é possivel fazer alterações nas configurações da Loja, dos seus dados cadastrais e Alterar sua Senha.

# DashBoard

Pagina inicial onde são apresentadas informações sobre a sua conta e sobre o volume e tipo de transações que sua
loja vem realizando vio Checkout Cielo.

## Tipos de informações

Nessa tela você encontra dois tipos de informações:

* **Alertas** – Indica se há pedidos a expirar na data presente.
* **Volume financeiro e transacional** - São gráficos interativos que demonstram em porcentagem (e em valores totais) qual a participação de cada meio de pagamento no total de transações realizadas e o volume total de acordo com o status das transações.

![DashBoard](/images/checkout-dashboard.png)

# Pedidos

Nessa pagina fica contida toda a listagem de transações realizadas por um determinado periodo de tempo no Checkout Cielo. Nessa pagina é possivel pesquisar um determinado pedido , via a colocação de um determinado parametro de busca nos campos la existentes ou desmarcando os “checkbox” dos “Meios de pagamento” ou “Status de pagamento” e apertando o botão “Buscar”.

O resultado da pesquisa é exposta em forma de uma listagem de operações. Essa listagem pode ser exportada como forma de excel.

![Pedidos](/images/checkout-pedidos.png)

# Produtos

Nessa pagina são listados todos os produtos cadastrados no Checkout Cielo. Tambem é possivel fazer uma busca pelo nome do produto nesta pagina. A lista de produtos pode ser exportada no formato Excel.

No menu Produtos, há também outras duas áreas: **Cadastrar de produtos** e **Listar Produtos Cadastrados**.

## Listar Produtos Cadastrados

![Produtos cadastrados](/images/checkout-listar-produtos.png)

Clicando no Titulo ou SKU do produto, você será redirecionado a página de informações de Produto, onde todas as caracteristicas do produto são informadas e onde você pode definir o padrão do Botão (caso a sua integração seja com base no Botão Checkout Cielo) a ser usado na venda desse produto.

![Detalhes do produto](/images/checkout-detalhes-produto.png)

## Cadastrar de Produtos

Nessa pagina é possivel cadastrar seus produtos com base no tipo de produto em si. O Checkout Cielo considera 3 tipos de produtos: Material Fisico, Digital e Serviço.

* **Material Fisico** – Produtos Fisicos que necessitam ser enviados pelos lojistas. Ex: Roupas, Brinquedos, etc.
* **Digital** – Bems digitais vendidos pela internet. Ex: Software, Jogos , Musicas, etc.
* **Serviço** – Serviços a serem prestados. Ex: Entrega delivery, projetos e orçamentos.

![Cadastrar produtos](/images/checkout-cadastrar-produtos.png)

<aside class="notice">Material Fisico exige que um tipo de frete seja cadastrado.</aside>

<aside class="notice">O campo “SoftDescriptor” permite que lojista insira uma mensagem que será exibida na fatura do cartão de crédito do comprador. Essa funcionalidade é indicada para lojas que tem o nome fantasia muito diferente em relação a Razão social.</aside>

<aside class="notice">A mensagem inclusa no campo “SoftDescriptor” deve ser limitada a 13 letras e não pode conter espaços. Exemplo: “Loja X” (errado) “Loja_X” (correto)</aside>

<aside class="notice">O cadastro de produtos não é obrigatório para lojistas que utilizem a integração via carrinho</aside>

# Relatórios

Nesta pagina é possivel gerar 03 tipos de relatorios: Relatório financeiro, Detalhado de vendas e Listagem de clientes.

## Relatorio Financeiro

Esse relatorio apresenta as vendas pagas em um determinado periodo de tempo, sendo separadas por meio de pagamento. Selecionando o periodo e tipo de pagamento, após pressionar “Buscar” o resultado será apresentado.

![Relatório financeiro](/images/checkout-relatorio-financeiro.png)

## Relatório detalhado de vendas.

Esse relatorio informa o valor de cada pedido assim como dados sobre o produto e o comprador. O relatorio somente informa dados dos pedidos considerados com status “PAGO”.

<aside class="notice">Pedidos realizados no Modo de teste não são apresentados nesse relatório, mesmo que estejam com o status “PAGO”</aside>

![Relatório detalhado de vendas](/images/checkout-relatorio-detalhado-vendas.png)

## Listagem de clientes

A listagem de clientes gera um arquivo excel contendo os dados dos clientes que realizaram compras em sua loja.

### Os dados apresentados são:

1. Nome
2. E-mail
3. Telefone
4. CPF
5. Endereço (como descrito pelo cliente ou como retornado pela informação do CEP)
6. Numero
7. Complemento (se houver)
8. Bairro
9. Cidade
10. Estado
11. CEP

## Extrato de cobrança

A lista do valor cobrado pelos serviços oferecidos pela Cielo será apresentada neste relatório. Todos os dados dos planos e custos transacionais serão apresentados aqui:

![Extrato de cobrança](/images/checkout-extrato-cobranca.png)

# Suporte

Nesta aba constam os manuais do Checkout Cielo, assim como a pagina de FAQ e de “Duvidas”, onde o lojista pode entrar em contato com a equipe de suporte Checkout Cielo.

![Dúvidas](/images/checkout-suporte.png)

Nessa pagina é possivel entrar em contato a respeito de duvidas Operacionais, tecnicas e Comerciais e ter acesso aos documentos técnicos e de suporte do Checkout Cielo.

* **Manual do Desenvolvedor** – Contém os procedimentos e diretrizes de integração do Checkout Cielo ao seu site.
* **Tutorial do Lojista** – Principal fonte de informação sobre a utilização do Checkout Cielo do ponto de vista do Lojista
* **FAQ** – Perguntas mais comuns a respeito do Checkout Cielo. Contem informações sobre questões Comerciais, Técnicas, Operacionais e sobre o Modo de teste.

# Configurações

Página onde é possivel fazer alterações nas **configurações da Loja**, dos seus **dados cadastrais** e **Alterar sua Senha**.

## Configurações da Loja

Nesta pagina é possivel fazer configurações em diferentes mecanismos dentro do Checkout Cielo. Essa área é dividida em 4 partes diferentes: Exibição, Pagamentos, Antifraude, Frete de Correios & serviços.

![Configuração Exibição](/images/checkout-configuracoes-loja.png)

### Exibição

Aqui é possivel alterar o logo do meio de pagamento disponível em sua loja e a cor de fundo do site via o uso da caixa de opções ou digitando o código relativo a cor escolhida (As cores estão no padrão RGB).

<aside class="notice">O logo de sua loja será exibido na tela de Checkout centralizado.</aside>

### Pagamentos

Nesta tela é possivel alterar as configurações dos meios de pagamento disponiveis em sua loja , os definindo como ativos ou não, e configurar a URL de retorno, notificação e Mudança de Status.

#### Cartões de crédito e Parcelamento

Basta marcar a caixa de seleção do cartão que deseja disponibilizar no momento do pagamento. Para desabilita-lo, basta desmarcar a caixa de seleção O parcelamento é definido por bandeira de cartão. O numero de parcelas maximas disponibilizadas para cada cartão passa a ser definida pelo Lojista. O Checkout Cielo permite parcelamento até 12 vezes sem juros.

Há a opção de definir um valor minimo de parcelamento. O valor definido faz com que independentemente do valor da compra, o comprador somente possa fazer parcelamentos com valor acima do Valor Minimo.

**Exemplo:** Caso o valor minimo de parcelamento seja de R$10,00, uma compra de R$100,00 poderá ser parcelada máximo em 10x, mesmo que na configuração da loja o parcelamento em 12x esteja habilitado.

<aside class="warning">O numero maximo de parcelamento da loja depende do limite definido na Afiliação. Por padrão toda afiliação tem limite de 3 vezes.</aside>

<aside class="warning">O cartão American Express tem limite de parcelamento em 3 vezes por padrão. Essa configuração é standart da bandeira AMEX, logo , não é possivel aumentar o numero de parcelas alem deste limite.</aside>

#### URLs principais do Checkout Cielo

As URL’s devem ser cadastradas pelo próprio lojista no seu Backoffice, na aba “configurações / Configurações
da loja”.

* **URL de Retorno** - Ao finalizar a transação o comprador final poderá ser redirecionado para a URL de retorno. Ao clicar no botão “VOLTAR” na tela de comprovante de vendas, o comprador será direcionando para a URL de retorno previamente cadastrada no BackOffice.
* **URL de Notificação** - Ao finalizar uma transação é enviado um post com todos os dados da venda para a URL de Notificação, previamente cadastrada no BackOffice. O POST de notificação é enviado apenas no momento que a transação é finalizada, independentemente se houve alteração do status da transação.
* **URL de Mudança de Status** - Quando um pedido tiver seu status alterado, será enviando um post para a URL de Mudança de Status, previamente cadastrada no BackOffice. O POST de mudança de status não contem dados do carrinho, apenas dados de identificação do pedido.

Na tela de pedidos, dentro de cada transação, há a opção de reenvio do POST de mudança de status. Basta clicar nos botões azuis, marcados na imagem abaixo:

![Detalhes do pedido](/images/checkout-detalhe-pedidos.png)

#### Desconto para Boletos e débito online

É possivel realizar oferecer descontos nos meios de pagamento boleto e débito online. Esse desconto pode ser definido de duas maneiras.

* **Via Backoffice:** Basta selecionar o valor em (%) que o meio de pagamento virá a oferecer.
* **Via POST:** é possivel enviar o no POST do carrinho um parametro contendo o desconto (%) que o meio de pagamento virá a oferecer.

#### Valor Minimo de boleto

É possivel definir um valor minimo para que o boleto seja apresentado. Compras em valor inferior ao definido não tem o boleto disponibilizado na tela de checkout.

<aside class="warning">Se valor da compra for inferior, caso não haja outro meio de pagamento disponivel, não haverá opção para o comprador, obrigando-o a retornar a loja criar um carrinho com o valor acima do minimo.</aside>

Para evitar a situação descrita no alerta acima, sugerimos:

* Caso sua loja não tenha outros meios de pagamento, informe ao comprador sobre o valor minimo do boleto.
* Adquira outros meios de pagamento como Cartões de crédito (procedimento realizado pelo Checkout Cielo) ou débito online.

<aside class="warning">O valor minimo do boleto não funciona em caso de descontos definidos pelo lojista. Caso o lojista defina valor minimo de boleto de R$100,00 e um desconto de 10%, será gerado um boleto de R$90,00 (inferior ao minimo)</aside>

#### Antifraude

Aqui é possivel definir a automação dos processos de captura e cancelamento de pedidos com base no resultado da analise de anti-fraude.

<aside class="notice">Se o lojista não tem habilitado o antifraude em seu contrato junto a Cielo ou não enviar no POST a solicitação de analise de fraude, a captura automática não será executada. Caberá ao lojista a captura manual do pedido.</aside>

![Anti fraude](/images/checkout-anti-fraude.png)

#### Frete de Correios & Serviços

Nesta área você configura as opções de frete disponiveis em sua Loja.

Na seção sobre informações sobre frete há uma explicação mais detalhada sobre os tipos de fretes disponiveis no Checkout Cielo. Há tambem na área de fretes de Correiros, uma calculadora de frete para consultas (essa calculadora dá o valor de frete de cada tipo de frete cadastrado para um determinado peso e localidade)

![Frete Correios](/images/checkout-frete-correios.png)

#### Dados Cadastrais

Nesta seção, ficam listados os dados da loja cadastrada e do Lojista.

![Dados cadastrais](/images/checkout-dados-cadastrais.png)

#### Alterar sua Senha

Aqui é possivel alterar a senha de acesso ao Checkout Cielo.

![Alterar senha](/images/checkout-alterar-senha.png)