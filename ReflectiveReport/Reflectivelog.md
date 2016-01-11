Article selection:

For the reflective report assignment, I have chosen two articles that describe a method or technique for LSRE. 
  [1]	T. Gorschek and C. Wohlin, “Requirements abstraction model,” Requir. Eng., vol. 11, no. 1, pp. 79–101, 2006.

Description of RAM model:
The main aim of this model is to take care of continuous incoming stream of requirements in market-driven requirements engineering ranging from abstract level to technically detailed level.
Requirements engineering using RAM model involves three steps: 
Step1-Specify (elicit): This step involves specifying the raw requirement and eliciting enough information about it to specify a number of attributes. The main goal of this step is to get an overview of the raw requirements to the stage where the product manager understands the requirement clearly. In order to get a uniform way of specifying requirements, four main attributes are specified manually.
 1. Description: The description should not be more than five sentences and should describe the central essence of the requirement. 
2. Reason/Benefit/Rationale: This attribute consists of two parts: WHY the requirement is specified and BENEFIT of the specified requirement. Benefit should be written in the context of the subject (like user, product, and requirement’s perspective) of the requirement being stated.
 3. Risks: This attribute describes the restrictions or risks with the requirement.
 4. Title: The title should reflect the contents of requirement and should not be longer than five words. 
Step 2 (Place):
This step is centred on what abstraction level the now specified requirements resides on and involves placing the requirements on respective levels. There are four abstraction levels described in this paper.
1. Product level 2. Feature level 3. Function level and 4. Component level
The product level is the most abstract level and requirements on this level are goal like in nature i.e. not fitting the normal distribution of requirements. These requirements are abstract enough to be comparable directly to the product strategies and indirectly to the organisational strategies.
The feature level is the next level in the model. The requirements in this level are features that the product supports. It includes the abstract description of the feature itself and does not offer details as to what functions are needed to support features. 
The functional level is a repository for functional requirements i.e. what a user should be able to do and also for non-functional requirements. These requirements should strive to be testable and unambiguous.
The component level is the last level of abstraction in RAM and is of a detailed nature depicting information that is closer to how something should be solved.  The main reason for the existence of this level is that many requirements come from internal sources like engineers are on this level. It also offers a possibility to break down functional level requirements into more detail and set limits to a functional requirement.
In order to implement this step, a how-to-guide was developed and presented in this article which operates on the principle of asking a series of questions and thus guiding the initial placement of the requirement.
Action step 3- Abstraction (work-up):
This step involves abstracting or breakdown of a requirement depending on the initial placement of the original requirement. And the work-up process involves creating new requirements on adjacent abstraction levels or linking to already existing ones, depending on the situation. To perform this action, two workup rules are set. 
R1: No requirement may exist without having a connection to the product level.
R2: All requirements have to be broken down to function level.
R1 can be met in one of the two ways, through creating one or more new workup requirements or the requirement in question is linked to already existing requirements on an adjacent upper level. In this case, the requirement is abstracted upward and can be compared to the product strategies.
R2 involves the creation of several workup requirements being created. For a requirement to be detailed enough and on the right level of abstraction for this to be possible, every requirement has to be broken down to function level.
As in the case of previous step, a how-to-guide was developed to aid in the workup of requirements which shows mandatory as well as optional workup of requirements.

Reason for selection of this article: 
After going through the article, I found this model very interesting and useful to handle the continuous flow of requirements in market-driven requirements engineering. As it includes four levels of abstraction and each level is linked to the other level, the interdependencies can be handled effectively and it helps the requirement engineers to easily manage the large incoming pool of requirements. This model also offers a clear understanding of all the requirements, as several attributes are attached to each requirement. As the requirements in higher levels are linked to the lower level (component level), it helps to know whether the implementation of the requirement is possible or not and this helps to reduce the problem of over scoping and need for scope creep. I have selected this article for reflective report assignment because after reading the RAM process, I got an idea of how to implement it practically by considering an example and it seems to be interesting and very useful for me. Implementation of this model also helps me for my release planning assignment to clearly understand at which level a requirement is specified and also guide me how to add new requirements to the original requirements.

