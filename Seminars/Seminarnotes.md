Homework:

Seminar 0:

What is large-scale requirements engineering?

The explosion of new ideas is particularly an evitable part of a company that operates in Market Driven Requirements Engineering (MRDE). Hence there is a need for these companies to often manage hundreds and thousands of requirements arriving from multiple sources. These requirements are inter-related with increasing number of customers, end users, developers, subcontractors, product features, and external system interfaces collectively known as stakeholders. This context is defined as large-scale requirements engineering (LSRE) or very large-scale requirements engineering  (VLSRE)[1].

What are the challenges in large-scale requirements engineering?

Major challenges in large-scale requirements engineering are specified below [1] [2]. 
•	Ill structured problems
•	Uncertain environments
•	Shifting goals
•	Resource allocation
•	Time stress
•	Multiple stakeholder situations
•	Incompleteness of the available information
•	Finding right balance between selecting commercial requirements and internal quality requirements
•	Requirements prioritization
•	Complex dependencies between requirements
•	Multi-objective decision problems
•	Informal Communication
•	Managing requirements interdependencies 
•	Cost estimation

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

References:
[1]	J. Moratalla, V. de Castro, M. L. Sanz, and E. Marcos, “A gap-analysis-based framework for evolution and modernization: modernization of domain management at Red.es,” in 2012 Annual SRII Global Conference (SRII), 24-27 July 2012, 2012, pp. 343–52.
[2]	Sungjoo Lee and Yongtae Park, “Customization of technology roadmaps according to roadmapping purposes: Overall process and detailed modules,” Technol. Forecast. Soc. Change, vol. 72, no. 5, pp. 567–83, Jun. 2005.
[3]     W. S. DeSarbo, P. Ebbes, D. K. H. Fong, and C. C. Snow, “Revisiting customer value analysis in a heterogeneous market,” J. Model. Manag., vol. 5, no. 1, pp. 8–24, 2010.

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











