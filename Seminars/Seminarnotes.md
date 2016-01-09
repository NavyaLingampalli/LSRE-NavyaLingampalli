Homework:

Seminar 0:

What is large-scale requirements engineering?

The explosion of new ideas is particularly an evitable part of a company that operates in Market Driven Requirements Engineering (MRDE). Hence there is a need for these companies to often manage hundreds and thousands of requirements arriving from multiple sources. These requirements are inter-related with increasing number of customers, end users, developers, subcontractors, product features, and external system interfaces collectively known as stakeholders. This context is defined as large-scale requirements engineering (LSRE) or very large-scale requirements engineering  (VLSRE)[1].

What are the challenges in large-scale requirements engineering?

Major challenges in large-scale requirements engineering are specified below [1] [2]. 
•	Ill structured problems:Some design methods  require that engineers formulate the requirements and solutions 
        separately and independently, but this is impossible if design problems are ill-structured. The main characteristics
        of an ill-structured problem are that the solution space is not well-defined and there is no criterion to test
        different solutions and decide which is best.
•	Uncertain environments:Uncertainty comprises both external and internal elements. External uncertainty includes
        changes in the market, the operating environments, business processes, and threats. Other elements include emerging
        requirements/expectations, changes in priorities, emerging competitors (including users) and introducing new
        technologies. Internal uncertainties include program/project execution as well as design, implementation, and
        performance challenges. 
•	Shifting goals:As there is a continuous flow of requirements from multiple stakeholders, there is a chance of shifting         from the goals which leads to the failure of project as the customer needs will not be met.
•	Resource allocation:It is very challenging to allocate resources for such a large pool of requirements. Inapproriate          allocation of resources to any requirement leads to many problems.
•	Multiple stakeholder situations:As the field of large scale requirements engineering deals with huge markets and large         number of users, multiple stakeholders come into play and needs of all the stakeholders must be met and establish             proper communication must be established among them.   
•	Incompleteness of the available information:
•	Finding right balance between selecting commercial requirements and internal quality requirements:
•	Requirements prioritization: As in the case of large scale requirements engineering, it is not possible to meet all           the requirements by considering available time and budget of the product. Hence suitable prioritization technique is          to be chosen in order to satisfy the needs of customer and users, and also to minimize cost and time of the project.
•	Complex dependencies between requirements: 
•	Multi-objective decision problems:
•	Informal Communication:
•	Managing requirements interdependencies:As there is a large pool of requirements, quite number of interdependencies           will be there between several requirements. These interdependencies must be handled carefully and should be properly          selected to different releases. 
•	Cost estimation: As the large scale requirements engineering includes continuous flow of requirements, it is difficult         to know which requirements should be included in relation to the cost estimations. The selected requirements should be         in such a way that the budget of the project should not be exceeded. And it is also challenging to determine cost             estimations exactly as there will be many dependencies between the requirements.

What is the order of magnitude of the number of requirements we are discussing?

The table below shows the orders of magnitudes in requirements engineering [3].
			
	Small-Scale Requirements Engineering	      ~10 requirements
	Medium-Scale Requirements Engineering	      ~ 100 requirements
	Large-Scale Requirements Engineering	    	~1000 requirements
	Very Large-Scale Requirements Engineering		~10000 requirements

Read up on and summarise [Strategic] Release Planning.

Strategic release planning is one of the most important parts of the requirements engineering process and is performed at the product level.  “The idea of selecting an optimum set of features or requirements to deliver in a release within given constraints is called strategic release planning or road-mapping”.  The main purpose of release planning is to balance the stakeholders’ demands according to available resources. It is one of the complex problems, as it requires understanding of planning objectives and other constraints. The release plan is refined and re-planned after the execution of each release. It is one of the important task to be performed in both bespoke and market driven products. In the case of bespoke products, it is useful in the selection of most valuable requirements of a customer in the first release and reduces the importance in future releases. And in the case of market-driven products, the importance of release planning is very important and it helps in deciding which customer will get what requirements and in which release.  There are several approaches to develop strategic release plan. Two basic approaches include 
1.	Ad-hoc planning
2.	Systematic planning
These two approaches are discussed in detail in the summarization of article [4] below.

Summarization of [4] (G. Ruhe and M. O. Saliu, “The art and science of software release planning,” IEEE Softw., vol. 22, no. 6, pp. 47–53, Nov. 2005.):

The authors of this paper mainly concentrated on the advantages of release planning, what should be contained in release planning, difficulties in creating it and presented two approaches of RP namely 

1. Art of RP approach: Which relies on the human intuition, communication and capabilities which can address RP’s implicit and tactic aspects. Mainly agile development practices use this approach as it includes physical meetings between different stakeholders and relies on their effort. However it has its own disadvantages in few cases such as if the number of features and stakeholders is very high. Hence this approach doesn’t provide guidance on how to decide on features and priorities in the case of involvement of multiple stakeholders and it do not techniques to balance the conflicts that may arise between multiple stakeholders. 

2. Science of RP approach: This is a formal approach unlike art of planning which is based on the belief that the problem can be formalized and results can be obtained by solving it. And the authors discussed about two approaches, which have modeled the problem as a specialized optimization problem. And this articles also discussed about the formalization of RP aspects using adhoc methods that include 
1. Penny’s approach and 
2. Incremental Funding approach (IFM)
But all these approaches have their own disadvantages.

