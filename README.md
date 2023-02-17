#Whitepaper

#DocuMed: A dApp for storing medical records that can be access by everyone while remaining maximum privacy

Composted by
Nicholas Wong Zi Loong, Tay Hui Yee, She Jun Yuan, Teoh Mae Kay, Bernard Ong Yuzhe

#Abstract

DocuMed is a decentralized application (dApp) that utilizes blockchain technology to securely store medical records while ensuring maximum privacy for users. The dApp uses standard blockchain encryption methods and Soulbound Tokens (SBTs) to verify and ensure that users are linked with their medical records. When signing up, users provide their thumbprint and DNA details for identity verification. The medical records stored on DocuMed are available for public access, but personal data is only revealed when authorized by the individual. In case of emergencies, hospitals may override the access of a potentially unconscious individual. Participating hospitals need to have funds locked up on the blockchain, and if the override of personal information is not justified afterwards, the funds will be transferred from the defaulters to the individual whose personal information was exposed. With DocuMed, patients have full control over their medical records, which can be easily accessed by healthcare providers with the patient's permission. As more hospitals adopt DocuMed, it will ensure secured shared medical profiling wherever you go. The use of SBTs and blockchain technology ensures the security and privacy of the records, making it an attractive option for those who value privacy and security in healthcare. 

#Problem Statement

There are several problems with the current system of medical records, which are mostly paper-based or stored electronically in disparate systems. Here are some of the main issues:

1.	Fragmented Data: Medical records are often fragmented due to the lack of a centralized system for storing patient data. This fragmentation can lead to inaccuracies, inconsistencies, and errors in diagnosis, which can ultimately lead to improper treatment. For instance, a patient's medical history from different providers may not be available to a physician in case of an emergency, resulting in ineffective treatment. (Dietsche, 2023)

2.	Privacy and Security: Medical records contain sensitive personal and health information, making them a prime target for cyberattacks. Current medical records systems often lack sufficient safeguards to protect patients' sensitive health information, which can result in data breaches, identity theft, and other security risks that compromise patient privacy. Data breaches in medical records can lead to a loss of trust between the patient and healthcare providers. (Just a Moment. . ., n.d.)

3.	Lack of Interoperability: The lack of interoperability between different medical records systems can result in redundant tests and procedures, delayed care, and increased costs. For example, if a patient visits a new provider or hospital, they may have to repeat medical tests that have already been performed, which can result in unnecessary costs and prolonged treatment. (2021)

4.	Inefficient Processes: Paper-based medical records and outdated electronic systems can lead to slow and inefficient processes for healthcare providers, which can result in longer wait times for patients and delayed treatment. Patients may also face difficulty accessing their own medical records, which can make it difficult for them to manage their own health effectively. (Adler, 2008)

5.	Limited Patient Access: Patients often have limited access to their own medical records, which can make it difficult for them to stay informed about their own health and take an active role in their care. This can result in poor outcomes and lower quality of care. (Just a Moment. . ., n.d.-b)

6.	Cost: Traditional medical records systems can be expensive to maintain, especially for smaller practices or hospitals, which can lead to higher healthcare costs for patients. The cost of updating or migrating to a new system may be prohibitive for some healthcare providers, resulting in a continued reliance on outdated systems. (Gallego et al., 2010)


Overall, these problems with current medical records systems highlight the need for more modern, secure, and interoperable solutions that prioritize patient privacy and provide patients and healthcare providers with easy access to accurate and complete medical information, which is what we are trying to achieve with DocuMed.

#Product Overview

#Functions of DocuMed

DocuMed is a decentralized application (dApp) that is built on the Polygon blockchain. It uses blockchain technology to ensure all users data are stored in the network and will not be fragmented as all user profile and medical records are stored on a public network and allows access from any parties (hospitals, clinics, research facility etc.) when user grants permission. Next, by building on Polygon, we can ensure high standards security and as it uses advanced consensus algorithms, such as Practical Byzantine Fault Tolerance, Variable Resonance, and EOS consensus. (Polygon (MATIC ERC-20) Mobile Wallet, 2023) While absolute privacy can be ensures as only the user and the parties that the user grants permission are able to view their medical records and personal information. Moving on, DocuMed is compatible in all of the hospitals that adopt it as their medical record database and uses the received data to generate standardized electronic health records (EHR), electronic medical records (EMR) and personal health records (PHR) to ensure maximum interoperability with different health institution. Furthermore, by utilizing Polygon, access of data will be almost instantaneous as to not delay any treatment processes and ensuring maximum efficiency. Last but not least, by having a user oriented dApp, all medical records and information will be readily available for their viewing. The cost of using DocuMed is relatively low compared to traditional medical record system.

#Process of Setting Up a DocuMed Account

With DocuMed, users can easily create or import a wallet, which will come with a SoulBound Token (SBT) that serves as their digital identification card. The SBT is generated only once for each user, and it serves to authenticate the user's identity across the platform. To use all services on DocuMed, users simply need to visit any hospital that uses DocuMed and present their government-issued ID card and provide their fingerprints, this is a one-time process and doesn’t need to be redone after confirmation of credentials. These details are then linked to their SBT, which ensures that no one can create another profile with the same ID card and fingerprints.



