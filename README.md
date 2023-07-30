# PHARMA-NET
A blockchain-based system that tracks the movement of drugs throughout the supply chain.

## Network Architecture

![](images/Network_Blueprint.png)


As shown in the image above, there are five stakeholders/organisations in this supply chain network.

 

**1. Manufacturers:** All the drug manufacturers that are registered or will be registered in the future with the network will belong to this level. For example, companies like ‘Sun Pharma’ and ‘Dr. Reddy’s Laboratories which are drug manufacturing companies will be a part of the ‘Manufacturers’ organisation.

 

**2. Distributors:** All the drug distributors that are registered or will be registered in the future on the network will belong to this organisation. These distributors will purchase drugs directly from the manufacturers. For example, companies like ‘VG Pharma’ and ‘Medico Labs’ would constitute drug distributors and be a part of the ‘Distributors’ organisation.

 

**3. Retailers:** All pharmacists or drug retailers will be a part of this organisation. The retailers will receive drug consignments from the distributors. 

 

**4. Consumers:** These are the people who purchase medicines from pharmacists. 

 

**5. Transporters:** A transporter is an entity responsible for the shipment of consignments from one point to another. For example, entities like Blue Dart or FedEx will transport the drug consignments from Manufacturers to Distributors. Similarly, if a consignment has to be shipped from a Distributor to a Retailer, a transporter will be required. 


## Workflow
The workflow required for the case study is divided into the following four units:

 

### Company Registration: 
-   All the entities who wish to be part of the supply chain network must be first registered or, in other terms, stored on the ledger. 
### Drug Registration:
-   As a part of this process, any drug manufactured has to be registered on the ledger by the manufacturing company. 
### Transfer Drug:
-   A buyer of the product will raise a Purchase Order for a particular drug.
-   The Purchase Order will be generated for a batch of drugs. It will include information like the name of the drug, the quantity required, the Buyer, etc.
-   Based on the Purchase Order, the seller of the drug will initiate the process of shipment of the drug with the help of a transporter company like ‘FedEx’, and a shipment object will be created.
-   The shipment object will contain information like the name of the transporter, origin, destination, etc.
-   Once the consignment is received by the buyer, the buyer will become the new owner of each item of the batch. 
-   If the buyer is a consumer, then the Purchase Order and the shipment process need not be initiated. Only the owner of the drug is changed from the retailer to the consumer. 
### View Lifecycle: 
-   It is the process to view the lifecycle of the asset to date. 
-   Imagine a consumer or a retailer wishes to view the lifecycle of a drug called ‘amoxicillin’ with serial number ‘medi-001’. The ‘View Lifecycle’ functionality of the smart contract will allow any participant in the network to view the entire lifecycle of the asset.


## Network Properties

![](images/Network_Architecture.png)

Let’s look at the properties of the fabric network required for the supply chain network.

<img width="587" alt="Screenshot 2023-07-30 at 1 52 50 PM" src="https://github.com/dhayalan/pharma-net/assets/121813/7ffd651f-6c20-4cc1-9e23-88d6d6fb55d9">

**Note:** There are several other attributes for the network setup that are not specified. You are free to assume the values for those attributes.

## Smart Contract Properties

<img width="746" alt="Screenshot 2023-07-30 at 2 18 28 PM" src="https://github.com/dhayalan/pharma-net/assets/121813/835d78b6-b9c2-439a-ba0e-e98d5aff0ca6">