In this paper, a formalization method is presented by integrating both human and computational intelligence to define optimal feature assignment releases and it offers greater flexibility in the number of releases. And only 2 releases are considered in this paper for simplicity. For this, the authors considered a feature set  (F) which relate to new functionalities, customers’ change requests or defect corrections and these are to be released to K release options and a set decision variables.  In order to allocate the features to the releases, two types of dependencies between the features are identified as 
1) Coupling relation (C) in which features should be released jointly and 
2) Precedence relation (P) in which features are released in certain order.
For the feature realization, resource constraints were considered and capacities available for each resource type and proposed an equation that must be satisfied for all the releases and resource types. And as the stakeholders are very important in planning of any product, they are considered based on their importance as per an ordinal nine-point scale. Also the feature prioritization is considered in relation to value and urgency using nine-point scale. Two releases are considered in this paper and each stakeholder has nine votes for each feature and has three possible options. Based on these, few assumptions are made and according to them the objective is set as to maximize F(x) function and dependency constraints are also given. As this formulation constitutes a specialized integer linear programming problem and all the objectives stated are linear functions and decision variables are integers, it differs from simple spreadsheet calculations and support further a series of elementary arithmetical operations.  This approach finally formulates a series of problems as variants and these are solved to generate set of qualified alternative solutions. And a human decision maker such as project manager based on his/her experience and familiarity evaluates these solutions. Hence this method includes both human intelligence and computational intelligence that offers a high-level framework. And this paper further extended the approach by performing a variety of tasks during three phases of the planning process. And a sample problem is explained clearly to illustrate the proposed approach.

Summary of article [5] (R. B. Svensson, T. Olsson, and B.Regnell, “Introducing support for release planning of quality requirements - an industrial evaluation of the QUPER model,” in 2008 Second International Workshop on Software Product Management, 9 Sept. 2008, pp. 1-9.)
The authors of this article argue that in market-driven product development and release planning, it is important to find the balance between competing quality requirements. Lack of good release planning may result in unsatisfied customers and market loss. Very less research is looked into prioritization of the quality requirements in release planning which is very important to be considered especially in the case of market-driven product development. Hence this paper presents a quality performance (QUPER) model which supports release planning and road mapping of quality requirements and it also presents one case of QUPER tailoring, implementation, and most important evaluation, conducted at Sony Ericsson. The main purpose of this is to investigate the implementation of QUPER in industry.
This paper includes a detailed explanation of QUPER model. This model was developed in three main steps: 

 Step 1: Problem definition. Aim of this stage is to understand different requirement decision scenarios and the need for a cost-benefit model including quality aspects to support road mapping and scoping was identified.
Step 2: Model definition. This is based on the input from step 1. And it includes three types of views.
 1. The QUPER benefit view: It includes three breakpoints indicating principal changes in the benefit level with respect to user experience and market value. 
i) The utility breakpoint represents the border between a quality level useless and useful quality.
ii) The differentiation breakpoint represents the shift from useful to competitive quality, which makes them have a competitive market proposition.
iii) The saturation breakpoint imply a change in quality level from competitive to excessive quality, where higher quality levels have no practical impact on the benefit in the particular usage context considered.
2. The QUPER cost view includes the notation of cost barriers that represents the non-linear relation between quality and costs.
3. The QUPER roadmap view combines the benefit and cost views by position the breakpoints and barrier together ordered on the same scale.
Step 3: Model validation. This includes evaluation of the model which is generally carried out through interviews and expert decisions.
The implementation of these steps is carried out in Ericsson and evaluation is done for only benefit view because it is considered the most important part of the QUPER model for Sony Ericsson to start with. This is done in 4 steps
 1. Define quality aspects.
2. Estimate your product’s current quality and the competing products’ quality.
3. For each quality aspect and for each relevant qualifier, estimate the breakpoints.
4. Estimate candidate targets and discuss and decide on actual targets for coming releases.
And this paper includes detailed description of practical application of QUPER model by conducting interviews and involving experts of the company. The results indicate that the quality performance model provides helpful information about quality requirements in release planning.

Summary of article [6] (R: Berntsson Svensson, B. Regnell (2015) “A case study evaluation of the guideline-supported QUPER model for elicitation of quality requirements”, 21st International Working Conference on Requirements Engineering: Foundation for Software Quality (REFSQ’15),Essen, Germany, pp. 230-246, 2015.)
The authors of this paper argue that the release planning is very important for market-driven software product development organisations operating on a competitive open market. And it is more advantageous when the level of quality of the product is compared with its competitors’ products and hence quality requirements can be seen as a key competitive advantage. There are several methods and techniques like Release Planning Prototype and EVOLVE, which use generic algorithms to resolve the release planning issue but it is not worthwhile if the input data is highly uncertain. And according to surveys, only two strategic planning methods addressed quality constraints. 
1. Win-Win model which is a quantitative model and addresses effort and time constraints but not the quality level of QR.
2. QUPER is the only method which addresses quality and cost constraints of QR
This paper includes
 1. Detailed guidelines of how to apply QUPER model in practice with an illustration of QR.
2. An added step which includes how to incorporate cost dependencies between quality requirements. The reason to add this step is that dependencies may have a major impact on the estimated cost for other QR. The cost to improve the quality level for one QR may imply an improved level of quality for other QR. This may lead to a change of other QR cost barriers and which QR to select for the coming release. Hence there is a need to incorporate cost dependencies in QUPER model.
3. Two evaluations of complete version of QUPER model which helps to evaluate QUPER’s applicability.

Two main factors motivated the creation and evolvement of QUPER model is
1. Direct need identified in industry.
2. A model for supported release planning of QR was not found in the literature.

