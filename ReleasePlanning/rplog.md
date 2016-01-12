Week 46:

 As a part of release planning assignment, I have referred to some of the articles

 [1] G. Ruhe and M. O. Saliu, “The art and science of software release planning,” IEEE Softw., vol. 22, no. 6, pp. 47–53, Nov. 2005.

[2]	P. Carlshamre, “Release planning in market-driven software product development: provoking an understanding,” Requir. Eng., vol. 7, no. 3, pp. 139–51, 2002.

These articles helped me to get an idea of release planning, its importance in the case of market driven requirements engineering and how it is implemented practically. Some of the approaches to develop a strategic release planning are also specified in these articles. 

Then I have gone through all the given 73 issues and tried to understand them. I felt that most of the basic requirements of course management system are covered and detailed and there are quite number of interdependencies among them.  

Week 47:

I have gone through all the issues in detail and identified some of the issues which are not clearly understood by me. To make them clear, I started commenting on the issues.And some of issues can be enhanced further by adding sub features. Suggestions for these issues are also incuded in the comments. 

Issue number: 35

Issue: Extra Contents of Personal Profile (The personal profile shall have the following text fields: address, zip code, city, e-mail address, ICQ UIN, home, mobile, and office phone number, fax number, age, interests, "about me", link to personal homepage)

Comment: Does the user need to provide all the details mentioned above compulsorily? All the users may not be willing to share their personal information. So it would be better if only important information is to be made compulsory and other contents are left optional to the user.

Issue number: 14

Issue: Course News (It shall be possible to attach news items to a course, in order to keep the students informed about the course).

Comment: What does the news item include? Does it include any additional links?

Issue number: 58

Issue: Access to use course file achieve (Participators in a course shall be able to browse the file archive and download files from the course file archive).

Comment: Is there any default location to save the downloaded files? It would be much easier for the participants if there is a feature of saving the files in desired location each time the download button is clicked.
Issue number: 21

Issue: Course Info (For each course, there shall be information attached containing scope and goal of the course, contents of the course, and examination forms in the course to present to the students what the course goals are).

Comment: It would be useful for the user if we add additional features like downloading the information such as examination forms.

Issue number: 6

Issue: Market (We are currently focusing on the Swedish market, but will extend this to the European market in the future. Long-term, we may wish to target other continents as well).

Comment: Educational systems may vary from continent to continent, so the present system may not be suitable and acceptable in other continents?

Week 48:

After receiving the replies to my comments which include clarification of the issues and suggestions for adding additional issues in extension to the given issues, I carefully analyzed them and took decisions for further actions. And as I found that there are quite number of inter dependencies between different issues, in order to link them to each other, I have gone through some articles that explains how to link requirements to one another. 
[3] P. Carlshamre, K. Sandahl, M. Lindvall, B. Regnell, J. Nattoch Dag,“An industrial survey of requirements interdependencies in software product release planning”, in Proceedings of the fifth IEEE International Symposium on Requirements Engineering, 2001.
[4]  T. Gorschek, P. Garre, S. B. M. Larsson, and C. Wohlin, “Industry evaluation of the 
requirements abstraction model,” Requir. Eng., vol. 12, no. 3, pp. 163–90, Apr. 2007.
Article [3] helped me to know the importance and complexity of the consideration of interdependencies among the requirements, especially in the case of market-driven requirements engineering.
Article [4] helped me to know how to link the requirements at lower level (component level) are linked with the requirements in higher level (product level) and vice versa and also knowledge about how additional features can be added linking to the original requirements.

Week 49:

After analyzing the replies and articles carefully, I started linking the requirements to each other. I found some of the main requirements have sub-requirements and identified them by applying my knowledge gained from the literature I have studied before. I found that issue 43, issue 45 and issue 66 are dependent on issue 20 and are sub requirements of issue 20.  In order to link sub requirements to the main requirement, I found that few labels are provided in GitHub and started linking the requirements using duplicate label. But after receiving the feedback, have realized that the sub requirements are not duplicates to the main requirement and they are clarifications of the main requirement. To make this clearer, I gained knowledge about the usage and meaning of all the labels and how to link sub requirements to main requirements.   
After knowing how to link the requirements and assign labels to the requirements, I started adding new features. I have added two new issues which are sub requirements of existing requirements. The issues are:
1. Download files to desired location: It must be able to the participants to save downloaded files in desired location each time the download button is clicked #84.
2. Download examination forms: Users must be able to download examination forms of a particular course from the course information page #83. 
And identified that issue 83 is a sub requirement and enhancement of issue 21 and issue 84 is a sub requirement and enhancement of issue 31 and issue 58. I linked the corresponding requirements with enhancement labels.

Week 50:

