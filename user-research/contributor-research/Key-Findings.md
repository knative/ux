# Key Findings:

In our investigation of the Knative contributor experience, We explored why people contribute to Knative and found they do it to learn, connect with others, and work on advanced technologies. We also discovered challenges contributors and maintainers face, like getting started and staying engaged. The Knative community is friendly and helpful, but sometimes people stop contributing due to personal reasons or finding it too difficult. These findings should help us understand how to make Knative better for everyone involved.

## Table of Contents

1. [Motivations Behind Contributing to Knative](#motivations-behind-contributing-to-knative)
2. [Primary Challenges Faced by Contributors](#primary-challenges-faced-by-contributors)
3. [Primary Challenges Faced by Maintainers](#primary-challenges-faced-by-maintainers)
4. [Community Engagement and Interactions](#community-engagement-and-interactions)
5. [Reasons for Disengagement](#reasons-for-disengagement)
6. [Some Additional Insights](#some-additional-insights)


## Motivations Behind Contributing to Knative

- ### **Learning and Skill Development**
	- **Real-World Experience**: Many contributors are driven by the desire to learn new cloud-native technologies and many seek real-world application of their programming skills. One contributor noted, "I feel *like the main motivation is skill development because I never had much experience in software development."*
	- **Upskilling and Competitive Advantage** A maintainer said, *“One (contributor motivation) is, of course, just learning new technologies, people like to just check it out, see if it's something that can give them a competitive advantage either in their company or on their resume.”*

- ### **Networking and Collaboration**
	- Contributing to Knative provides a platform to interact with professionals from prominent companies. A contributor highlighted this by saying, *"These opportunities to talk to Red Hat full-timers would never present itself outside of, you know, open source development."*   

- ### **Interest in Advanced Technology**
	- **Technological Appeal**: Contributors are drawn to Knative's modern technologies and serverless computing. 
	- **Specific Interests**: Some contributors are intrigued by certain technical aspects of Knative based on their prior experience. For example, a contributor expressed, *"When I started, there was one issue about adding more tests in Knative. Since I was slightly familiar with how it works, I thought it might be a good idea to just add tests."*

- ### **Immediate Needs**
	- **Company Needs**: Some contributors are driven by the immediate needs of their employers. One explained, *"Maybe the company is using Knative, and they want to get that feature in faster without waiting on the maintainer capacity."*
	- **Short-term Engagement**: Contributors with some specific goals (such as the one mentioned above) might only stay involved until their objectives are met. A maintainer shared, *"Their involvement is limited to that feature. After that, they disappear."*

- ###  **GSoC and LFX Mentorship:**
	- Several contributors discovered Knative through programs like Google Summer of Code (GSoC) or the Linux Foundation (LFX). But most of them disengaged after their project terms were over. 

## Primary Challenges Faced by Contributors

 - ### Onboarding Difficulties
 	 - **Complexity of Tools:** Many contributors struggle with understanding and using Docker and Kubernetes. One noted, "Understanding how Docker works and why Docker is necessary. And also what Kubernetes is, I think those would be really helpful when someone's trying to set it up and start contributing."
	 - **Lack of Clear Starting Points**: Many contributors find it difficult to know where to begin. One mentioned, *"When I first assigned myself to a ticket, I just didn't have any idea about how to proceed with it."*
	- **Specific Documentation**: Some of the existing documentation is not very detailed and some contributors specifically pointed out the absence of clear setup instructions for Mac M1 and WSL. Also, some expressed a strong need for more comprehensive resources, such as tutorials and clearer documentation, to assist them in navigating the project setup process and becoming familiar with its various components and workflows.
	- **Intimidation**: The sheer size and complexity of the codebase can be intimidating. One contributor stated, *"Knative is like a super huge project... So I was really overwhelmed at the beginning when I started contributing."*
	-   **Assumed Background Knowledge**: Onboarding materials often assume a high level of prior technological knowledge. As one maintainer pointed out, *"It assumes that you have a lot of background in technology."*
	-   **Difficulty Finding Information**: Contributors struggle to find relevant information, especially regarding specific repositories and topics. One said, *"Narrowing down which part should I focus on... is the most difficult part."*
	-  **Complex Terminologies**: The language used in Knative documentation can be challenging to understand. A contributor mentioned, *"The language was kind of complex for me to understand what these particular terms are referring to."*


 - ### Issue & Task Selection
	 - **Seeking Guidance for Issue Selection**: Contributors often have to seek advice from experienced members to find suitable issues: *"I ask for advice. So I would ask Calum and Leo for advice about what issues are more suitable for first issues or for new contributors."*
    - **Scarcity of Good First Issues**: Many contributors find that the issues labeled as "good first issue" are very less and quickly claimed, leaving them with fewer options: *"But when I was picking the tickets, all the ones that were labeled as first issue were all taken."*
    -  **Complexity of Multi-repository Issues**: Some issues labeled as "good first issue" require knowledge of multiple repositories, which can be challenging for beginners: *"One single issue that is even marked as good first, it requires you to know how those repos work together."*

 - ### Some Other Challenges
	 - **Demotivation Due to Complexity:** The initial complexity and lack of understanding can lead to demotivation. One contributor expressed, *"I felt the most demotivated to keep doing this when I didn't know where to start or where to get help."*
	 - **Facilitating Direct Engagement**: Contributors express a desire for direct interaction with maintainers. They suggested something like Office Hours or One-on-One Mentorship opportunities that could provide them valuable guidance and support, helping them overcome barriers to entry and navigate the project more effectively.
	 - **Balancing Commitments:** Contributors who are students or have full-time jobs find it challenging to balance their commitments with contributing to Knative. One contributor mentioned, *"I'm also balancing full-time university undergraduate at the same time, so I can't commit too many hours per week to Knative."*



## Primary Challenges Faced by Maintainers
- ### **Contributor Engagement and Management** 
	- Maintainers often struggle with inconsistent participation from contributors. Contributors may take on issues but then become unresponsive, leaving work incomplete. This stalls progress (especially if there is a timeline associated with a ticket) and creates uncertainty about how to proceed. One maintainer expressed this dilemma: *"Should I like make a PR to override their work … I don't want to do that... Or should I just do that myself? Or should I just wait forever?"*
	- Additionally, maintaining engagement over time is difficult. Contributors might resolve initial questions and then disappear, leading to a cycle where maintainers constantly invest time in onboarding new contributors without long-term returns: *"They come in, they do something, they get it to work, I think, but they don't come back."*

- ### **Onboarding New Contributors**
	- The onboarding process for new contributors is often challenging for maintainers due to the complexity of Knative and its technological stack. Contributors frequently struggle with setting up their development environments, understanding the codebase, and debugging their work: *"With enough like energy, like willingness to do that, you can kind of get some local setup that kind of works. But then like, learning about the all components and how all work is or working is complicated."*

- ### **Pull Request (PR) Challenges**
	- Maintainers spend significant time helping contributors get their PRs merged, especially when these contributors lack sufficient understanding or have not thoroughly tested their code. This can be frustrating and time-consuming: *"Sometimes they'll open a pull request that doesn't really resolve it at all or doesn't compile, and then you have to help them figure out how to get their code to compile."*
	- Long-standing PRs can become problematic as they may require rebasing or run into conflicts, further delaying progress.

- ### **Identifying, Creating, and Labelling Suitable Issues**
	- Maintainers acknowledge the difficulty in consistently identifying what makes a "good first issue": *"We don't really know what's a good first issue. Okay, in a sense that, as I said, different contributors are coming from different backgrounds."*
	- Creating and maintaining good first issues can be time-consuming for maintainers, making it difficult to keep a steady supply: *"It might take me five hours to flip that up with a whole bunch of small good first issues, and then it'll take me over 20 or 30 hours to coach people through pull requests for all those."*

- ### **Balancing Responsibilities**
	- Maintainers face the challenge of balancing their own work with the needs of contributors. The frequent need to switch contexts between different tasks and issues adds to their workload: *"One user facing some challenges while like using eventing or like Knative as a whole, and one contributor is trying to get their PR merged or reviewed. And that is, that's the main challenge, ton of content switch."*

## Community Engagement and Interactions
- ### **Welcoming and Supportive Community**
	- Many contributors feel welcomed and supported by the Knative community. The maintainers and other community members are responsive and patient, creating an encouraging environment for both new and experienced contributors: *"I don't know how to say that, but like, I feel welcome."*
	- This sense of community is often cited as one of the most rewarding aspects of contributing: *"I think the most rewarding thing is the community that I'm able to join as part of my contribution journey."*

- ### **Responsiveness and Accessibility**
	- Maintainers are generally quick to respond to queries, whether on Slack or through GitHub, which enhances the engagement and fosters a positive experience: *"One thing that I noted is that all of the maintainers that I contacted response really quickly, which is really convenient."*

- ### **Preferred Mode of Communication**
	- Community meetings are less attended by contributors, particularly newer ones, who prefer to interact through Slack or GitHub. They feel hesitant to engage in meetings due to a lack of confidence or familiarity with the project: *"I still feel a little not confident enough to join that maybe I because I didn't know that much about the work."*
	- One-on-one interactions are preferred by some as they find it less intimidating: *"Meeting one on one will be a little bit more helpful instead of having a lot of people talking to me."*

Overall, the Knative community is rated very highly by contributors, who appreciate the quick and helpful responses from maintainers and the collaborative atmosphere: *"If I have to rate it 1 to 10, I would probably rate it 9"*

## Reasons for Disengagement
- ### **Personal and Professional Priorities**

	- **Individual Needs:** Contributors often engage based on personal or professional needs. If Knative aligns with their daily workflow or company projects, they are more likely to contribute:
*"I will contribute to Knative if I need Knative, like if I use Knative stuff in my daily workflow, or in my company."*
    - **Time Commitment:** As students, contributors often face time constraints due to academic and professional responsibilities, which can lead to reduced engagement.
*"During the school time, a lot of contributors are students... And, you know, like in the university, people are really busy, especially during the exam time or assignment due date."
"I have to manage my college as well as the internship that I'm doing and Knative as well."*
    
	-   **Transition to Work:** After graduating, contributors might prioritize their jobs over open source contributions unless their job involves using Knative.
*"After the student phase, when we start working, it's mostly about individual needs."*
    

- ### **Technical Challenges**

	-   **Understanding Complexity:** Many contributors struggle with the technical complexity of the issues, especially if they lack sufficient knowledge of the codebase.
 *"After they take on the issue and they cannot understand what they're asking to do, or they cannot understand the code base, they feel discouraged."*
    
	-   **Multi-repository Knowledge:** Some issues require understanding multiple repositories, which can be overwhelming for new contributors.
    

- ### **Lack of Immediate Rewards**

	-   **Recognition and Rewards:** Contributors might feel unappreciated or insufficiently rewarded for their efforts, leading to disengagement.
    
	-   **Financial Incentives:** The lack of financial compensation can deter long-term commitment, especially when setting up the development environment and understanding the system can be time-consuming.
*"You're not getting paid. So most people do not have the luxury of being able to sit down for the multiple days that it takes."*
    

- ### **Mentorship and Guidance**

	-   **Post-Mentorship Drop-off:** Many contributors who join through programs like LFX mentorship do not continue contributing after the mentorship ends due to shifting priorities and commitments.
	-   **Need for Continued Support:** Contributors often need ongoing guidance to continue contributing after their initial engagement.
*"There is no clear follow-up to maybe their PR merged."*
    
    

- ### **Long-Term Engagement and Burnout**

	- **Sustaining Engagement:** Contributors might struggle to find the motivation to continue after completing initial tasks, especially if subsequent tasks are more challenging.
*"Some people never really take that next step to go beyond just a good first issue."*
	-   **Maintainer Burnout:** Maintainers might feel overburdened by the need to continuously keep up their individual work, provide extensive guidance to contributors facing challenges, create and manage issues, review pull requests, etc.

## Some Additional Insights

- ### **Perceived Value and Reputation of Knative**

	-   **Organizational Associations:** Contributors appreciate Knative’s structured environment and its association with reputable organizations like RedHat, Google, and CNCF:  "Knative is kind of a growing repository, growing project... previously owned by Google and then go to CNCF."*
	-   **Engineering Excellence:** The project’s reputation for high-quality engineering attracts contributors who want to learn and grow: *"It has a good reputation in terms of engineering."*
    
- ### **Community Support and Interaction**
	-   **Welcoming Community:** A supportive community that is willing to help newcomers significantly boosts contributor motivation: *"People in the Knative Slack or the CNCF Slack are really nice people... they're willing to help you as long as you go and ask for help."*
	-   **Confidence Building:** Contributors gain confidence through successful participation in programs like GSoC, which can motivate ongoing engagement: *"The most important thing that I have gained is the confidence... you don't need to know many things or a lot of things to work in an organization that you can start from a very small thing and, you know, expand your knowledge from that. "*
    
	-   **Positive Experiences:** Contributors who receive timely and helpful responses from the community are more likely to stay engaged: *"The maintainers are very supportive … if you have maintainers like that, then that's a really lucky thing to have."*
    
		-   **NOTE:** Poor experiences with other projects, such as lack of feedback or community engagement, can drive contributors to Knative, where they look to find a more responsive environment: "I tried to contribute to ____ (_name removed_)… I even participated in their community meetings, but they just ignored me … So I gave up on them…"
    

- ### **Contribution Types and Expectations**

	-   **Diverse Contribution Opportunities:** Encouraging diverse types of contributions, such as code reviews or documentation improvements, can keep contributors engaged: *"People might not realize the other types of contributions that would be very welcome... like helping review a pull request…"*
    
	-   **Managing Expectations:** Ensuring that contributors have realistic expectations about the time and effort required for meaningful contributions can prevent burnout: *"You don't need to know many things or a lot of things to work in an organization... you can start from a very small thing."*