In this paper a detailed guidelines of application of QUPER model is presented in 7 steps by considering an example of quality requirements of a mobile TV.  And all of these steps are based on the description of the QUPER model discussed in [5]. Those steps include 
1. Identify candidate QR.
2. Define scale and unit.
3. Identify reference levels.
4. Elicit quality breakpoints.
5. Estimate cost barriers.
6. Set candidate requirements.
7. Identify cost dependencies.
Each of these steps is clearly explained with figures and thus it helps to know the practical view of QUPER model. Also the complete version of QUPER was evaluated in industry at one case company with 24 industry professionals using real QR. Hence through this paper, we can gain the practical knowledge of applying this model and also helps to understand the problems that may arise while applying this model practically.

The main difference between article [5] and [6] is that the authors of [6] included the cost dependencies among QR and both the articles helps to consider quality requirements and also describe the practical application of QUPER model in different companies.

Summary of article [7] (B. Regnell, P. Beremark, and O. Eklundh, “A market-driven requirements engineering process: results from an industrial process improvement programme,” in Conference on European Industrial Requirements Engineering (CEIRE ’98), 19-20 Oct. 1998, vol. 3, pp. 121–9.)

The authors of this paper mainly concentrated on the market-driven requirements engineering and describes an industrial process called REPEAT (Requirement Engineering ProcESs At Telelogic) which incorporates continuous requirements elicitation and prioritisation together with expert cost estimation as a basis for release planning. This process is enacted by the Swedish CASE-tool vendor Telelogic AB which is a fast growing company with 180 employees and more than 600 worldwide customers. This process is used in-house at Telelogic for eliciting, selecting and maintaining requirements on the product family called Telelogic Tau which is a software development environment for real-time systems.

REPEAT process:
REPEAT is a process which manages the requirements throughout a release cycle and covers important requirements engineering activities such as requirement elicitation, documentation and validation. The actors involved in this process include:
1. Requirements Management Group (RQMG)
2. Issuer
3. Customers and users
4. Requirements teams
5. Construction team
6. Test team
7. Expert and 
8. Requirements Database (RQDB)
The RQMG group with the support of experts is responsible for deciding on requirement state transitions. The states are 
1. New (Requirement is issued and given an initial priority)
2. Assigned (Requirement is assigned to an expert for classification)
3. Classified (Rough estimate of cost and impact are attached)
4. Rejected (End-state indicating requirement has been rejected)
5. Selected (Requirement is selected for implementation)
6. Applied (End-state indicating requirement is implemented and verified) 
REPEAT is instantised for each release and each instance has duration of 14 months. A new product version is released at fixed dates for every 6 months. Each REPEAT instance has five different phases separated by milestones. Different phases are explained as follows. 
1. Elicitation phase: It includes two activities collection and classification. The output of this phase is that the priority, cost and impact estimates are given to the requirements and it enters the classified state and will be further treated in the next phase.
2. Selection phase: The main goals of this phase are to select which requirements to implement in current release, to specify the requirements in more detail and to validate the requirements document. And the output is a requirements document which includes a selected list, detailed specification of all requirements and a non selected list which includes requirements that are postponed to next release.
3. Change management, construction, verification and conclusion: During change management, the RQMG takes decisions on changing the requirement document caused by new incoming requirements. Feedback is given to the issuer on the decisions taken to the change in requirements. Construction includes iterative design and implementation process with a weekly build and unit test. In verification activity, requirements in selected list are verified against requirements document using requirement based testing method. And then the conclusion phase is entered where metrics are collected and final report is written.

Implementation of this process resulted success rates to the company due to its detailed specification of requirements, classification activity, prioritization etc. However there are many challenges that are identified by the company. They include
1. Overload control
2. Connecting fragments
3. Bridging the chasm between elicitation and selection
4. Long-term product strategy for a diversity of market segments
To meet the above challenges and based on the expert surveys, case studies and experiments REPEAT-2 is introduced and the two main techniques which supports this introduction are hierarchical use case modelling and cost value use case prioritization.

References:
[1]	S. Aaramaa, T. Kinnunen, J. Lehto, and N. Tausan, “Managing constant flow of requirements: screening challenges in very large-scale requirements engineering,” in Product-Focused Software Process Improvement. 14th International Conference, PROFES 2013, 12-14 June 2013, pp. 123–37.
[2]	K. Wnuk, J. Kabbedijk, S. Brinkkemper, B. Regnell, and D. Callele, “Exploring factors affecting decision outcome and lead time in large-scale requirements engineering,” J. Softw. Evol. Process, vol. 27, no. 9, pp. 647–73, Sep. 2015.
[3]	B. Regnell, R. B. Svensson, and K. Wnuk, “Can we beat the complexity of very large-scale requirements engineering?,” in Requirements Engineering: Foundation for Software Quality. 14th International Working Conference, REFSQ 2008, 16-17 June 2008, pp. 123–8.

Seminar 2: 