I found that by adding some extra features to the existing system will increase its usability and started adding new features to the system. I have added three new features 
1. Automatic logout: The system must automatically logout if the user is not using the system for a long period of time or if the tab/browser is closed #103. This requirement serves as a new feature to the system and hence it is labelled as a feature.
2. Enable and disable option for automatic logout: All the users may not want to automatically logout from the system. Hence an option is provided to enable and disable this feature #104.
Issue 104 is identified as a sub-requirement and enhancement of issue 103 and they are linked together with enhancement label.
3. Contact information: Through this feature, all the students must be able to find the list of teachers of all courses and their contact information so that it will be easy for them to contact the required teacher. This can be accessed by providing a separate link #114.
And this issue is identified as an enhancement of issue 16 and they are linked together with enhancement label. In addition, this issue also serves as a new feature and hence I have added feature label to it.
After adding the new features, I started assigning myself to some issues. The issues assigned by me are issue 15, issue 30, issue 31, issue 57, issue 58, issue 84, issue 103, issue 104 and issue 114. I have considered file archive as it seems to be interesting for me to deal with and assigned all the five issues (15, 30, 31, 57, and 58) related to it. I have created five of the issues and self assigned four of them (84, 103,104,114). So, in total I have assigned 9 issues.
 I have assigned issue 84 because it was created by me and also the main requirements of this issue, 31 and 58 are assigned by me. As issue 103 is a new requirement created by me and it has no main requirements, I have assigned it to me and as issue 104 is a sub requirement of 103, it was also assigned by me. Issue 114 is a new feature and is added by me, so I have assigned this issue. I did not assigned issue 83 though it was created by me, as it is a sub requirement of issue 21 and it is already assigned by someone. 

Week 51:
After assigning the issues myself, I have to assign milestones for each issue. To do this, all members of the course started discussing about each prioritization technique mentioned in the discussion form. After analysing all the advantages, disadvantages and suitability of all the techniques for release planning assignment, we decided to use grouping technique based on the customer value.
Description of grouping technique:
This approach is based on grouping the requirements into different priority groups. Each group represents something that the stakeholders can relate to (e.g. critical, standard, optional), for a reliable classification. However, the requirements in each group have the same priority, which means that each requirement does not get a unique priority. For the release planning assignment, the priority groups are divided based on the MoSCoW technique. In general, the MoSCoW technique is used by analysts and stakeholders for prioritizing requirements in a collaborative fashion. It consists of four priority groups: 
Must have: Must Haves are features that must be included before the product can be launched. It is good to have clarity on this before a project begins, as this is the minimum scope for the product to be useful.
Should have: Should Haves are features that are not critical to launch, but are considered to be important and of a high value to the user.
Could have: Could Haves are features that are nice to have and could potentially be included without incurring too much effort or cost. However, these will be the first features to be removed from scope if the project’s timescales are later at risk.
Won’t have: Won’t Haves are features that have been requested but are explicitly excluded from scope for the planned duration, and may be included in a future phase of development.
In addition to the prioritization, roadmap is also established. It includes 6 milestones and the development of entire product would be completed within these milestones.

Week 52:
In order to set milestones for the issues, the issues are divided into different versions based on its aim as follows:
Version 0.1:
Aim: Early version, get the bare minimums up and running so that teachers can at least keep students informed about a course. Hence the most important and basic requirements of the system are assigned to this version. In total, 13 issues were assigned to it and according to MoSCow technique, number of issues assigned in each group are
Must have: 8
Should have: 2
Could have: 1
Won’t have: 0

Version 0.5:
Aim: The most important features are available, but perhaps not with full functionality. In total, 32 issues were assigned to it and according to MoSCow technique, number of issues assigned in each group are
Must have: 10
Should have: 14
Could have: 7
Won’t have: 1

Version 0.8:
Aim: The Full functionality for the most important features. All features at least partially implemented. In total, 38 issues were assigned to it and according to MoSCow technique, number of issues assigned in each group are
Must have: 11
Should have: 14
Could have: 12
Won’t have: 1

Version 0.9:
Aim: All functionality implemented. In total, 13issues were assigned to it and according to MoSCow technique, number of issues assigned in each group are
Must have: 7
Should have: 5
Could have: 1
Won’t have: 0
Version 1.0:
Aim: Bugs addressed and most important feedback from earlier releases taken into account. In total, 3 issues were assigned to it and according to MoSCow technique, number of issues assigned in each group are
Must have: 3
Should have: 0
Could have: 0
Won’t have: 0

The issues assigned by me are divided into these milestones as follows:

Version 0.5:
Issue 15 (Course file archive)
Issue 30 (Add/Remove files to file archive)
Issue 58 (Access to use course file archive)
Issue 103 (Automatic logout)
Issue 114 (Enable and Disable option for logout)

Version 0.8:
Issue 31(Download files from course file archive)
Issue 84 (Download files to desired location)

Version 0.9:
Issue 57(Access to change in course file archive)
Issue 104(Contact information)
