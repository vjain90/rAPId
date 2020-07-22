# rAPId
For NatWest API Hackathon

What is Community of Banks  project ?

Currently banks are spending lot of time and effort in collecting documents from customer and verifying the same with authenticated 3rd party. Customers at the same hand have to go through same process of providing documents again and again for different banks even though their documents are verified by an authenticated  3rd party in a bank.

Community of Banks is a concept to form consortium of banks on legal terms and condition to share the customer documents and verification details with other authenticated bank in the community to save effort and cost of verification and document collection.

How the Community of banks concept should work ?

Community of bank is meant to allow authenticated banks within a community to search for a prospect details and check if he /she is already a customer with other bank . His documents can be reused by the applicant bank and also if the bank is willing they can choose to reuse the  verification done a authenticated 3rd party for previous bank.
This solution can be  expanded to large scale landscape where customer’s documents can be shared through a secure channel among the members of community.
When a customer is onboarded in any bank , a consent can be taken for that customer if his documents can be shared with other banks for any of his engagement with them in future.


Installations : 

How to use it :  
1.	A common portal based on Microsoft Portal can be exposed to banks to search and see the customer details OR Banks can choose to use direct API < name of API>
2.	For demo purpose Microsoft Canvas app is used to build a search and retrieval mechanism.
3.	Search based on prospect basic details , Name, email id
4.	The  API , integrating multiple banks together in background will search matching result.
5.	All matching result will be shown to applicant bank with details if the prospect is a customer for any bank , its details of document verification as well .
6.	Applicant Bank can choose to request for reusing the document from the verified banks source and can also request for verification certificate from the bank to consider immediate verification and putting a Due diligence reminder after a suitable time for the prospect once onboarded.

How to prepare solution in Visual Studio:
1. Download and xtract all the following three zip files:
- ApiTest.zip
- dll1.zip
- dll2.zip

2. Copy all the dll's from both dll1 and dll2 into the follwing path "\ApiTest\obj\Release\netcoreapp2.1\win-x86\PubTmp\Out" and build the project before running. 

# rAPId
