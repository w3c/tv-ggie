GGIE Identity Use Cases
Many of the Use Cases GGIE has been exploring require knowledge about the content creator, the end client and the end user including identification, location, software/firmware capabilities, etc. This information, while necessary to accomplish GGIE’s goals, exposes many privacy issues that cannot be ignored. While solving these issues is out of scope for GGIE, identifying the issues and creating requirements based on them should be explored and documented. It is the competing needs for identity and identification of people and devices versus the expectation of privacy that are highlighted by these use cases. 
Definitions for Identity Discussions : 
Anonymity: The property of being not identifiable (within a set of subjects).  Anonymity serves as the base case for privacy: without the ability to remain anonymous, individuals may be unable to control their own privacy.  Unlinkability ensures that a user may make multiple uses of resources or services without others being able to link these uses to each other.  Unlinkability requires that entities be unable to determine whether the same user caused certain specific operations in the system. 
Pseudonym: A bit string which is unique as an ID and is suitable to be used for end-point authentication.
Unlinked Pseudonym: A pseudonym where the linking between the pseudonym and its holder is, at least initially, not known to anybody with the possible exception of the holder himself or a trusted server of the user.  Also called Initially Unlinked Pseudonym
Explicit Authentication: The act of verifying a claimed identity as the sole originator of a message (message authentication) or as the end-point of a channel (entity authentication).  Moreover, this identity is easily linked back to the real identity of the entity in question, for instance being a pre-existing static label from a predefined name space (telephone number, name, etc.)
Authorization: The act of determining if a particular right, such as access to some resource, can be granted to the presenter of a particular credential. Depending on the type of credential, authorization may or may not imply Explicit Authentication.
Linked pseudonym (not defined in RFC 3693): A pseudonym that can be linked to the true identity or to other pseudonym(s) of one or more people/objects, typically using a pseudonym certificate or token service.

Identity Use Cases

Identity Use Case 1: Online Anonymity
Jack is an average guy who has been using his computer and more recently his mobile devices to watch news and other info-videos, listen to music, and generally “surf the web”. He knows his online activities are being monitored by companies, hackers, foreign governments, and others. These fears are confirmed when ads show up for products and services, he has searched for and sites he has visited. He would like to be able to perform these activities anonymously – to lower his online footprint. While no expert, Jack knows that part of the task is for him to avoid providing things like his email address, name, phone number, financial information, etc., to these sites. But he also knows he can be easily targeted by information his devices send to the sites he connects to that is out of his control such as his IP and MAC addresses; and software, hardware, and app “fingerprints”. And since he does use some sites that require him to be identified, for example to make purchases, he knows that it is possible to “connect the dots” and tie the rest of his online activities to them and therefore to him or his devices. 
He would like to block any personally identifiable information (PII) that he does not consciously provide from being discovered leaving it for him to decide to when and to whom he will identify himself. 

Identity Use Case 2: Creating a Unique Identity (Pseudonym)
Building on Identity Use Case 1, Jack would like to create a pseudonym or unique identity that he can use when online. The ID would have no links to his real identity and could be deleted or abandoned at any time and replaced by a new one thereby limiting the information that anyone or any company could collect to the period during which he used it. He wants to combine the use of the ID with the ability to block unwanted personally identifiable information from being sent without his knowledge. 
Identity Use Case 3: Creating and Managing Multiple Unique Identities
Building on Use Cases 1 and 2, Jack would like to be able to easily create and manage multiple pseudonyms, each of which providing anonymity for his true identity with, in the extreme example, a new one being created for each online activity he performs. Each should also have a life expectancy with a rules-based duration determined by him so none of them can accumulate more than a small amount of information about his online activities. One might have a longer life expectancy so that while he is looking to purchase something advertisers can target ads but the accumulation of data about his activities ends when he “deletes” the pseudonym, it reaches its preset “end of life”, or other triggers. 
Although what he is looking for is an application, the tools needed to create such an application are the target of this use case.

Identity Use Case 4: Linked Unique Identities
Building on Use Cases 1, 2 and 3, Jack wants to be able to link his new unique identity(s) with information that identifies him as belonging to one or more groups, or to authenticate him as an authorized visitor to a site. For example, he is a member of several professional accounting organizations and investing sites that provide online webinars and other services and would like these sites to be able to automatically identify him when he goes to those sites while not providing his true identity. The idea is to enable them to authenticate the unique identity while maintaining his anonymity with the rest of the online world. 

Identity Use Case 5: Family use of an ExampleCo Account (Formerly UC 1)
Bob has an account with ExampleCo, a provider of books, movies and games. He creates subaccounts for his wife, his adult son and his underage children ages 5 and 8.  Bob can see the spending amounts done on the account, but there are different levels of detail about purchase that he can see depending on the privacy settings of each subaccount.
He can see all of his and his wife’s spending activity, and likewise his wife can fully see his and her activity.  Both he and his wife can see the minor children’s full spending activity. The children are only able to see their own spending.  Bob can see the amount spent by his adult son, however the son has set his privacy settings to not reveal any purchase information beyond the total amount spent so far in the current billing cycle.
Since the children are young he creates a set of rules limiting what they can spend, the types of content they can access, and other aspects of their access and use of the service. He also occasionally adds “gift card” money they receive on birthdays, and money they earn from doing chores to what each child can spend.  Bob wants his children to remain anonymous to the sellers of the content they purchase.  
Finally, Bob may want to ensure their identities are fully anonymous, even if his account were to be compromised. 
Actors: 
Primary account holder
Subaccount holder
User device (tablet, PC, smart phone, TV used to access online products and services)
Network service provider 
Network interface device(s) (cable/DSL modem, smartphone, router, etc.)
Linked pseudonym service

