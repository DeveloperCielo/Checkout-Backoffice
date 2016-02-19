---
title: Cielo Backoffice 

toc_footers:
  - <a href='/Checkout-Cielo/'>Cielo Checkout Manual</a>
  - <a href='/Checkout-FAQ/'>Frequently Asked Questions</a>

search: true
---

# Cielo Backoffice

The purpose of this document is to guide the retailer during the sales with Checkout Cielo. Describing the features, 
the methods to be used, listing necessary information and providing examples.

## Overview

To access Cielo's Checkout Backoffice, it is necessary that the retailer **[log in on Cielo website](https://www.cielo.com.br/minha-conta)** 
by entering the Membership Information (Establishment Number.) and User:

![Backoffice Cielo Login](/images/checkout-login.png)

Then you must include your password:

![Backoffice Cielo Password](/images/checkout-login-senha.png)

In the "Online Sales" simply click Cielo's Checkout

![Online sales](/images/checkout-vendas-online.png)

If the Cielo's main website is not available, simply visit the URL https://cieloecommerce.cielo.com.br/backoffice and enter your e-mail
registration and password. 

[!Checkout Cielo](/images/checkout-cielo.png)

## Changelog

* **1.5** - 27/08/2015
    * Updates: Recurring button, the login screen, information about installments.
    * Inclusion of Recurrence's report
* **1.4** - 21/07/2015
    * Inclusion of Recurrence in "payment methods"
* **1.3** - 28/01/2015
    * Update of automatic capture
    * Update of ORDERS information
    * Update Anti-fraud Minimum amount.
* **1.2** - 21/01/2015
    * Name Change - Cielo's Checkout becomes integrated solution
* **1.1** - 16/12/2014
    * Update screens "Settings" and "My purchases".
* **1.0** - 21/11/2014
    * Initial version

## Cielo's Backoffice Pages

The Backoffice is made up of 6 different pages of administration Cielo Checkout. They are:

