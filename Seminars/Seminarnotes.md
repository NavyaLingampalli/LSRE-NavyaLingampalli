Homework:

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

	Summarization of [4] (Art and science of software release planning):

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

References:

[1]	S. Aaramaa, T. Kinnunen, J. Lehto, and N. Tausan, “Managing constant flow of requirements: screening challenges in very large-scale requirements engineering,” in Product-Focused Software Process Improvement. 14th International Conference, PROFES 2013, 12-14 June 2013, 2013, pp. 123–37.
[2]	K. Wnuk, J. Kabbedijk, S. Brinkkemper, B. Regnell, and D. Callele, “Exploring factors affecting decision outcome and lead time in large-scale requirements engineering,” J. Softw. Evol. Process, vol. 27, no. 9, pp. 647–73, Sep. 2015.
[3]	B. Regnell, R. B. Svensson, and K. Wnuk, “Can we beat the complexity of very large-scale requirements engineering?,” in Requirements Engineering: Foundation for Software Quality. 14th International Working Conference, REFSQ 2008, 16-17 June 2008, 2008, pp. 123–8.
[4]	G. Ruhe and M. O. Saliu, “The art and science of software release planning,” IEEE Softw., vol. 22, no. 6, pp. 47–53, Nov. 2005.