Boston Matrix (four-quadrant analysis or BCG matrix):  It is an analysis method proposed by the Boston Consulting Group which is one of the large consulting firms in the United States. It is mainly based on the idea that the company’s business units are classified into four categories based on the combinations of market growth and market share relative to the largest competitor. Market share represents the percentage of the total market achieved by the organisation which is measured in terms of revenue or unit volume and market growth refers to the attractiveness or demand of a market. The four categories of Boston Matrix are as follows:
1.  Skinny dog type (Dog), namely a lower market growth and low market share rate products and thus they tend to absorb cash rather than generating it and are developing in a slow growing industry.
2. Taurus type (Cash Cow), namely a lower market growth and high market share of products and hence exhibit a return on assets that is greater than the market growth rate, and thus generate more cash than they consume. So this type of business units should be milked, extracting high profits by investing fewer amounts. This helps to provide the cash required to turn the question marks into stars and many other financial needs of the organisation.
3. Problem children (Question mark), namely higher market growth and low market share of products and hence they grow rapidly by consuming high amounts and retrieving low profits. Hence it has the potential to gain market share and become a star, and eventually a cash cow when the market growth slows. So there is a need to analyze them carefully to decide whether they are worth the investment required to increase market share and hence named as question mark.
4. Star-type (Star), namely higher market growth and high market share of products and hence it generates large amounts of cash and also consume large amounts because of their high growth rate. If a star can maintain its large market share, it will become a cash cow when the market growth rate declines. The portfolio of a diversified company always should have the stars that will become future cash cows.
The main purpose of this matrix is to help the companies to decide which of their units they should keep, where they should invest further and which ones should they consider getting rid of. But it has its own limitations and is listed below.
Disadvantages:
1. Focussing only on market growth and market share can encourage organisations to disregard other key factors that define their competitive position. In addition, they need to take into account interdependencies between your products and be aware of the merits of differentiation as a way to gain a competitive edge. 
2. The framework assumes that each business unit is independent of the others. In some cases, a business unit that is a "dog" may be helping other business units gain a competitive advantage.
3. The Boston Matrix assumes that the higher your market share the more profitable your product or business unit will be. It also rejects the possibility that a niche product with a low market share can be profitable. In some cases of reality, dogs offer more profits than cash cows.

Seminar 1:
GAP analysis: 
It is a process through which a company compares its actual performance with the expected performance in order to determine whether the company is meeting its expectations and utilising the resources effectively.
It also provides a way to identify how available software services (as-is) may be assembled within the newly conceived and redefined business models (to-be) to better meet the organization’s goals [1] . This can be conducted in different perspectives such as organization, business processes, information technology etc.

GAP analysis templates generally have the template with these three steps. The basic steps to perform GAP analysis are:
1. Identifying the future state to which the company’s performance should be expected to reach.
2. Analyzing company’s current situation (includes attributes, competencies, and performance levels). 
3. Identifying how to bridge the gap between current state and expected future state.
The assessment of the current situation and future situation can be both qualitative and quantitative.

Future state: It includes the target condition that a company wants to achieve. In general, this section is drafted in quantifiable terms such as aiming to increase number of customer calls by a certain percentage within specific period of time. 
Current state: Identifying the current situation of a company can be effectively done through brain storming workshops, one-to-one interviews, reviewing documents, observing project activities such as design work shops etc. This analysis can be quantitative such as looking at the number of calls answered within in a specific time period, or it can be qualitative such as examining the state of diversity in work place.

Description of gap: After identifying the current situation and future objectives of a company and if there is a gap, its description which includes what constitutes the gap and the factors that contribute to it. These descriptions can also be qualitative and quantitative.

Bridging the gap: It includes listing of all possible solutions that can be implemented in order to reduce the gap between current state and future state. These solutions must be specific and connected to the factors listed in gap description.

There are many tools to perform GAP analysis such as McKinsey 7S Framework, SWOT analysis, Nadler-Tushman model etc. The selection of a particular tool by a company depends on specific goals and objectives of that company. 

Road mapping:
Road map is a specialised type of strategic plan that outlines activities an organisation can undertake over specified time frames to achieve stated goals and outcomes. And road mapping is a process through which a road map is created, implemented, monitored and updated if necessary.
 Technology road mapping is originally developed by Motorola in 1970s in order to support improved alignment between technology and product development. This approach facilitates the communication across functional and organizational boundaries. Road mapping can be performed at either of the two levels, industry or corporate [2]. Road mapping in the case of large scale requirements should be planned properly in order to achieve better results. The general process of road mapping is as discussed below and this is well suited for large scale projects. 
On an average, it takes 6 to 18 months to develop a roadmap. The process of road mapping includes two types of activities expert judgement and consensus, and data analysis and four phases namely planning and preparation, visioning, roadmap development (6 to 8 months) and roadmap implementation (1-5 years recurring).
Expert judgement and consensus activities: 
These activities form the core of road mapping process and are conducted through workshops. These workshops include experts of different disciplines like technology, policy, finance etc. Expert judgement provides a way to make choices among possible scenarios revealed by data and analysis activities. And building consensus across these experts helps to generate strong support for the road map. 
Data and analysis activities: To achieve the roadmap goals, expert judgement should be supported by data and analysis. These activities can be accomplished by a team of analysts and technology experts. The extent of data and analysis activities will vary depending on the amount of available data, time and resources.
Phase 1-Planning and preparation:  
In this phase, the organization undertaking the road mapping initiative must answer several questions related to the plan of road map. The answers for these questions can be obtained through some actions such as ensuring leadership commitment, appointing a steering committee, developing a statement of purpose and scope, conducting base line research, selecting and engaging stakeholders and experts early in the process.
Phase 2- Visioning
Setting a vision is the process of defining the desired pathway for a technology’s deployment. This process includes important tools such as modelling and scenario analysis which are used to define possible future states. Road mapping often includes vision workshops where leading experts will meet and discuss about desired future state of the company and common understanding is established. The participants of a typical workshop include leading researchers, government leaders and senior industry representatives.
Phase 3-Roadmap development
The roadmap development phase begins once the vision is established.  This phase includes some important activities such as holding road map workshops, preparing the draft road map document, conducting a roadmap review.  
Phase 4- Road map implementation and adjustment 
This phase includes two steps launching the road map and putting in place tracking systems. The final road map outlines a set of priorities such as research projects, technology demonstrations, policy advances, regulatory changes and financial commitments. It also includes monitoring the progress and adjusting the road map.   