Implementation plan:
As specified in model description above, this model can be performed in three steps. It is not possible for me to implement thousands of requirements, as the implementation for this assignment should be performed individually and also limited time is available. Hence to make clear that this model is clearly understood by me, I have considered three requirements related to an online shopping website and decided to implement all the three steps of RAM model by specifying each requirement, placing them in exact abstraction levels and connecting the levels together by adding new requirements at different levels. To do this, I will follow how-to-guide aids given in the article [1]. 

Execution and proof of concept:
In order to execute the model, I have considered three requirements related to an online shopping website as:
Rq1. The user must be able to login into the system before the usage of product. 
Rq2. The product is targeted towards markets of several countries.
Rq3. There should be a facility to track the products ordered by the users.


Step 1(Specify):
In this step, each requirement should be specified using four attributes: Description, Rationale/Benefit, Risks and Title.
Requirement:              Rq1          
Description:              The user must be able to login into the system before the usage of product.
Reason/Rationale/Benefit: Unauthorized users should not have access to the product functionality.                   
Title:                    Login functionality.

Requirement:              Rq2          
Description:              The product is targeted towards markets of several countries.
Reason/Rationale/Benefit: Many users don’t understand English and prefer the system be in their                                                         native language and it makes usage of the system more comfortable and attractive.
Risk:                     It may result some problems with user interface logic.                   
Title:                    Multiple markets

Requirement:              Rq3          
Description:              There should be a facility to track the products ordered by the users.
Reason/Rationale/Benefit: It helps the users to know when would be the product delivered and has a positive effect on                                   usability of the system.                   
Title:                    Tracking of shipments

Step2 (Place): 
To place the requirements into their abstraction levels, how-to-guide aid provided in the article is used:
The first question is if the requirement is functional or not, or if the requirement is testable. This applies to Rq1 as it includes the function of logging in into the system and is testable. But none of the other two requirements satisfy these questions. Hence Rq1 is placed in function level of abstraction. 
The next question is if the requirement consists of a specific suggestion of how something should be solved. None of the selected requirements satisfy this.
The next question is if the requirement is comparable to the product strategies. Rq2 is directly comparable to the product strategies and is at most abstract level of description. Hence it is placed in product level of abstraction. But Rq3 is more detailed and is not directly compared to the product strategies.
The next question is if the requirement describes what a system should include/support. Rq3 describes that the product should support tracking. Hence Rq3 is placed in feature level of abstraction.

Step 3 (Abstraction): 
After placing the requirements in their abstraction levels, the two rules R1 and R2 must be satisfied by adding new requirements. The addition of requirements is done by following the guidelines specified in how-to-guide aid.

For Rq1:
As Rq1 is in the function level of abstraction, requirements should be added for product level, feature level and component level. The addition is done as follows:
Product level: 
Secure product- The system should be able to prevent unauthorized use. 
This requirement is the most abstract form of Rq1 and is directly linked to the product strategies. Hence it is added to the product level of abstraction.
Feature level:
Personal profile- Users in the system shall have a personal profile.
This requirement specifies what a system should include and hence it is added to the feature level of abstraction.
Component level:
Successful Login- When a user has successfully logged in, the product shall display the users’ personal profile page.
Incorrect Login- If user enters an incorrect user id and/or password; the login page shall be reloaded with information showing that incorrect login has been performed.
These requirements are in more detailed form and describe how an action should be performed. Hence it is added to the component level of abstraction. 

For Rq2:
As Rq2 is in the product level of abstraction, requirements should be added for feature level, function level and component level. The addition is done as follows:
Feature level:
Support different languages- The system is able to provide information in different languages.
This requirement specifies what a system should include and hence it is added to the feature level of abstraction.
Function level:
Select desired language- The system must allow users to change the language using a button.
This requirement includes functions of the product and hence it is included in the function level of abstraction. 
Component level:
Language not available- The system must provide an error message if the language selected is not available.

