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



 Summary of article [“R: Berntsson Svensson, B. Regnell (2015) “A case study evaluation of the guideline-supported QUPER model for elicitation of quality requirements”, 21st International Working Conference on Requirements Engineering: Foundation for Software Quality (REFSQ’15),Essen, Germany, pp. 230-246, 2015”].
The authors of this paper argue that the release planning is very important for market-driven software product development organisations operating on a competitive open market. And it is more advantageous when the level of quality of the product is compared with its competitors’ products and hence quality requirements can be seen as a key competitive advantage. There are several methods and techniques like Release Planning Prototype and EVOLVE, which use generic algorithms to resolve the release planning issue but it is not worthwhile if the input data is highly uncertain. And according to surveys, only two strategic planning methods addressed quality constraints. 
1. Win-Win model which is a quantitative model and addresses effort and time constraints but not the quality level of QR.
2. QUPER is the only method which addresses quality and cost constraints of QR
This paper includes
 1. Detailed guidelines of how to apply QUPER model in practice with an illustration of QR.
2. An added step which includes how to incorporate cost dependencies between quality requirements. The reason to add this step is that dependencies may have a major impact on the estimated cost for other QR. The cost to improve the quality level for one QR may imply an improved level of quality for other QR. This may lead to a change of other QR cost barriers and which QR to select for the coming release. Hence there is a need to incorporate cost dependencies in QUPER model.
3. Two evaluations of complete version of QUPER model which helps to evaluate QUPER’s applicability.

QUPER model:
Two main factors motivated the creation and evolvement of QUPER model is
1. Direct need identified in industry.
2. A model for supported release planning of QR was not found in the literature.

The QUPER model is based on the observations that quality is continuous and non linear. It basically includes three types of views [5]. 

1. The QUPER benefit view: It includes three breakpoints indicating principal changes in the benefit level with respect to user experience and market value. 
i) The utility breakpoint represents the border between a quality level useless and useful quality.
ii) The differentiation breakpoint represents the shift from useful to competitive quality, which makes them have a competitive market proposition.
iii) The saturation breakpoint imply a change in quality level from competitive to excessive quality, where higher quality levels have no practical impact on the benefit in the particular usage context considered.
2. The QUPER cost view includes the notation of cost barriers that represents the non-linear relation between quality and costs.
3. The QUPER roadmap view combines the benefit and cost views by position the breakpoints and barrier together ordered on the same scale.

In this paper a detailed guidelines of application of QUPER model is presented in 7 steps by considering an example of quality requirements of a mobile TV. Those steps include 
1. Identify candidate QR.
2. Define scale and unit.
3. Identify reference levels.
4. Elicit quality breakpoints.
5. Estimate cost barriers.
6. Set candidate requirements.
7. Identify cost dependencies.
Each of these steps is clearly explained with figures and thus it helps to know the practical view of QUPER model. Also the complete version of QUPER was evaluated in industry at one case company with 24 industry professionals using real QR. Hence through this paper, we can gain the practical knowledge of applying this model and also helps to understand the problems that may arise while applying this model practically.

References:

[1]	S. Aaramaa, T. Kinnunen, J. Lehto, and N. Tausan, “Managing constant flow of requirements: screening challenges in very large-scale requirements engineering,” in Product-Focused Software Process Improvement. 14th International Conference, PROFES 2013, 12-14 June 2013, pp. 123–37.
[2]	K. Wnuk, J. Kabbedijk, S. Brinkkemper, B. Regnell, and D. Callele, “Exploring factors affecting decision outcome and lead time in large-scale requirements engineering,” J. Softw. Evol. Process, vol. 27, no. 9, pp. 647–73, Sep. 2015.
[3]	B. Regnell, R. B. Svensson, and K. Wnuk, “Can we beat the complexity of very large-scale requirements engineering?,” in Requirements Engineering: Foundation for Software Quality. 14th International Working Conference, REFSQ 2008, 16-17 June 2008, pp. 123–8.
[4]	G. Ruhe and M. O. Saliu, “The art and science of software release planning,” IEEE Softw., vol. 22, no. 6, pp. 47–53, Nov. 2005.
[5]     (R. B. Svensson, T. Olsson, and B.Regnell, “Introducing support for release planning of quality requirements - an industrial evaluation of the QUPER model,” in 2008 Second International Workshop on Software Product Management, 9 Sept. 2008, p. 9 pp.)


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





