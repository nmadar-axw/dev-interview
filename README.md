## Axway Romania Developer Interview

Your task for today will be to design and implement a **REST API** over **two** collections. The collections will be defined as follows: one **'buyers'** collection and one **'transactions'** collection.
Buyers will be defined as being of **two types: corporate and individual buyers**. 



For the individual buyer, you must include at least the following fields:

id: Id

buyerName: String

value: Numeric (sum of all transaction values)

dateRegistered: Date

buyerPersonalIdentification: String

transactions: Array<Id>



For the corporate buyer, you must include at least the following fields:

id: Id

buyerName: String

value: Numeric (sum of all transaction values)

address: String

companyIdentification: String

transactions: Array<Id>


The transactions will be defined as follows:

id: Id

transactionNumber: Numeric

value: Numeric

description: String


**Tasks**:
1.	You are supposed to fully implement all CRUD operations on these collections. 
2.	For the 'buyers' collection you must ensure that no duplicate buyers can be inserted
(hint: filter by 'buyerName'), and deleting a buyer must ensure the complete deletion of all transactions associated to it.

**Bonus round**: 

Sketch an HTML + Javascript interface that can call and display the results from at least one endpoint.