For Rq3:
As Rq3 is in the feature level of abstraction, requirements should be added for product level, function level and component level. The addition is done as follows:
Product level:
Status of ordered products- The system is able to provide status of the ordered product.
This requirement is the most abstract form of Rq3 and is directly linked to the product strategies. Hence it is added to the product level of abstraction.
Function level:
Allow users to enter information for tracking- The system must allow users to enter the order information for tracking.
This requirement includes functions of the product and hence it is included in the function level of abstraction. 
Component level:
Contents of order information: The order information should include the id of the product and the destination.
Contents of tracking information: The displayed tracking information should include date of order, destination and current status of shipment. 
These requirements are in more detailed form and describe how an action should be performed. Hence it is added to the component level of abstraction. 

After the completion of abstraction process, each requirement should be attached with other attributes include requirement source, requirement owner, requirement manager, relation/ dependency, state, reject reason, due date, version, date of creation and last changed. 

Lessons learned:
From this article, I have concluded that the flow of requirements in market driven requirement engineering is continuous through the product development life cycle. Improper handling of these requirements results in the failure of the product to meet the needs of market. The incoming requirements come in different abstraction forms and with different levels of complexities. This should be handled effectively as it leads to the development of inappropriate and infeasible requirements and hence such type of requirements should be removed in middle of the development which results in wastage of effort and money. Several interdependencies exist among different requirements and these dependencies must be handled carefully before early stages of development. 
Through the implementation of this model, I observed that each requirement is clearly understood by me and, its causes, benefits and possible risks of each requirement are known. The addition of new requirements in relation to the available requirements became easy and clear, as the requirements are added to distinct abstraction levels. I got a clear idea of how requirements in MDRE are handled, implemented and divided into different releases. This method also helped me to know how dependencies can be handled in the companies practically. I gained knowledge about the challenges faced in handling and placing the requirements in different levels. At the beginning I am confused to take decisions in placing and adding the requirements, but how-to-guide aids helped me to avoid this confusion. However some of the decisions taken by me may be not exact as this is the first time for me to read and implement RAM model. But most of the decisions taken by me are analysed and presented along with reasons.  

Reflections:
In order to compare my work experiences of this implementation, I referred article
  [2]	T. Gorschek, P. Garre, S. B. M. Larsson, and C. Wohlin, “Industry evaluation of the requirements abstraction model,” Requir. Eng., vol. 12, no. 3, pp. 163–90, Apr. 2007.
The authors of this article performed case study in two companies by implementing RAM model on their company products and gathered opinions of both the companies about the implementation of this model. The results indicate that implementation of RAM at both these companies has yielded substantial increase in both accuracy and quality of requirements. But the costs and efforts of implementation are increased due to implementation of this process. However as there is increase in the levels of accuracy and quality, it is obvious that the cost and effort should be spent more in order to acquire benefits. And this increase is very moderate in total and can be handled by both the companies. This model is tailorable, maintaining    certain concepts (use of abstraction and attributes) but adaptable enough to fit different environments.  RAM is tool independent, but requires tool support to be scalable and practical. The two companies are developed companies and so it became easy for them to handle the requirements using this model. Through my experiences, I felt the same that handling such a large number of requirements increases cost and effort for the implementation. And since I have considered only three examples it is easy for me to implement this manually, but as MDRE process includes thousands of requirements implementation of this model requires tool support for sure. However the observations through case study may not be accurate as this observation is short term and problems may also arise in later stages of the product development.

Article 2: R. B. Svensson, T. Olsson, and B.Regnell, “Introducing support for release planning of quality requirements - an industrial evaluation of the QUPER model,” in 2008 Second International   Workshop on Software Product Management, 9 Sept. 2008, pp. 1-9.