1.	[DashBoard](#dashboard)- Home Page where you will find out your account and on the volume and type of transactions 
that your store has been conducting via Cielo's Checkout
2.	[Orders](#pedidos) - this page contains a list with all the transaction held for a certain period of time in Cielo's Checkout. 
In this page is possible to search for a particular request, through a particular search parameter in the existing fields and unchecking 
the "checkbox" of "Payment Methods" or "Payment Status" and pressing the "Search" button.
3.	[Products](#produtos) - this page lists all registered products in Cielo's Checkout. It is also possible to search by product name 
on this page.The list of products can be exported in Excel format.
4.	[Reports](#relatórios) - On this page you can generate 05 types of reports:
    * "Financial report",
    * "Sales Detailed",
    * "Customer List",
    * "Billing Statement" and
    * "Recurrence Report".
5.	[Manuals](#maniais) - This page contains the manuals Cielo's Checkout, as well as the FAQ page and "Questions" where the retailer 
can contact the Cielo's Checkout support team.
6.	[Settings](#configurações) - Page where it is possible to make changes to the Store settings, their registration and change your
password data.

# DashBoard

Homepage which presents information about your account and the volume and type of transactions that your store has been conducting via 
Cielo' Checkout.

## Types of information

On this screen you will find two types of information.

•	**Alerts** - Indicates whether there are applications to expire on this date.
•	**Financial and transactional volume** - are interactive graphs that show a percentage (and totals) of the share of each 
payment methods in all transactions carried out and the total volume according to transactions status.

![DashBoard](/images/checkout-dashboard.png)

# Orders

This page contains the list with all the transaction held for a certain period of time in Cielo's Checkout. 
In this page is possible to search for a particular request, through a particular search parameter in the existing fields and 
unchecking the "checkbox" of "Payment Methods" or "Payment Status" and pressing the "Search" button.

The search result is displayed in the form of an operations list.This list can be exported to excel.

![Pedidos](/images/checkout-pedidos.png)

# Products

In this page are listed all registered products in Cielo's Checkout. It is also possible to search by product name on this page.
The list of products can be exported in Excel format.

In Products menu, there are also two other areas: **Products Register** and **Registrants Products List**.

## List Products Registered

![Products registered](/images/checkout-listar-produtos.png)

By clicking on the Title or SKU product, you will be redirected to product information page, where all product characteristics are 
reported and where you can set the default button (if your integration is based on the Cielo's Checkout button) to used in the 
sale of that product.The Integration via Button is best explained in item 
[Uso do botão Checkout Cielo “Comprar“](#uso-do-botão-checkout-cielo-comprar).

![Product Details](/images/checkout-detalhes-produto.png)

## Register products

In this page is possible to register their products based on the product type itself. The Cielo Checkout considers three kinds of products: Physical Material, Digital and Service.
•	**Physical Material** - Physical products that need to be sent by retailers. Eg: clothing, toys, etc.
•	**Digital** - Digital goods sold over the Internet.Eg: Software, Games, Music, etc.
•	**Services** - Services to be provided. Eg: delivery, projects and budgets.

![Register products](/images/checkout-cadastrar-produtos.png)

<aside class="notice"> Physical materials requires register <strong>a type of freight.</strong></aside>

<aside class="notice"><strong>The "SoftDescriptor"</strong> field allows retailer enter a message that will appear in the 
buyer's credit card invoice. This functionality is suitable for stores that have very different trade name in relation to 
Corporate's name.</aside>

<aside class="notice">The message included in the "SoftDescriptor" should be limited to 13 letters and no spaces.</aside>

<aside class="notice">Registration of products is not mandatory for retailers who use the integration via shopping cart.</aside>

# Reports

On this page you can generate 05 types of reports: "Financial report", "sales Detailed", "Customer List", "Billing Statement" and 
"Recurrence Report".

## Financial report
 
This report presents sales paid in a period of time, being separated by payment methods. Selecting the period and type of payment, 
after pressing "Search", the result will be displayed.

![Financial report](/images/checkout-relatorio-financeiro.png)

## Detailed sales report

This report informs the value of each order as well as data about the product and the buyer.The report only shows data of the applications considered with "PAID" status.

<aside class="notice">Orders placed in the <strong>test mode<strong> are not presented in this report, even if they are with status 
"PAID".</aside>

## Customers List

The customer list generate an excel file containing the data of customers who made purchases in your store.

### THE DATA SUBMITTED ARE:

1.	Name
2.	E-mail
3.	telephone
4.	CPF
5.	Address (as described by the client or as information returned by the CEP)
6.	Number
7.	Supplement (if any)
8.	Neighborhood
9.	City
10.	state
11.	Zip code

## Billing statement

The list of the amount charged for the services offered by Cielo will be presented in this report. All data plans and transaction 
costs will be charged here:

![Billing statement](/images/checkout-extrato-cobranca.png)

## Recurrence report

In this report it can search the set of recurrence and their transactions based on their ID or Status/occurrence interval.

![Recurrence report](/images/checkout-relatorio-recorrencia.png)

After clicking in the "+" you open the recurrence details screen:

![Recurrence details](/images/checkout-detalhes-da-recorrencia.png)

The recurrence details inform the shopping cart and history of scheduled transactions. By clicking '+ Details" the retailer is directed
to Order detail screen (see "ORDER" item)

# Manuals

This page contains the manuals Cielo's Checkout, as well as the FAQ page and "Questions" where the retailer can contact the Cielo's 
Checkout support team.

![Questions](/images/checkout-suporte.png)

In this page it is possible to contact regarding Operating questions, techniques and Commercial and have access to technical documents
and Cielo's Checkout support.

•	**Developer Guide** - Contains procedures and Cielo's Checkout integration guidelines to your website.
•	**Retailers Tutorial** - Main source of information about using Cielo's Checkout from the point of view of the Retailer
•	FAQ - Frequently Asked Questions about the Cielo Checkout. It contains information on Commercial, Technical, Operational questions 
and the Test mode.

# Store Settings

This page is possible to make settings on different mechanisms within the Cielo's Checkout. This area is divided into four different 
parts: Display, Payments, Fraud, Post Office & Freight Services.

## Exhibition

Here it is possible to change the logo of the payment's methods available in your store and the background color of the website via 
using the options box or by entering the code on the chosen color (Colors are in RGB pattern).

![Exhibition Settings](/images/checkout-configuracoes-loja.png)

<aside class="notice">The logo of your store will appear in the centralized Checkout screen.</aside>

## Payments

In this screen it is possible to change the settings for payment methods available in your store, defining them as active or not, 
and set the URL's return, notification and Status Change.

![Exhibition Settings](/images/checkout-configuracoes-pagamento.png)

### CREDIT CARDS AND INSTALLMENT

Simply check the card in the check box that you want to make available at the time of payment. To disable it, simply uncheck the 
checkbox.

The installment is defined by card issuer. The retailer defines the number of maxim installments available for each card. The Cielo 
Checkout allows up to 12 installments without interest.There is the option to set a minimum value of installment.
The value set makes regardless of the purchase price, the buyer can only make installment payments with value above the Minimum Value.

**Example**: If the minimum installment amount is $10.00, a purchase of $100.00 may be parcelled at 10x maximum, even if the store 
setting, the payment in 12x is enabled.

<aside class="warning">The maximum number of Store installment depends on the limit set in Membership. By default all affiliation is
released with 12 installments limit. The minimum installment amount required is R $ 5.00.</aside>

<aside class="warning">The authentication of credit cards occurs only for Visa and Mastercard. This function must be enabled in your 
membership.</aside>

### MAIN CIELO CHECKOUT URLS

The URLs must be registered by the retailer himself in his Backoffice, in "settings  Store Settings" tab.

•	**URL Return** - At the end of the transaction, the customer may be redirected to the URL of return. By clicking in the "Back" button
on the sales receipt, the buyer will be directing for the URL's return previously registered in the BackOffice.
•	**URL Notification**- At the end of a transaction a post is sent with all thesale's details to the URL's Notification, previously 
registered in the BackOffice.**The Notification POST is sent only when the transaction is completed, whether there was a change of 
transaction status**.
•	**URL Status Change** - When an application has changed their status, will be sending a post to the URL Status Change, previously 
registered in the BackOffice.The POST status change does not contain the shopping cart data, only the identification of order data.

You can resend the POST of Change Status in each transaction in the Order Screen. Just click on the blue buttons marked in the image 
below:

![Order details](/images/checkout-detalhe-pedidos.png)

<aside class="notice">Retailers of the "Terra Cielo Virtual Store" have URL's notification, status change and Return automatically 
updated. For these retailers, it is not necessary to change the URLs mentioned.</aside>

### DISCOUNT FOR BOLETOS AND ONLINE DEBT

It is possible to offer discounts in boleto and online debt payment's methods. This discount can be defined in two ways.

• **Via Backoffice**: Simply select the value (%) that the payment's methods will offer.
•	**POST**: it is possible to send the POST a parameter containing the discount (%) that the payment's method will offer.

### MINIMUM AMOUNT OF BOLETO

It is possible to set a minimum amount to present the boleto. **There is no boleto available for purchases with lower amount in the 
checkout screen**.

<aside class="warning">If the purchase price is lower than it should be and if there is no other payment's methods available, 
there will be no option for the buyer, forcing him to return to the store to create a shopping cart with an amount above the minimum.
To avoid this situation we suggest:<br /><ul><li>If your store does not have other payment's methods, inform the buyer about the boleto's
minimum amount.</li><li>Get other payment's methods such as credit cards (procedure performed at Checkout Cielo) online debit.</li></ul></aside>

<aside class="warning">The boleto's minimum amount does not work in the event of discounts set by the retailer. 
If the retailer set boleto minimum amount of $ 100.00 and a discount of 10% will generate a boleto of R $ 90.00 (less than the minimum)</aside>

### ANTI FRAUD

Here it is possible to set the automation of the capture processes and cancellation amount that a transaction should have to be 
analyzed.

<aside class="notice">If the retailer has not enabled the fraud on his contract with Cielo or doesn't send the fraud analysis request 
in the POST, the automatic capture is not performed if it is set to be made based on the risk analysis of status. 
It will be up to the retailer the manual capture of the application.<aside class="notice">

![Anti fraud](/images/checkout-anti-fraude.png)

Field of minimum amount for AF analysis:

![Minimum amount or anti fraud](/images/checkout-anti-fraude-valor-minimo.png)

### FREIGHT & POSTAL SERVICES

In this area you configure shipping options available in your store. In the Section [Shipping information](#informações-sobre-frete) for more detailed explanation 
of the types of freight available at Cielo's Checkout. There is also the area of Correios (post office) freight, a shipping calculator
to queries (this calculator gives the shipping amount of each type of freight registered for a given weight and location)

### REGISTRATION DATA

In this section are listed the data of registered shop and the retailer.

![Registry data](/images/checkout-dados-cadastrais.png)

### CHANGE YOUR PASSWORD

Here it is possible to change the password for access to the Cielo Checkout.

![Change password](/images/checkout-alterar-senha.png)

# Use the Buy Button of Checkout Cielo 

Integration via Button is a method of buying used whenever there is no "shopping cart" in your store or when you want to associate a 
direct instant purchase to a product, as a promotion in the homepage and skipping the shopping cart step.

Integration via button can also be used to send an e-mail marketing, or a collection via email, ie, adding the button (HTML) for the 
product/service to be purchased/paid. Or whenever you want to provide a quick sale.

To use this feature, you must register the product you want to sell your information, and then simply copy the generated source code 
for this button. The inclusion of the products is done within the Backoffice, at Products menu/Register Product

## Button features:

*	Each generated button is only for a particular product.
*	The price of the product can not be changed in the Checkout screen
* It's not necessary develop a shopping cart
*	Registration of the product is required to create the button.

Each button has a unique code that only allows to buy that particular product in price and shipping registered. 
Therefore, a fraudster can not change any of this information at the time of submitting the purchase because the Cielo's Checkout 
will get all product data in the Backoffice of the register, and will be worth the registered data.

# Payment options

This section explains the payment's methods used by Cielo's Checkout, as these work and how these are controlled in the backoffice.

## Boleto

All boleto generated (issued) appears with the status of "PENDING" in the Order Report. Their exchange status will depend on manual 
actions of the retailer.

### POSSIBLE BOLETO STATUS

* *PENDING** - boleto issued by the transaction process. Status continues until manually changed by the retailers.
* **PAID OUT** - Status used when the "Conciliate" button is activated by the retailer.This status can be reverted to pending using 
the "Undo reconciliation" Button.
* **EXPIRED** - active status after 10 days of creation of the boleto, if this has not located reconciled during this period. 
Boletos with "EXPIRED" status can be reconciled.

### RECONCILING A BOLETO

It is up to the retailer to confirm the payment through a Conciliation Guide with her/his bank statement.

![reconciling a boleto](/images/checkout-cielo-conciliar-boleto.png)

To perform the Conciliation you should:

1.	Access the order report at the Backoffice;
2.	Filter orders by Payment Method "Boleto" and status "PENDING" and identify the boleto concerned by amount;
3.	Click on the sign + at the end of the line to access the page "Details";
4.	Click on the button "Confirm Payment" and inform the payment date, for your control in the future;

The request goes to PAID status. The Buyer will also see the request as PAID in the "Backoffice of the Purchaser"

### UNDOING THE RECONCILIATION (PAYMENT) OF A BOLETO.

If the conciliation has been done wrong, simply:

1.	Find the Order;
2.	Enter the details and click on "Undo Payment" button;
3.	The order will return to the status of "PENDING".

## EXPIRED BOLETOS:

If the boleto is not reconciled within a period of 10 days after its expired date, the status will be changed to **"EXPIRED"**, 
for better control of the expired boletos. EXPIRED boletos can be reconciled.

![Boleto](/images/checkout-cielo-boleto.png)

<aside class="notice">Boleto validity - If the boleto expires on a non-working day, like Saturday, it will be valid until the 
next business day</aside>

### Data flow of Boleto

![Data flow of Boleto](/images/checkout-fluxo-boleto.png)

## Credit card

The Cielo's Checkout accepts major credit issuers in Brazil and in the world.They are: Visa, MasterCard, American Express (Amex), Link,
Diners, Discover, JCB and Aura.

### RECEIVING A CREDIT CARD SALE

Order by credit card will be included in [Backoffice Cielo Checkout](http://developercielo.github.io/Checkout-Backoffice/)t as 
"AUTHORIZED" or "not authorized", depending on the result of the authorization in Cielo. If you have any problem when processing 
this request (the consumer closed the screen, for example), it will include as **"NOT FINISHED"**.

## FRAUD ANALYSIS 

Orders **"AUTHORIZED"** will be sent online, that is, upon sale, to analyze the anti-fraud tool, when this development is properly 
standardized integration.The result of this analysis will be translated in the field **"AF indication"** in the Order Report for each 
order.

This analysis indicates a **"LOW RISK"** or "HIGH RISK" for the sale.This suggestion is what should guide the decision to confirm or 
cancel the sale. The analysis will be presented in "Order Details", as below:

![Fraud analysis](/images/checkout-cielo-analise-risco.png)

## Credit recurrence in Cielo Checkout

The Recurrence is an automated scheduling process of credit transactions, that is, a transaction that automatically repeats without
requiring the buyer to access transactional screen, according to the rules defined at the time of scheduling.

Recurring transactions are ideal for business models that involve the concept of signature or transactions that are repeated, 
but should not occupy the buyer's credit limit.

Difference between recurring transactions and installments:

* **Installments:** This is a transaction divided into "N" months.The integration amount of the transaction ranks independent buyer of
the initial installment credit limit (see example).The retailer receives the sales amount in installments and not run the risk of the 
installments be denied.
*	* **EX**: Sales of R $ 1,000.00 installments in 2 times.Although the buyer to pay only R $ 500.00 in the first installment, 
the amount of the consumed credit limit in January is full, R $ 1,000.00. If the card limit is less than R $ 1,000.00 the transaction 
will be denied
*	* **Recurring**: They are different transactions on the same card in previously scheduled times.The first transaction schedules the 
future sales from an interval X (see example). Each "X" intervals will charge your credit card. A sale can be divided into 
"N" Recurrences in order to not take the credit limit of a buyer (see example 02)
*	* **EX02**: Sales of R$ 1,000.00 on 01/15/2015, with a monthly recurrence and end date on 01/06/2015. Thereby, all transaction on
15/02 will be a new charge of R$ 1,000 in the buyer's card, repeating the process until 15/05, which is the last valid date before the
end date.
*	**EX03:** Sales of R$ 1,000 on 01/15/2015, with Monthly recurrence using two instalments.The store may have the intelligence to send 
the Checkout a transaction of $ 500.00 in January with monthly interval closing date in 15/02/2015.In this situation, the limit 
occupied at buyer's card will be R$ 500.00 initial invoice, avoiding the risk shown in Example 01

A recurrence transaction on the Cielo Checkout has two settings: "Interval" and "Closing Date".

•	**Interval** - repeating pattern and time interval between each transaction (monthly, bimonthly, quarterly, half yearly and annual)

•	* **Closing date** - Date of the recurrence process fails to occur.

The buyer's credit card data is stored securely within the Cielo's Checkout, allowing its reuse in a recurring transaction. This data is not accessed by the retailer.

The Recurrence transactions are available in the Backoffice as other sales in your store "ORDERS" tab.The first recurring transaction is a normal transaction, following the rules and preferences set by the retailer in the backoffice.Subsequent transactions are captured automatically.

## RECURRENCE BUTTON

One way to accomplish recurrence within the Checkout is to create a recurring button.Simply register the product, including a charge 
interval and a date for closing (optional), as shown below:

![Recurrence button](/images/checkout-botao-recorrencia.png)

<aside class="warning">If a button is used after the "End Date" registered, the transaction raises an error displaying "Oppss" in 
transactional screen. Data can be edited on the button of the editing screen in "Product Details"</aside>

### CANCELLATION OF CIELO CHECKOUT RECURRENCE

The cancellation of the recurrence occurs within the Backoffice Checkout Cielo, the Orders tab. Simply access a recurrence of 
transaction (marked with the symbol "Applicant"), go into the details (the symbol "+")

![My sales](/images/checkout-minhas-vendas.png)

Select one of the following two options:

![Cancel Recorrence](/images/checkout-cancelar-recorrencia.png)

## Types of Cancellation:

•	**Cancel** - Cancels the transaction in question without affecting future recurrence transactions.
•	**Cancel Recurrence** - cancels the scheduling future transactions as a whole, ending recurrence.It not cancels the current 
transaction or those that have already occurred.

<aside class="warning">The Recurrence occurs only for credit cards and product type "SERVICE" and "DIGITAL GOODS".</aside>
<aside class="warning">Recurrence is initiated at the time of authorization, NOT IN CAPTURE.</aside>
<aside class="warning">If the recurrence do not have a date to be finalized, it will automatically repeat until you cancel 
it manually.</aside>
<aside class="warning">The Recurrence must be enabled in your Affiliate, otherwise, scheduled transactions will be denied.</aside>

## CREDIT CARD FLOW

![Credit card flow](/images/checkout-fluxo-credito.png)

## Debit card

The Cielo's Checkout accepts major market debit card issuers: Visa and MasterCard. Debit card transactions have as participants 
issuing banks, which in turn use the same resources for online transactions (token, password card and etc.) to the authentication 
process.See the list of participating issuers in Support Cielo e-Commerce.

*	**E-mail**: cieloecommerce@cielo.com.br
* **Phones**:
* **Capital**: (no area code) 4002.9700
* **Other Places**: 0800.570.1700
* **From abroad**: +55 (11) 2860.1348

The authentication of the transaction will ensure extra security against the retailer disputes the consumer (chargeback).
The debit product necessarily requires a certified transaction, otherwise the transaction is not permitted. Authentication is required 
for debit transactions and optional for credit.

### DEBIT CARD TRANSACTION STEP BY STEP:

1.	Client accesses the internet banking
2.	Type the card password 
3.	Bank confirms the password
4.	Transaction executed

### DEBIT ONLINE

Applications sold through online debit will be included in [Backoffice Cielo Checkout](http://developercielo.github.io/Checkout-Backoffice/) as PENDING, PAID, UNAUTHORIZED or NOT FINISHED, 
depending on the outcome of the authorization by the Bank.

* **Pending** - corresponds when the buyer did not get response from the Bank when concluding the order, in the order words, 
you can not even charge the Bank website to enter the data for debit.
* **Paid**- corresponds when the buyer accomplish successfully the debit payment.
* **Unauthorized** - Presented to retailer when the buyer attempting a transaction via debit and not have to balance for the 
transaction.
* **Not Finished**- Presented to retailer in case of the buyer has problems to finalize the payment through Debit, either by 
closing the window seat or simply not coming to the bank screen.

### FLOW DEBIT ONLINE

![Online Debit flow](/images/checkout-fluxo-debito.png)

Difference between reversal and cancellation

* **Cancellation:** you can do it in the same day and return the card limite to the buyer's card within 72 hours, 
according to the rules of the issuing bank. It is not displayed on the buyer's invoice;

* **Reversal:** from the day after the capture, the amount is "returned" in the buyer's invoice within 300 days. 
It is presented in the buyer's invoice.

## Capture/Automatic Cancellation

<aside class="notice">See the difference between cancellation and reversal in <a href="#difference between reversal and cancellation">Diferença entre estorno e cancelamento</a></aside>

### AUTOMATIC CAPTURE

**"AUTHORIZED"** and **"LOW RISK"** sales in anti-fraud tool may be CAPTURED **automatically by the system**.
This requires setting in the [Backoffice Cielo Checkout](http://developercielo.github.io/Checkout-Backoffice/). 
After this setting, the status displayed will be "PAID". This sale will be confirmed (captured) in Cielo.

![Automatic capture and cancellation](/images/checkout-cielo-cancelamento-captura-automatico.png)

### AUTOMATIC CANCELLATION 

The "AUTHORIZED" sales, and "HIGH RISK" in anti-fraud tool may be CANCELLED automatically by the system. This requires setting 
in the [Backoffice Cielo Checkout](http://developercielo.github.io/Checkout-Backoffice/). After this setting, the status displayed will be "CALLED OFF".This sale will be canceled (undone) 
at Cielo.

<aside class="warning">Attention! You have the option to choose the best integration for your business, capture/manual or automatic cancellation is made 
directly from your Backoffice.</aside>

![Automatic capture and cancellation](/images/checkout-cielo-anti-fraude-cancelamento-captura.png)

## Capture/manual Cancellation

<aside class="notice">See the difference between cancellation and reversal in <a href="#diferença-entre-estorno-e-cancelamento">Difference between reversal and cancellation</a></aside>

**"AUTHORIZED"** sales awaiting a decision of confirmation or cancellation. And this decision should come in accordance with fraud analysis, if this feature is properly parameterized integration.

Confirmation of the sale should be made by the CAPTURE button on the "Orders" tab at [Backoffice Cielo Checkout](http://developercielo.github.io/Checkout-Backoffice/). After confirming, 
the status will change to "PAID". This sale will be confirmed (captured) in Cielo.

But the cancellation must be made by the CANCEL button in the same section in [Backoffice Cielo Checkout](http://developercielo.github.io/Checkout-Backoffice/). After the cancellation, the status will change to   "CANCELLED".This sale will be canceled (undone) at Cielo.

<aside class="warning">Attention! You have up to 5 days to confirm the sale! If this is not done, it is no longer valid in Cielo, and the reserved limit to your store/sale will be released.This is a standard procedure for all stores.When the authorized sale confirmation deadline expires, the application 
will automatically move into the "EXPIRED" status.This will happen on the sixth day after the authorization date (date of sale)</aside>

### Reversal of Sale

If the sale has already been confirmed (PAID status) it can be even in the future reversed. Simply click the button on the Order Details.

### EXPIRED CREDIT CARD SALES

When the authorized sale confirmation deadline expires, the application will automatically move into the "EXPIRED" status. This will happen on the sixth day after the authorization date (date of sale)

## Chargeback

The consumer (buyer) can somehow cancel the purchase directly with the bank issuing of the credit card. If this happens the merchant 
will receive a Chargeback "not buying Recognition" warning from Cielo or if there has been a purchase with a rigged card, you will 
receive a Chargeback notice as "fraud".

![Chargeback](/images/checkout-cielo-chargeback.png)

This communication is done via the [Backoffice Cielo Checkout](http://developercielo.github.io/Checkout-Backoffice/), but by selling extract Cielo, highlighted as a financial adjustment.
Sales extract is available at Cielo website [www.cielo.com.br na aba “Acessar Minha conta”](https://www.cielo.com.br/minha-conta).

![Access my account](/images/acessar-minha-conta.png)

After receiving this, in Cielo's own website it is possible to access the [Backoffice Cielo Checkout](http://developercielo.github.io/Checkout-Backoffice/) and signal the request to have received Chargeback, for its better control.Just enter the Order Details and click the "ChargeBack" button, and its status will be "chargeback".

## Freight

The Checkout Cielo supports different types of freight, which can be used differently according to the options offered in your store.The available options are:
•	Post office (Correios)
•	Fixed Shipping 
•	Free shipping
•	* No shipping

The manner and type of freight that will be active in your store is configured in the Cielo Checkout Backoffice.Because of the technical aspect, we suggest that the shipping settings has been made by a developer. Freight different calculation methods:

### CALCULATION FOR OWN SHIPPING

It can select one or more shipping options. They will be presented to the consumer according to your choice from the available options. The value selected by the consumer is added to the total purchase price.

### AGREEMENT WITH CORREIOS

* The Cielo Checkout will use this contract number to the freight calculation, using the freight table that you have agreed with Correios.In this way, the checkout will present all the shipping options of Correios (Sedex, Sedex 10, Sedex Hoje and PAC, etc.) for the consumer to choose, according to the entered destination zip code.The amount selected by the Consumer will be added to the total purchase price.
* Use the freight calculation of Correios on Cielo Checkout.The Cielo's Checkout will present at all Correios shipping options (Sedex, Sedex 10, Sedex Hoje and PAC, etc) for the consumer to choose, according to the entered destination ZIP code.The value selected by the consumer is added to the total purchase price.
* Selection of Shipping in the cart, and not at the Checkout Cielo.The Checkout Cielo only display the screen of choice of payment methods for consumers.The value of freight is already built into the final value

<aside class="notice">The consumer can not change the shipping address on the Cielo's Checkout screen</aside>  