Identity Use Case 6: Anonymizing the Creation of Content (Formerly UC 3, revised)
John is an amateur photographer and videographer. He posts many of his creations, often for profit through contributions from viewers, advertising or by offering it for sale. Some of his work is controversial and has in the past generated vitriolic responses and even threats to him and his family. 
He would like to be able to choose when and whether to
•	link his true identity to his work 
•	link a unique identity his work
•	remain totally anonymous 
His true identity would be used to build his portfolio. A linked identity might be used to allow audiences to follow his work and to allow him to profit from those works without revealing his true identify. Multiple linked identities would allow him to target different audiences with different works. Anonymous unlinked identities would allow his to post his more controversial work without fear of having it linked to him or his family. 
Recognizing that it is not just his name that can be used to identify him, he wants to be able to control access to other PII that could be used to identify him under the various scenarios. In addition to the PII information in Use Case 1, his camera (or smart phone, etc.) may attach PII such as location, date and time, etc., to his photos and videos which can be used to tie his pseudonyms to his true identity. However, he would like to maintain the ability for this information to be recovered and used for billing or other purposes, at least in the case of linked pseudonyms. 

Identity Use Case 7: Linking Content to a Unique Identity (Formerly UC 4) 
Bob has created a number of unique videos and published them on various sites.  He decided to use a unique identity for himself, a pseudonym, for each video that he published and continued to use that unique identity when he published the video on other platforms.  Any derivative or related work should be linked to the original video and to his unique ID. He now wants to unify the social media experience – comments, likes/dislikes, related and even derivative works for each video so that viewers can view the unified social media experience for the video on a website that Bob has setup to highlight the video. In effect, each video he created, along with anything related to that video is tied to a unique identity created specifically for that body of work. 

Identity Use Case 8: Selling Content and Related Assets Linked to a Unique Identity (Formerly UC 5)
Building on Identity Use Case 4, whereby a unique ID is linked to each video and all derivative work, social media sites experiences, etc., associated with that video. A buyer has offered to buy the rights to several of his videos.  Bob now needs to bundle the videos he is selling and transfer them to the new owner. He must identify the specific videos and related assets he is selling. 
Question: Does the sale include just the video or does it include any or all related and/or derivative works, social media links, etc.? 

Identity Use Case 9: Severing Links Between Content/Related Assets and a Unique Identity (Formerly UC 6)
Building on Use Case 5, rather than sell one of the videos and related assets Bob owns, he would like to either abandon it (completely sever any ties to himself and any of his identities) or actively donate it to the public domain (create a new link to the public domain) while either leaving intact ties to either his real identity or another pseudonym for marketing purposes or completely sever all links. 

Identity Use Case 10: Severing Links to a Compromised Identity (Formerly UC 7)
Bob has an account with ExampleCo. He set up an identity (pseudonym) with ExampleCo to provide some privacy with respect to his purchases, and as an added layer of security for the associated financial transactions. ExampleCo does not have a direct link to his financial institutions. Instead Bob uses his unique ID to request payment to ExampleCo from an intermediary institution, SafePay. He has been informed that ExampleCo has been hacked and his identity information stolen. Bob wishes to abandon that ID severing all ties to it, and create a new unique ID in its place. 
Bob would also like to assign the old ID to a law enforcement agency or organization so it can be used to help track down the thief or whomever purchased it from the thief in the event they attempt to use it. 

Identity Use Case 11: Content Purchase Using Unique Identity
Julie purchases all of her movies, music, and other content from a number of online sites. She also uses several streaming services. She is uncomfortable providing her credit card or bank account information to these sites since at least one of them has been compromised in the past (that she knows of). She uses a payment service for those sites that allow it but she would like her identity and privacy to be better protected. Specifically, she would like to: 

1) use a unique identifier (pseudonym) to order content and services from the sites without providing any personally identifiable information (PII) 
2) direct her payment service to transfer payment for the purchase(s) to the content retailer or a streaming service using her unique identity for that vendor, without disclosing who she is or any financial information
3) keep her payment service from knowing any details about her purchase 
4) be able to follow up on her order in case of delivery problems or post-delivery problems. She wants to use the unique identity for follow up as well so as not to expose additional PII. 

Basically she would like to keep all details of herself from the vendor, and all details of the purchase other than the vendor and the amount to be paid from her payment service. The purchase would simply transfer funds equal to the purchase price to an account with the vendor tied to her unique identity. However, she would like her unique identity(s) to be cryptographically linked to her true identity, under her control, so she can tie the purchase and its payment to her account in case of delivery or post-delivery/warranty problems, and for legal and tax purposes. 

Identity Use Caser 12: Use of One-Time-Identifiers
A content service provider wants to provide a feature that lets their customers request content, receive a history of what they have watched, and provide them with recommendations without revealing to anyone “snooping” who the customer is or their content choices. One way to do this is to use a one-time ID for the customer and a one-time content ID for the content. The service provider might provide the one-time ID to the customer using a secure means which can be a form of cryptographic key or part of a hash algorithm that can be bound to any subsequent exchanges of content IDs. Since only the service and the customer knows the one-time ID, only they would be able to determine the true identity of the customer and content IDs being exchanged. 
