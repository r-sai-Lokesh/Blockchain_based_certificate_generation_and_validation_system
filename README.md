Blockchain-Powered Document Verification using IPFS:

This project endeavors to establish a robust and decentralized system for document verification leveraging Blockchain and InterPlanetary File System (IPFS) technologies. By storing document hashes on the Blockchain and the documents themselves on IPFS, the system ensures unparalleled security against tampering while facilitating easy access and verification by authorized entities.

Key Features:

Ensures secure document verification using Blockchain and IPFS technologies.
Decentralized architecture eliminates single points of failure and central authority.
Streamlined verification process without intermediaries or third-party dependencies.
User-friendly interface for seamless document upload and verification.
Supports various document types and formats.
System Requirements
Node.js and npm installation.
MetaMask Wallet integration.
IPFS client (Note: IPFS server issue is currently under resolution).
Installation Steps
Clone the repository:

bash
Copy code
git clone ....
Install necessary packages:

bash
Copy code
cd Blockchain_based_certificate_generation_and_validation_system
npm install
Launch the application in your browser using a Live Server extension.

How to Use
Begin by adding an exporter to the list of authorized parties. Click on "Add Exporter," and input the exporter's Ethereum address.

Upload a document by clicking "Upload Document," selecting the file from your computer. The document undergoes encryption and is stored on the IPFS network, with its hash recorded on the Blockchain.

To verify a document, click "Verify Document," and enter its unique identifier (hash) in the input field. The system retrieves the document from IPFS, decrypts it, and compares its hash with the Blockchain record.

The system promptly displays the document's authenticity status.


Acknowledgments
Metamask, Solidity, Web3.js, and IPFS documentations.
Insights from Truffle documentation.