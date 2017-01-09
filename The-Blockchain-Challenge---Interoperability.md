## Interoperability – making every thing “play well together”

The only way to get ahead of the problem is to have each government take over the “prescription issuance and fulfillment” process, e.g. implement a Government Fraud Detection Solution that takes the ‘paper’ out of the hands of possible ‘abusers’ and turns the ‘last mile’ of the ePharma™ workflow process into one where paper prescriptions are not allowed at any time.

We are not putting drugs on the Blockchain (that is part of the bigger “to be” process of ePharma™; an “Automated eDrug Tracking and ePrescription Management Application”). 

We are putting the people that handle the drugs, i.e. issuance, fulfillment, and collection of medications (drugs) during this “last mile” of the prescription process, on the Blockchain!!!

Government agencies, local police departments, hospitals, caregiver and rehab clinics, pharmacies, Doctor’s offices, Ministries of Health, Economy and Interior – any entity providing oversight / licensing / regulations / services in their normal operations that would tie it in any way to medications (drugs) and / or prescriptions for those medications (drugs).

Beyond curbing abuse and increasing integrity in our drug supply, there are a number of other significant benefits that naturally flow from the abundance of data and information that will now be available to policymakers and government officials.  Reliable information about drug inventories provided on a realtime basis can save countless lives during an epidemic, natural disaster or similar event that causes an urgent need for large quantities of critical drugs.  In some areas, even hoarding remains a real issue, one that makes it difficult to maintain adequate inventories of the most needed drugs in many parts of the world.  Once again, issues like hoarding and other attempts to disrupt the distribution chain can now be stopped by government officials who for the first time will have the information necessary to prevent such abuses. 

We think it is useful to discuss a few of the decisions we made in the overall architecture of ePharma™, (ePrescribe™ - a smaller sister module).  With respect to the underlying blockchain protocol, we chose to build on Hyperledger Fabric (v.0.6) for two reasons.
  
First, this was a great opportunity to take a deep dive into a new platform for some of us, which allowed us to appreciate differences between Fabric and Ethereum, a platform which most of us have more experience using.  Second, Fabric’s built in membership services makes modeling privileges based on roles simpler for prototyping.  After researching the state of blockchain-based sovereign identity and reputation tools, there is little doubt that (uPort) is the most advanced. 

We believe there is a strong likelihood that self-sovereign identification will one day play an important role in many verification and integrity schemes.  One important observation about uPort in particular—while built on the public Ethereum network, it can serve as a source of verification for Fabric chaincode and even non-blockchain applications. This is made possible by a very flexible and modular layering of interaction that starts with a controller contract layer.  Simply put, an individual’s uPort identification can serve as a trusted oracle of information that can be utilized by Fabric chaincode.  

![uPort Stack](https://s3.amazonaws.com/epharmamedia/uPortstack.png)

As we continue to develop ePharma™ after this ePrescribe™ submission, part of our work will involve experimenting with interoperability between blockchain protocols.  Ultimately, ePharma™ can be built on any blockchain protocol, and further decisions will be made before ePharma™ is deployed for commercial use.  In the interim, however, part of the more exciting work will be in interoperability – making every thing “**play well together**”.   