Tools available for continuous integration:
Continuous integration is an integral part of agile software development setup where members of a team integrate their work frequently. Usually each person integrates daily leading to multiple integrations per day. Some of the open source tools available for continuous integration are listed below.
Jenkins
Buildbot
Travis CI
Strider
Go
Integrity

Customer Value Analysis:
CVA is an innovative research technique that determines how an organization is viewed relative to others in a market place and helps to develop a quantitative picture of the markets in which the organisation compete. Customer value has recently become an essential and important element of a firm’s competitive strategy. Hence the creation of superior customer value is a key element for ensuring corporate success [3]. 
It includes opinions of both customers and competitor’s customers so that the product’s relative performance can be assessed which helps to provide more accurate and usable information for planning and strategic positioning purposes.  
In general, customers choose suppliers who offer them the best value and most useful benefits at the most reasonable prices. Customer Value is a choice model which shows how customers select between competing suppliers.
The main activities performed by a company through this analysis are:
1.Identify the attributes that matters to its customers and to the competitors’ customers.
2.Show exactly how these attributes are defined by the customers.
3.Quantify the company’s performance and the competitors’ performance.
4.Show corresponding prepositions of different customers and what can be done according to this.
5.Provide a fact based, data driven system for making decisions.
6.Provide ways to overcome the competition and tracking ongoing progress.

Technical product management:
Product management is one of the important organisation roles. It is the process of collecting and using data on the products that a business or organization sells handles or makes. Product management process can be handled by the project managers in companies. Some product managers have natural affinity for working with development, some for sales and marketing and some others prefer for work on business issues. Among these, technology expertise plays an important role and deals about how the product works. The product managers pick up a deep understanding of the product and its technological capabilities. The term technical project management describes a person, not a role. It implies that it does not describe a product manager who needs to actually perform technical tasks (software architecting and coding), but they need to perform product management role in close coordination with the technical team. Technical product managers should have strong technical background and this position generally involves close interaction with development leads, product architects and key customers. 
The activities to be performed by a technical manager include:
1. Conducting technology assessments.
2. Analysing the competitive overlook.
3. Maintaining the product portfolio landscape.
4. Monitoring and organising industry innovations.
5. Writing product requirements and use case scenarios.
6. Maintaining a status dash board for all the portfolio products.  

Internal value analysis (IVA):
It is defined as a method which is used to measure whether a product in a company is in line with its strategies or not by taking limited resources and other products into account [4].

Summary of article [J. Karlsson, K. Ryan, “A cost-value approach for prioritizing requirements”, IEEE Software, 1997]:

Authors of this paper argue that meeting needs and expectations of stakeholders is the ultimate goal of any software project that seeks a competitive edge. In order to achieve this objective, stakeholder’s system requirements must be managed accurately. Deciding on which requirements really matters is a difficult task and is also very important because of time and budget constraints. Despite the rapid growth and advancement of requirements engineering research, company managers still do not have simple, effective and industrially proven techniques for prioritization. 
Requirement prioritization helps companies to make acceptable tradeoffs among conflicting goals (quality, cost and time-to- market) and to allocate resources based on importance of requirements to the project as a whole.
Hence the authors of this paper have developed an analytical tool for prioritizing requirements based on a cost-value approach. This tool ranks the candidate requirements in two dimensions based on their value to the customer and users, and based on their estimated cost of implementation. And this method is successfully applied in two telecommunication software development companies. 
Cost-value approach: This approach helps to make the prioritization process simple, fast and yield accurate and trust worthy results. It prioritizes requirements according to their relative cost and value. Cost is the cost of successfully implementing the candidate requirements. In practice, software developers often calculate costs in terms of money. The candidate requirements are investigated through Analytic Hierarchy Process (AHP) which compares the requirements pair wise according to their relative cost and value. Pair wise comparison is chosen because it includes redundancy and is sensitive to judgemental errors. 
Prioritization of requirements using cost-value approach includes five steps.
1. First the requirements engineers review all the requirements carefully to ensure that they are stated in an unambiguous way.
2. Customers and users apply AHP’s pair wise comparison to assess the relative value of candidate requirements.
3. Relative cost of each candidate requirement is estimated by experienced software engineers using AHP’s pair wise comparison.
4. Then the software engineers use AHP to calculate relative value and implementation cost of each candidate requirement and plots these values on a cost-value diagram.
5. Stakeholders use this diagram as a conceptual map for analyzing and discussing the requirements and based on this discussion, software managers prioritize the requirements and decide which requirements should be actually implemented.
Case study 1 (The RAN project):
The goal of this project was to identify and specify requirements for a system that would give managers information about mobile telephony system operation. The authors identified 14 high-level requirements that cover main system functionality and were intended to give managers information about capacity, coverage and quality of mobile communication system. Once these requirements are defined by the authors, project members reviewed agreed on them. A group of experienced project members are asked to represent customer’s views and carefully instructed them on prioritizing requirements, making pair wise comparisons carefully. To make the requirements more clear, the project manager explained each requirement and discussed it with all the participants of the project. Sheets are distributed outlining 91 unique pairs of requirements including the fundamental scale. Then the pair wise comparisons are made by the participants, first according to the value and later according to the estimated costs. The participants are allowed to work with the requirement pairs in any order they chose, allowing for retraction during the comparison process. When all 14 requirements had been pair wise compared, value distribution and the cost distribution are calculated, as well as the consistency indices and ratios of the pair wise comparisons.  Based on the resulting distributions, the candidate requirements are outlined in a cost–value diagram and presented the results to the project members. Analysis is done by this cost value diagram which clearly facilitates requirements selection.  
Case study2 (The PMR Project): Encouraged by the usefulness and effectiveness of the cost–value approach in the RAN project, the authors undertook a second case study. A project that was developing a fourth release: the Performance Management Traffic Recording project is selected and cost-value analysis is applied for prioritizing the requirements for fourth release. The requirements are divided into three categories: those demanding traditional defect correction, those requiring performance enhancement and those suggesting added functionality. The authors decided to prioritize only the last category because both the project managers and the customers agreed that all defects had to be corrected and performance had to be enhanced. 11 high-level functional requirements are selected and 55 pair wise comparisons are made. This approach suggests that the company can deliver a software system with substantial customer satisfaction at a significant reduction in cost.
In my opinion, this approach of prioritizing the requirements is well suited for the projects with less number of requirements. It is difficult to apply this approach in the case of large scale requirements engineering as it does not take interdependencies into account. However it has many advantages and can serve better if it is able to handle large number of requirements and consider interdependencies. 