Description of application of QUPER model:
Quality performance (QUPER) model supports release planning and road mapping of quality requirements.
This paper includes application of QUPER model for quality requirements through the following steps:
1. Identify candidate QR: In this step, quality requirements are identified and the consequences (relevant features, market segment, competitor and hardware platform capability) for that quality requirement is considered.
2. Define scale and unit: This step includes the defining a scale and a measurement unit which is used to express the level of quality of QR.
3. Identify reference levels: In this level, identification of reference levels is done for each QR based on actual products. These reference levels can be based on competing products as well as own products. 
4. Elicit quality breakpoints: After the identification of all the reference levels, the market expectations should be defined in terms of the values of quality breakpoints (utility breakpoint, differentiation breakpoint and saturation breakpoint).
5. Estimate cost barriers: This step includes the estimations of cost in terms of cost barriers (CB). Although it is possible to identify and estimate one, two, or several CB for each QR, the recommended number of CB is two. 
6. Set candidate requirements: This step includes estimations of proposed candidate requirements, and decides actual requirements for coming releases, where estimates can be given in three forms. One way to specify a requirements quality interval is by using both a Good and a Stretch target.
7. Identify cost dependencies: This step includes the identification of potential cost barriers. 
Reason for selection of this article: 
As the QUPER model was developed with the aim to support high level decision-making in release planning of quality requirements, it helps the market-driven software products to plan their product releases effectively. This helps them to deliver the products to market as early as possible with a competitive level of quality compared to its competitors’ products. And QUPER is the only method which addresses both the quality and cost constraints of QR. In this paper, in addition to the description of how to apply QUPER model in practice, an extra step i.e. cost dependency step is also added. This helps to effectively handle the cost dependencies between the QRs in practice. I have selected this article for reflective report assignment because after reading the application of QUPER model, I got an idea of how to implement it practically by considering an example and it seems to be interesting and very useful for me. 

Implementation plan: As specified in the description of application of QUPER model above, this model can be performed in seven steps. To make clear that this model is clearly understood by me, I have considered two quality requirements related to the Automated money machine (AMM). This system takes a user transaction as input and sends the information to the central bank account system and receives acknowledgement that the transaction has been processed and responds to the user. And I decided to implement all the seven steps of QUPER model by specifying each quality requirement, determining the reference levels by identifying the competitors’ current position and determining the costs and cost dependencies of each quality requirement. 

Execution and proof of concept: 
In order to execute the QUPER model, I have considered two quality requirements related to AMM and all the seven steps are performed on them.

Step 1: Identify candidate QR:
QR1- A competitor recently launched an AMM system with response time of 8 seconds for the requests of the users. 
QR2- A competitor recently launched an AMM system with Mean Time to Repair (MTTR) within 2 hours. The MTTR is defined as the sum of the time required for fault isolation, correction and restoration to service for each failure divided by the number of failures. 

Step 2: Define scale and unit for each requirement:
QR1: 
Scale- Time
Unit-   Hours
QR2: 
Scale- Time
Unit-   Seconds

Step 3: Identify reference levels: For the two QRs, two reference levels are considered based on competing products. All the values are imaginary.

QR1:
Feature: AMM system response time.
Quality Requirement: Time to respond to the banker requests.
Definition: Number of seconds required by AMM system to respond to the banker requests.
Reference levels:
PRODUCT: Competitor X LEVEL:  20 seconds
PRODUCT: Own product Y LEVEL: 15 seconds
PRODUCT: Competitor Z LEVEL:  8 seconds

QR2:
Feature: Mean time to repair the AMM machine if there is any failure.
Quality Requirement: Mean Time To Repair (MTTR).
Definition: Mean number of hours required to repair the system. 
Reference levels:
PRODUCT: Competitor X LEVEL:  5 hours
PRODUCT: Own product Y LEVEL: 4 hours
PRODUCT: Competitor Z LEVEL:  2 hours

