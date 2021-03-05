* [What is the project] (# O-Q-% C3% A9-O-project)
* [Requirements] (# requirements)
* [Installation] (# installs% C3% A7% C3% A3o)
* [Update] (# Update% C3% A7% C3% A3O-DA-VERS% C3% A3O-Free-Para-Vers% C3% A3O-PRO)
* [Token and Key] (# token-e-key-de-producu% C3% A7% C3% A3o)
* [Basic Setup] (# Setting% C3% A7% C3% A3O-B% C3% A1Sica)
* [Parcels] (# parcels)
* [Uninstall] (# uninstall% C3% A7% C3% A3o)
* [For other versions] (# for-other versions)

### What is the project.
The "MoIP transparent" project was created to facilitate the purchase for the end user. The project when installed has the function of making purchase easier because it 'eliminates' the famous 'redirection'.
Benefits
Payment made totally in your e-commerce or website
The client is in the environment of your e-commerce or website throughout the purchase process, no need for registration or intermediate payment pages.

### purchase for 1 click
In the first purchase, you can choose to save your customer's credit card data. With this, the client can buy again on your e-commerce or site without typing all payment data. This feature makes the buying process much simpler and fast.

### Conversion increase of your sales
You can have an up to 30% increase in the conversion of your sales, since the number of steps your checkout will be reduced and your clients will not be directed to external pages to your e-commerce or site.

### MoIP data security
The payment data of your clients are directly directed from the browser to the MoIP. Without passing your servers, so you do not have to worry about the safety of this information.
### Requirements
** ** OpenCart: ** 1.5.1, 1.5.1.3, 1.5.2.1, 1.5.3, 1.5.3.1, 1.5.4, 1.5.4.1
** ** VQMOD: ** Yes
** ** jQuery: ** 1.7 or higher
* ** Colorbox: ** Yes

### Installation
1. Extract the MoIP.zip file to your comp1stor.
2. Copy the "Admin" folders, "Catalog", "Image", "Valdeir", "VQMOD", "System", and the "Return_MIP.php" file to the root of your store.
3. Access [http://www.seudominio.com.br/valdeir/mip/](javascript:void(0).
4. Click Install
5. Sign in with the admin user and password.
6. Fill all data

### Free version update for PRO version
* 1 - Extract the Moip.zip file to your computer.
* 2 - Copy the "Admin" folders, "Catalog", "Image", "Valdeir", "System" and the "return_mip.php" file to the root of your store.
* 3 - Access [http://www.seudominio.com.br/valdeir/mip/](javascript:void(0).
* 4 - Click Update.
* 5 - Sign in with the admin user and password.
* 6 - Access [http://www.seudominio.com.br/valdeir/mip/](javascript:void(0).
* 7 - Click Install
* 8 - Sign in with the admin user and password.
* 9 - Fill all data

### Token and Key Production
To receive the Token and Key production, your website should be homologated by the MoIP team for this just access:
* 1 - Access [https://www.moip.com.br/](javascript:void(0))
* 2 - Contact MoIP by asking for the Token and KEY production (inform your MoIP login and the URL of your application)
* 3 - After the approval you will receive an email informing your token and your production key
* 4 - After this process your website is apt to use the transparent checkout.
### token and test key
To receive the Token and Key production, your website should be homologated by the MoIP team for this is enough to register on the site:
* 1 - [http://labs.moip.com.br/login](javascript:vovoid(0)).
* 2 - After registering, log in.
* 3 - Access the Tools menu> API MOIP> Access keys.

### Automatic Return
For your client receiving the notification of the payment status automatically you need to cast your automatic return URL, so you just have access:
* 1 - [https://www.moip.com.br/](javascript:void(0))
* 2 - Go to My Data Menu> Preferences> Transaction Notification
* 3 - Mark the Receive Instant Transaction Notification
* 4 - Enter your URL in notification URL (eg: http://www.seudominio.com.br/retano_moip.php).
* 5 - Click Confirm Changes.

### Basic configuration.
* ** Status - ** Option to enable or disable the payment module.
* ** Payment ratio - ** Your company name / virtual store, will be displayed in the payment details on the MoIP website.
* ** Token - ** key In order to be able to release the module (such as receiving the token).
* ** Key - ** key In order to be able to release the module (such as receiving the key).
* ** Test mode - ** puts the module in test or in production. (For the module to enter production mode is needed token and key).
* ** Notify client - ** Notifies the client automatically when payment status is changed on the MoIP website.
* ** Authorized Status - ** Status When payment is authorized by MoIP.
* ** Status started - ** Status When payment starts by MoIP.
* ** Status Printed Boleto - ** Status When the ticket is printed.
* ** Full status - ** Status when payment is complete.
* ** Status canceled - ** Status when payment is canceled.
* ** Status under analysis - ** Status when payment is under analysis.
* ** Reverse status - ** Status when payment is inverted.
* ** Status in review - ** Status when payment is in revision.
* ** Reimbursed status ** - Status when payment is refunded.
** Geographical area - ** Geographic area where payment via MoIP is accepted. (MoIP only accepts from the Brazilian region), so do not have that option, create.
* ** Order - ** Order in which payment via MoIP will appear in the form of payment when the customer is finalizing the purchase.

### installments
The transparent MOIP Checkout module provides full flexibility and transparency for you to set up your installment rules according to the strategy and need of your business.
To accept a payment card with credit card you should access:
* 1 - Access [http://www.seudominio.com.br/admin/](javascript:void(0)
* 2 - Accessing the Extensions> Payment Menu> Click Edit next to MoIP> Soon after this select the Parcels (next to the left)
* 3 - Click Add and sets the "De *" values, "for **" and "Interest ***"
_ * The minimum number of parcel
_ ** The maximum number of parcel_
_ *** Amount of interest to that parcel group, obs: the value should be for example 1.99 | 2.66 | 7.43 or true _

In the installment settings you can inform you that you want to pass the rate of anticipation of the installment to your buyer, so ensuring that you will receive the same net value than in a transaction in sight, so you just use true in interest.

If you want to charge an additional fee for the installment purchase, but not necessarily to cover your rate of anticipation of installment, you can set the interest rate for your percentage buyer on the basis of the Price table (amortization of interest in equal parcels).

Not to charge additional value of your buyer (offer prices as "2 times without interest"), just inform the interest value to 0.00

_ ** Important: ** _ Be careful not to report conflicting installment settings. If it happens, we will treat the conflict as follows:
The configuration that accepts the least minimum amount of installments prevails over the others. Example: If you send a "2 to 7 installment" configuration and another from "7 to 12", a purchase in 7 installments will follow the settings of "2 to 7".

If the minimum quantity of installments is equal to more than one configuration, the configuration will prevail with the lowest maximum amount of installments. Example: A "2 to 7" configuration prevails over the configuration of a "2 to 12". A purchase in 6 times will use the "2 to 7" configuration instead of "2 to 12" (but a purchase in 8 times will use the "2 to 12" configuration normally)

If there are two settings with quantities of equal installments, the system will set randomly, ensuring that there is no error in the transaction.

### uninstallation.
* 1 - Access: [http://www.seudominio.com.br/valdeir/mip/](javascript:void(0).
* 2 - Click Uninstall.
* 3 - Login.
* 4 - Confirm you want to uninstall the module.
* 5 - Ready! The module has been uninstalled successfully.

### for other versions
[Access] (https://www.dropbox.com/sh/l4u1y4t292agk3n/wtpxcc3vo8)

Thanks.
Thank you all.