Summary of article (Gorschek & Wohlin “Requirements Abstraction Model”):
Authors of this paper argue that software requirements arrive in different shapes and forms to development organisations. Particularly in the case of market-driven requirements engineering, requirements direct on products rather than towards project and it results in challenges related to making different requirements comparable to each other. To make this comparison, a model with four abstraction levels was developed as a response to the industrial needs. It allows for placement of requirements on different levels and supports abstraction.
In software industry, market-driven incremental product development is becoming increasingly common place and is planned and executed with the goal of delivering an optimal subset of requirements in a certain release. This includes activities such as establishing what should be included in a release, when should be released and at what cost. As in the case of MDRE, requirements are generated by multiple sources, both internal and external and thus they come in different shapes and forms, at multiple levels of abstraction. Hence the project managers were faced with the challenge of how to take care of continuous incoming stream of requirements ranging from abstract to technically detailed. Based on this problem, Requirements Abstraction Model (RAM) is developed and this article presents the model, how it was created and validated through feedback from professionals and also how it was tested in a live project. The benefits of using RAM include:
1. All requirements are compared to the product strategies and this offers an assurance that requirements do not violate the overall goals set by the management.
2. All requirements are broken down to an abstraction level and this assures that the project get good enough requirements.
3. The requirements are formulated on the same level of abstraction and hence they can be compared and set against one another.
4. All requirements can be followed though several levels of abstraction giving a rich understanding of each requirement.
Requirements at different levels of abstraction are considered as crucial input to the development and helps to get a better understanding of which requirement to be developed and why. Both the abstract and detailed are important and two used in combination offers a better understanding. RAM does not assume a starting point. It takes what requirement is available as input and uses it as a base. There is no choice of flattening the requirements to a single abstraction level and hence this model offers the possibility of comparison of requirements against each other on one or several abstraction levels. 
The main cause for the development of RAM is the increased pressure on product development organizations to handle on expanding load of requirements coming in to product management on varying levels of attaraction and detail. Moving away from project-centered development demands support for handling the incoming requriements. Two major factors motivated for the creation and evolvement of RAM are (1) A direct need identified in industry. (2) A method suitable for continuous catching and handling them on multiple levels of abstraction was not found in the literature before.
Evolvement of requirement abstraction:
The evolvement of RAM took place through several stages. Intially it went through two major validations(static). These steps invloved brainstorming/interview sessions with product and PM.Then the importance of dynamic validation is recognized and it consisted of using RAM for real live requirement engineering. Both static and dynamic validations had a fundamental impact on the model. The authors of this article present RAM v.1.0 which is mainly aimed towards establishing support for intial stages of requirements engineering which is performed by Project Managers.
RAM structure and Overview:
Requirements engineering using RAM model invloves three steps:
step 1:specify(elicit): This step invloves specifying the raw requirement and eliciting enough information about it to specify a number of attributes. The main goal of this step is to get an overview of the raw requirements to the stage where the product manager understands the requirement clearly. In order to get a uniform way of specifying requirements, four main attributes are specified manually.
1. Description: The description should not be more than five sentences and should describe the central essence of the requirement.
2. Reason/Benefit/Rationale: This attribute consists of two parts: WHY the requirement is specified and BENEFIT of the specified requirement. Benefit should be written in the context of the subject(like user, product,requirement's perspective) of the requirement being stated.
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
Requirements workup discussion:
No requirement may exist without having a connection to the product level. This implies that new requirements are created on upper levels using lower level original requirements as a base.
All the possibilities and exceptions of connecting the requirements from upper level to lower level and vice versa are discussed in the workup discussions.
As the requirements are specified placed and worked up, additional attributes are specified for each requirement. Those additional attributes include requirement source, requirement owner, requirement manager, relation /dependency, state, reject reason, due date, version, date of creation and last changed. 
RAM validation:
This article also offers a presentation of the evolutionary development of RAM and is validated in industry against an organisation faced with improvement issues. Validation is divided into two main parts static and dynamic. Static validation consists of reviews and walkthroughs. For this purpose, different roles are identified as the product manager, the orderer, the project manager, the system engineer, developer, system tester, upper management. 
Dynamic validation consists of a live industry requirement engineering effort where the model was put through its phases. The idea of this was to use the model for actual requirement engineering in order to validate its components and to check if the model was scalable to a real development situation. It also involves validating several aspects of RAM such as abstraction levels. This validation is run on real requirements and answers to those questions are obtained. It was concluded that the material produced by using RAM was considered more than adequate and it also offers the material on an even level. And the potential problems with the model were not directly associated with RAM, but rather the infra structure needed to support it.
 This paper also addresses the issues faced by the requirement engineers and project managers of different organisations as the consideration of abstraction levels would be different in different companies. The future work of this article includes a controlled empirical evaluation in a lab environment performed which is helpful to give important feedback regarding usability and usefulness of RAM without spending valuable industry resources. In addition to this, an usable and flexible light weight model that covers requirement engineering activities performed not only during product planning and management activities, but also within and post projects is implemented and named RAM v.2.0. 

Summary of article (Gorschek & Davis “Requirements Engineering. In search of dependent variables”):

The authors of this paper presented a frame work of dependent variables that serves as a full range of requirements engineering quality assessment.  Generally in most of the companies, assessment is based on two main factors: The requirements process (like measurement of time and resources consumed) and the primary product (like measurement of the quality of software requirements). But some researchers’ state pointed out that performing well on either or both these tests do not necessarily translate into true success. Most of the requirements engineering process improvement efforts are performed with an aim of improving the projects with little or no concern for resulting products. In most of the cases engineers attempt to make changes to their processes (independent variables) with the hope that some positive outcome (dependent variables) will result. Dependent variables can vary tremendously from the shortest term to longest term. Deciding the right dependent variable for specific case is a major consequence. Hence to fill this gap, the authors of this paper presented a frame work of dependent variables, which can serve as a requirements engineering quality assessment basis. As requirements processes are changed, we may assess their impact on dependent variables and they generally reside within at least five distinct levels. 
Requirements phase:  This level includes dependent variables that relate to requirements cost and time, and quality.
Project: This level refer to, whether the project was completed on time, within budget and did it meet all the specified requirements. This level includes dependent variables that relate to project cost and time, project estimates and degree of requirements change. 
Product: Dependent variables within this level determine the degree of product success. This level includes dependent variables that relate to requirements selection and degree of impact. 
Company: This level includes measures such as portfolio management, strategic alignment and degree of impact.
Society: A project that contributes to a company’s bottom line but pollutes the environment or kills people must be considered a failure. Dependent variables of this level include positive and negative externalities.
Some of measures for all these five levels have been proposed by other researchers. But there is a need to develop new best-practice guides that take into account broader bases. This paper includes detailed summary of previous research on measures of all the five levels by which this article acts as a reference for research performed in this area. The main contributions of this paper include 
1. It creates a clear classification of levels so that the impact of changes in RE process can be assessed.
2. It suggests that product strategies should reflect long term goals, but these goals also have to be aligned to both current market and technology trends.
3. It increases awareness that the strategies used must be stated explicitly and all the requirement engineers should be aware of this.
4. It exposes the fact that at higher levels in the taxonomy, we need to recognize that impacts are multidisciplinary and multi-perspective.
 Al these contributions serve the companies to take care of the dependent variable while the requirement engineering process changes are made and serves as a reference as it presents a clear frame work of all the variables in different views. 

Summary of article (Khurum & Gorschek “A method for early requirements triage and selection utilizing product strategies”).
This paper evaluates an efficient and effective method that deals with the challenge of over load of the development organisation in the case of market-driven product development due to large number of requirements. A method for early Requirements Triage utility product strategies (MERTS) is built based on the needs identified in literature and industry. This paper includes the evaluation of effectiveness and efficiency through controlled experiment in lab environment with 50 software engineering graduate students as subjects. Evaluation is done by comparing MERTS with natural language (NL) format.
The authors of this paper argue that the requirements in market driven requirements engineering in contrast to traditional requirements engineering, come from internal sources (like developers, marketing, sales teams and bug reports) and also from external sources (different users, customers from different and multiple market segments and competitors) which results in large and continuous flow of requirements. It threatens to over load development organisations. To reach the optimal strategy for the company, all the factors such as selection, accuracy, scalable and cost effective way of selecting the requirements must be considered. To achieve this, strategic and middle management and technical experts all need to share one vision. This need can be achieved by a method for Early Requirement Triage and selection (MERTS) which combine both strategic and technical perspectives for the formulation of product strategies. MERTS has two main purposes:
1. It acts as a stepwise guide to create product strategies taking both technical and strategic views into account.
2. The strategies resulting from MERTS can be used by project managers to efficiently perform requirement triage and requirement selection in a reasonable amount of time.
MERTS background:
MERTS is centred on ensuring that the five strategic questions for a product are answered explicitly. The project managers using this method should follow three parts. Each part has several steps.
Part 1- Early requirement Triage: It provides steps to create an initial product strategy for use in requirement triage.
A. Specify: Includes specification of the directions of movement for the product deduced from the organisations’ mission statement. It includes answers for three strategic questions:
1. Where we want to go? 
2. How to get there?
3. What will be done?
for each product. The output of this step is a detailed understanding of goals and objectives associated with a specific product.
B. Assign weights: The answers from step 1 are assigned weights. The weights are assigned to each of the factors based on their relative importance. 
C. Compare requirements: Total weights of all requirements are compared against a threshold to select or reject each of the requirements.
Part 2- Requirements selection for release: After the identification of set of requirements, the next step is when to get there. This can be achieved through 
(i) Specification of product technology road map
(ii) Estimating resources        
 Part 3- Strategic Rationale: Once the strategic questions have been answered, reasoning behind the decisions should be documented.
In order to implement MERTS, requirements need to be comparable to the formulated strategies. 
Experiment: The experiment was conducted in an academic setting, with the help of 50 engineering graduate students of BTH. The main aim of the experiment is to compare the efficiency and effectiveness of MERTS with NL format. Subjects are divided into groups and experiment is conducted as one group having product strategy in NL format and another in MERTS format. Each subject was given either NL or MERTS formatted strategy and the strategy detailed goals of new version of a mobile phone targeted for entertainment oriented users in Asian market. Each requirement in the set has at least two levels product and feature, and also divided into functions and each requirement was formulated using attributes like unique id, product level requirement, feature level requirement, function level requirement, component level requirement. Hence this representation reflects the requirement abstraction model. Applicable validity threats i.e. internal validity, construct validity, external validity is also addressed in conducting the experiment. The results of the experiment stated that MERTS is far superior to NL when it comes to strategy formulation and utilization for the purpose of requirement triage. But the only potential drawback is that MERTS seems to be more resource intensive to use. This model takes more time but avoids errors and is a systematic method for thinking and make decisions which is missing with strategies.         

References:
[1]	J. Moratalla, V. de Castro, M. L. Sanz, and E. Marcos, “A gap-analysis-based framework for evolution and modernization: modernization of domain management at Red.es,” in 2012 Annual SRII Global Conference (SRII), 24-27 July 2012, 2012, pp. 343–52.
[2]	Sungjoo Lee and Yongtae Park, “Customization of technology roadmaps according to roadmapping purposes: Overall process and detailed modules,” Technol. Forecast. Soc. Change, vol. 72, no. 5, pp. 567–83, Jun. 2005.
[3]     W. S. DeSarbo, P. Ebbes, D. K. H. Fong, and C. C. Snow, “Revisiting customer value analysis in a heterogeneous market,” J. Model. Manag., vol. 5, no. 1, pp. 8–24, 2010.
[4]   T. Gorschek and A. M. Davis, “Requirements engineering: In search of the dependent variables,” Inf. Softw. Technol., vol. 50, no.1–2, pp. 67–75, 2008.

Seminar 3:
Summary of article (Wnuk & Gorschek “Obsolete Software Requirements”):
The authors of this paper stated that due to rapidly changing business environments, requirements engineering approaches are facing many challenges such as high volatility and quick evolution of requirements, requirements tend to become obsolete even before the completion of project. In extreme cases, obsolete requirements can extend the project timelines and total cost of the project, and may sometimes cause project failure. Hence there is a need for the companies to identify, handle and remove such requirements to avoid these difficulties. Several researches focused on the topics related to obsolete requirements (such as requirements volatility and scope creep). However, very little research is performed on obsolete requirements management or guidelines. Taking this gap into consideration, the authors of this paper formulated seven research questions which focus on understanding of obsolete software requirements (OSR) phenomenon and its place in the requirements engineering landscape. 
Requirements management is an integral part of requirements engineering and it helps to effectively manage the data created in requirements elicitation and development phases of the project and also integrates this data into the overall project flow. In the case of market-driven requirements engineering, a constant stream of new requirements and change requests is inevitable. Hence in such cases, absence of requirements management may lead to outdated requirements specification. According to the understanding of authors, obsolete software requirements are any type of requirement (stable, small, large, changing) that is not realized or dismissed, but which accumulates in the companies’ databases and repositories. And Requirements obsolescence is defined as a situation where volatility becomes outdated and remains in the requirements databases.  
Hence to make this concept clearer, research questions were framed such that a clear definition of obsolete software requirements is obtained, investigate the impact of the OSRs on industry practice, to get information about how likely the various types of requirements would become obsolete, investigation of the possible ways of identifying obsolete requirements in the requirements documents, to find possible actions to be taken against obsolete requirements after they are discovered,  to investigate whether there is a correlation between project size and the effects of OSRs, if OSRs are related to the software context, understand where in the requirements life cycle OSRs should be handled and to investigate if industry has processes for managing OSR.
To find answers to the questions, a survey is conducted and the conclusions drawn from the results include:
1. The definition of OSR given by the majority of respondents is “a software requirement (implemented or not) that is no longer required for the current release or future releases, and it has no or little business value for the potential customers or users of a software artefact”. 
2. OSRs constitute a significant challenge for companies developing software intensive products, with the possible exception of companies involved in the service domain.
3. Requirements that are related to specific standards and laws are least likely to become obsolete, while the inconsistent and ambiguous requirements are most likely to become obsolete.
4. In most of the cases, identification of OSRs is manual and it is difficult to identify them automatically.
5. The identified requirements should be kept in the requirements document or in the database and should be tagged as obsolete.
6. Large scale requirements and very large scale requirements engineering based projects are mainly affected by OSRs.
7. OSRs should be handled in early stages of requirements analysis and requirements validation and Requirements elicitation is not the best phase to manage OSRs.
 
Hence this paper acts as a reference to future researchers and gives scope to many new ideas regarding the area of obsolete software requirements such as the need to develop automated methods or tools to support practitioners in the identification and management of OSRs which is very useful for LSRE and VLSRE. 

Seminar 4:
What tools are available for requirements management?
Some of the tools available for requirements management are:
IBM Rational Doors
Jira
Jama
Kovair ALM studio
Mingle
Caliber
inteGREAT
in-STEP BLUE
VersionOne
Blueprint

Tools for agile requirements management:
HP Agile Manager
Jira Agile
Mingle 
VersionOne
Rally
AgileZen











