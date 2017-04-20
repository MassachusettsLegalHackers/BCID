# StonePape Explainer

StonePaper will not work without Metamask or a Etherium Node running. If you don’t know what the second one is download Metamask at https://metamask.io

Data Types

## StonePaper:

A Paper is StonePaper’s name for a document that is created on the blockchain that can never be changed. StonePaper is designed so that all documents included in the system, from ID providers, to contracts, to fingerprints, are held in the Blockchain in a Paper that can never be changed. A Paper doesn’t actually hold the information but it holds a link to the information as well as a “Hash” or “Digital Signature.” This allows a user to store their digital Identity securely either on their person, or online on a website and then user StonePaper to verify it. If the user doesn’t want anyone to know about the information all they have to do is delete all copies of the document and it’s gone… but if the information is to be public they can just load it into any cloud and the information will always be available.

### The Structure of a Paper is available below.


**string name;**                        //Document Name

**bytes32 sig;**                        //Hash of Document and Signature

**uint256 database;**                 // Number to identify the URL of the site which hold the data

**uint time;**                      // Time the document was created

**address creator;**                 // Creator of said document

**address lawyer;**                 // Lawyer who authorized said document

**uint256[] meta;**                 // All Meta data for document

**address contractLoc;**                 // Contract Location


## Briefcase:

A briefcase is the digital address where all of an individual's documents or Paper’s exist.

1.) The user is able to assign a name to their Briefcase to make it easy for people to determine who created a document. In the current demo you simply place your name in the box next to the “Your Name” button and press the button to write to the Blockchain.

2.) The user is able to go through their paper by going through the dropdown. Each Paper is stored with it’s name as the selectable characteristic.  

3.) In some cases your blockchain data will be out of date on the screen. By pressing the ‘Sync to the Blockchain’ button all data will be reloaded.
Societies:

# Societies 

Societies are structures that are used to determine if a user is part of a group or not part of a group. For example. if an organization only wanted their members to be able to sign a contract or have access to information they would use a Society.

1.) Any user can go through a Society and determine if they are part of the Society. Simply select a user by their name, choose a society and it will tell you if the user is verified or not verified.

2.) User’s can create their own society. Simply name your society and it will be created on the blockchain. Currently a user who creates a society will only be able add or remove users from the society but in future users will be able to add or remove supervisors from the project.

3.) You can add users to an Society you have created by simply choosing the society from the list, selecting the user, and  clicking add.

4.) You can remove users from a Society you have created by simply choosing the society from the list, selecting the user and clicking remove.

## Affidavit:

Affidavits are sworn documents that are placed into a user Briefcase. They are often used to prove a user identity or prove they were aware of particular information at an earlier data. A user simply titles the Affidavit in the first box, writes the Affidavit in the box below and press file to file the Affidavit in the user’s Briefcase.

## Contract Signature Traditional and Lawyer:

Contract and Signature is very traditional contract. The user titles their contract in the first box, the user then writes their contract in the box below.

The user then has the “Seller” as described in the contract sign their name below by drawing in the box with the word Seller above it.

The user then has the “Buyer” as described in the contract sign their name below by drawing in the box with the word Buyer above it.

The user then signs the contract themselves as a witness in the box with the word Witness above it.

The user can then select the Buyer’s and the Seller’s Briefcase so a version can be copied in their briefcase as well as the users.

## Contract Signature Digital Only:

Some users might want to create contracts that are signed completed digitally. This is two step process.

1.)        The user names the contract in the box “Name of Contract”

The user then writes the contract in the box below.

2.)        The user then selected the Buyer’s Brief and the 

Seller’s Briefcase. And then press  the word Draft.

*Note: In MetaMask the user will be required to write to the Blockchain “twice” for it to be successful.

The user then returns to their Briefcase and clicks on the contract this will open up a box. The user is able to then digital sign the contract from this box

 - - - - - - - - - -
 * This explainer was originally authored and released under creative commons license by Matthew Rappard of Toronto Legal Hackers who has generously made the code for StonePaper available under the MIT open source code license through a Toronto Legal Hackers GitHub repository.
 
**Creative Commons License:** This work is licensed under [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