Step 4 - Elicit quality breakpoints:
There are three types of quality breakpoints specified in the QUPER model:
Utility breakpoint: It is the lowest acceptable value on the market for a given segment.
Saturation breakpoint: Representing quality levels that are clearly considered excessive by the market.
The differentiation breakpoint: It is determined somewhere between utility and saturation. Values above this quality level gives market advantage compared to the current products of your competitors.

QR1:
Utility: 30 seconds                       
Saturation: 1 second                   
Differentiation: 10 seconds   

QR2:
Utility: 10 hours
Saturation: 0.5 hours                  
Differentiation: 3 hours

Step 5 - Estimate cost barriers

For this example, two cost barriers were identified. First cost barrier is related to software changes and the second cost barrier is related to new hardware components.

QR1:
Qref 1: 15 seconds
Q11:  9 seconds Rationale: new SW architecture needed
C11: 2 weeks
Q12: 4 seconds Rationale: new HW component needed
C12: 6 weeks

QR2:
Qref 2: 4 hours
Q21:  3 hours Rationale: new SW architecture needed
C21: 4 weeks
Q22: 1.5 hours Rationale: new HW component needed
C22: 10 weeks

Step 6- Set candidate requirements
Target:

QR1:
GOOD: 7 seconds Rationale: will beat most of the competitors
STRETCH: 5 seconds Rationale: if SW architecture is feasible

QR2:
GOOD: 3 hours Rationale: will beat most of the competitors
STRETCH: 2.5 hours Rationale: if SW architecture is feasible

Step 7- Identify cost dependencies.
I assumed that QR1 and QR2 are dependent to each other i.e. both of them affect the same architectural part and by clearly analysing the cost estimates and importance of both the requirements, I decided to implement QR1 as it is most important and requires less cost when compared to QR2 and effort estimations are made to it in terms of weeks and months. However, in real projects’ context cost dependencies of several QRs are determined and an expert of the company take decisions of selecting a subset of dependent QRs that are easy to implement than the other dependable requirements. Then the effort estimates are calculated for all the requirements in the subset and changes are made by the expert, if obtained effort is higher than the available resources.

Lessons learned: 
From this article, I have concluded that the organisations often face many challenges to set the right quality for requirements in relation to future market demands and competitor products. The organisations operating on market-driven software product development should plan the product’s releases effectively so that they can reach the market as early as possible with a competitive level of quality compared to the other products and hence quality requirements can be seen as a key competitive advantage in companies. 
Through the implementation of this model, I got a clear idea of how the quality requirements are specified and how to compare the quality of our own product to the quality other products produced by the competitors. This implementation also helped me to know how to reach the future state from the current state of the product by improving its quality. I also got a clear understanding of the importance of cost, benefit and roadmap view of the QUPER model and the importance of considering cost dependencies while selecting the requirements to different releases. I feel that the application of this model is easy and it gives a clear understanding of how to implement quality requirements practically.

Reflections:
 In order to compare my work experiences with others, I have selected and gone through another article.

[4]  R. Berntsson Svensson, Y. Sprockel, B. Regnell, and S. Brinkkemper, “Setting quality targets for coming releases with QUPER: an industrial case study,” Requir. Eng., vol. 17, no. 4, pp. 283–98, Nov. 2012.

 The authors of this article conducted case study and evaluated QUPER model practically. Based on their observations, the overall result indicated that QUPER is relevant to early decision-making process and the concepts of breakpoints, competitor analysis, cost barriers and identification of own products quality level provides a greater understanding of the needed level of quality for coming releases. This paper identified two main challenges by using QUPER in practice.
1. Difficulties to identify and specify the values for the differentiation and saturation breakpoints.
2. Difficulties in identifying the cost barriers and their values.
 In my view, the observations derived from my implementation and the observations of the authors of this paper are almost same. However, coming to the discussion of the challenges faced by the authors relating to the identification of values for breakpoints and cost barriers, it is not possible for me to draw exact conclusions about them because I have considered only two quality requirements and all the values taken by me are imaginary. But by referring to this article, I got an idea of difficulty level of identifying these values practically.  