#DocuMed for Health Institutions

DocuMed for hospitals, clinics or any other health institutions is a little bit different than users, the participating institution will need to stake a certain amount of $DMT (DocuMed Token) to be able to use the emergency feature, which would grant them access to some user’s personal information and medical records under certain circumstances (more about this will be shown in Game Theory under Technical Overview).

#Polygon Blockchain

One of the many reason that we want build our DocuMed on Polygon is because it leverages Ethereum's technology and adds more value to it. Firstly, Polygon offers us higher throughput and low-cost transactions, which is attractive for us as developers who want to create dApps that require fast and affordable transactions. Additionally, using the Polygon platform can increase the flexibility, scalability, and sovereignty of our blockchain project while still retaining the security, interoperability, and structural benefits of the Ethereum blockchain. This allows us to create more efficient and functional dApps that can support a wider range of use cases. Furthermore, the unique viability of Polygon in supporting dApp development makes it a popular choice among developers looking to build on the Ethereum ecosystem and various Ethereum-compatible blockchains. (Takyar, 2022) Overall, building on Polygon can offer us several advantages that can help us create better and more effective blockchain-based solutions. (What Is Polygon (MATIC)? Definition, Strengths, and Weaknesses, 2022) 

#Technical Overview

#DocuMed Token ($DMT)

A token named $DMT will be minted on the blockchain and be use as an instrument for the below mentioned Game Theory to work. The distribution of said tokens are as follows:
-	Development team: 20%
-	Early investors (ICO): 20%
-	Advisors: 10%
-	Community: 30%
-	Reserve fund: 20%

#Game Theory

In order to let all the actors act responsible in using DocuMed, a monetary incentive will be implemented to ensure the system will be able to work as intended and reduce the likelihood of bad actors to perform malicious actions that would cause unfairness to other actors and/or the whole community. As health institutions such as hospitals or clinics will have the option to access user’s data in an emergency, they might exploit this by using this data for malicious activities and this feature would greatly lower the privacy levels for an individual user. Hence, for any institutions to gain access to this emergency feature, they will be required to stake a certain amount of $DMT to be able to access it. Let a scenario where Alice is an unconscious patient being sent to the nearest Hospital B where she had never gone before (no medical records accessible). If the Hospital B decides to use the emergency feature of accessing Alice’s medical records and personal information without her consent, they will be required to scan Alice’s fingerprint and they will be granted access. Simultaneously, once her information is disclosed to Hospital B, a portion of Hospital B’s stake amount of $DMT will be locked up until Alice can access her account and sign a transaction that allows the locked-up fund to be return to Hospital B if Alice thinks that Hospital B is appropriate to access her privacy under the emergency circumstances. Likewise, if she thinks that it is against her will to share her information, she may sign the transaction to have the locked up funds to be transferred to her instead of Hospital B, but if Alice does decide to do that, she first will need to match the amount to be locked in on the blockchain, after that Hospital B will be prompt to provide evidence to prove her wrong, and the evidence will be posted on chain for $DMT stakeholders to vote for. The side with majority of the votes will receive the total locked amount and the voters will get a small amount of the locked amount.

In a nutshell, this mechanism will prevent any bad actors from either abusing their ability to violate user’s personal information (institutions) or trying to get a monetary edge from exploiting institutions (users). 
 
#References 

Adler, K. G. (2008, December 31). E-prescribing: Why the Fuss? AAFP. https://www.aafp.org/pubs/fpm/issues/2009/0100/p22.html
Dietsche, E. (2023, February 8). Are tech companies making healthcare fragmentation worse? MedCity News. https://medcitynews.com/2018/05/healthcare-fragmentation/
E. (2021, August 25). Interoperability in Healthcare. HIMSS. https://www.himss.org/resources/interoperability-healthcare
Gallego, A. I., Gagnon, M. P., & Desmartis, M. (2010). Assessing the Cost of Electronic Health Records: A Review of Cost Indicators. Telemedicine and E-Health, 16(9), 963–972. https://doi.org/10.1089/tmj.2010.0014
Just a moment. . . (n.d.-a). https://www.sciencedirect.com/science/article/pii/S1110866520301365
Just a moment. . . (n.d.-b). https://patientengagementhit.com/features/how-patient-health-data-access-drives-patient-engagement
Polygon (MATIC ERC-20) Mobile Wallet. (2023, January 31). ZenGo. https://zengo.com/assets/polygon/
Takyar, A. (2022, September 26). How to Build a dApp on Polygon? LeewayHertz - Software Development Company. https://www.leewayhertz.com/decentralized-app-on-polygon/
What Is Polygon (MATIC)? Definition, Strengths, and Weaknesses. (2022, September 22). Investopedia. https://www.investopedia.com/polygon-matic-definition-5217569

