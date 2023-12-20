## Project Polaris (BIS) working definition
The ability to make payments offline means being able to use a CBDC without being connected to the internet, either temporarily or because of coverage limitations. 
[^1]

### Offline
Not controlled by or directly connected to a computer or external network. For 
CBDC, this refers to being disconnected from CBDC ledger systems, not 
necessarily disconnected from communication networks.

### Offline payment
A transfer of value between devices that takes place without requiring 
connection to any ledger system.

### Staged offline
Where the payer and payee do not need to connect to a ledger system in order 
to exchange value, but the value exchanged is not finally settled on the payee 
until the payee connects to the ledger system. Value transferred to the payee 
cannot be spent until this second stage of online settlement has occurred.

### Offline CBDC system
A payment app or card-based payment system offered by the central bank that 
would not require a continuous connection to CBDC ledger systems.

### Fully offline system
System in which the payer and payee do not need to connect to a ledger system
(though there could be a local on-device ledger) to complete a payment, and 
any value exchanged is immediately transferred to the payee such that they can 
spend it at the end of the value transfer (settlement occurs offline). Both payer 
and payee can stay fully offline without limitation in time

### Intermittently offline system
Similar to fully offline, a system in which the payer and payee do not need to 
connect to a ledger system to complete a payment, and any value exchanged is 
immediately transferred to the payee such that they can spend it at the end of 
the value transfer (settlement occurs offline). However, risk parameters will at 
some point limit the ability of purses to transact and a purse will have to 
synchronise with the central system intermittently in order to continue to 
function.

## Digital Euro [^2]

### 'offline' mode
an “offline” mode designed to maximise certain cash-like characteristics (i.e. a 
bearer payment instrument that is not dependent on an online connection, but is 
limited to proximity payments and would need to be prefunded) and which is 
intended, subject to legislation, to offer a cash-like level of privacy for offline 
payments

The offline solution would follow a peer-to-peer validation model, where people
would be able to make and receive payments in physical proximity without the need 
to involve a PSP in the transaction. The payment would be <u>settled locally</u> (between 
the two devices) with no connection to any third party for validation or recording. The 
monetary value relating to the payment would be exchanged between the secure 
elements of the two users’ devices in accordance with the rules laid down in the 
legislative framework and the technical implementation by the Eurosystem. Any 
offline payment would require the secure storage of a certain amount of digital euro on the secure element. 

Offline holdings would be subject to a holding limit, which 
would be a subset of the total individual holding limit and applied per device. 
The offline functionality would require prefunding, for which an online connection 
would be required. Thus, provided users have prefunded their offline wallet 
beforehand, the offline digital euro could offer a fallback option when no internet 
connection is available. However, the device used for offline digital euro transactions 
would <u>still need to go online for verification of security features</u> at regular intervals. 
Offline digital euro payments would provide cash-like levels of privacy, but, just like 
cash in a lost or stolen wallet, any digital euro stored locally on a lost or stolen device 
would not be recoverable either from the Eurosystem or from the PSP.

[^1]: With Consult Hyperion. https://www.bis.org/publ/othp64.pdf
[^2]: https://www.ecb.europa.eu/paym/digital_euro/investigation/profuse/shared/files/dedocs/ecb.dedocs231018.en.pdf
