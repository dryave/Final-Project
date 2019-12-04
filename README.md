# Final Project Proposal (Part I)

# Outline

High-Level Summary: Malaria is a disease that is estimated to have killed up to half of the world’s population over time and still wreaks havoc across the world, especially in sub-Saharan Africa. In my final project, I would like to demonstrate how the malaria epidemic has changed in the last few decades based on certain interventions and financial resources and how we as citizens can advocate for interventions that are proven to be successful.

# Project Structure
1.	What is Malaria? A brief paragraph or two to help the audience all get on the same page. If the audience doesn’t believe that there are ways to effectively prevent and treat malaria, they will not be interested in hearing about the interventions.
2.	Malaria rates over time. Everyone has likely come across a map showing the prevalence of malaria in sub-Saharan Africa and been gob smacked by how ubiquitous it seems to be; I don’t believe that a map like this represents the true picture of malaria. Rather, I’d like to show how the rates have changed over time. I have access to many years of data from multiple countries (for more information, see the Data section of this proposal), but before constructing visualizations, I’d like to better understand the data. At this point, I don’t know if it would be more effective to paint this picture as the story of a single country (fewer data points but an easier to track story) or multiple countries in the sub-Saharan region, which would show us more general trends but wouldn’t allow us to understand causality quite as much. I think it would also be likely possible to do it both ways, both a macro and a micro approach.
3.	A brief history of interventions and how they play a role in either malaria reduction or cost-reduction of malaria services. I want this presentation to not be too text heavy because I think a lot of times, stories about malaria are too text-heavy and not very engaging or fun to read. But I think with a disease like malaria, there needs to be a lot of background information so that the audience who may not be familiar with malaria may understand. 
4.	A combination of the malaria disease rates and the interventions history. What I’d like to do through this visualization is help display visually how certain interventions have changed malaria rates. I won’t be able to determine causality necessarily (unless the data include randomized control trials), but it will be exciting to show the reader how certain changes in policy have effected changes in the disease rate.
5.	Information on costs of programs. Some programs (free village-wide medication campaigns, for instance) are much more expensive than others (bed net distributions at the family level, for instance). However, there aren’t a ton of sources that examine the relationship between cost and efficacy. With a combination of 2, 3, and 4, I will be able to do that.
6.	A call to action: based on the results shown in 5, I will be able to suggest which interventions get the most bang for their back, to put it colloquially. I would like the audience to leave the presentation encouraged that certain cost-effective interventions are also life-saving and will be willing to call their congressperson to encourage them to support these interventions by increasing the amount of foreign aid appropriate in the next budget.

# Sketches
![IMG-6973](https://user-images.githubusercontent.com/56807370/69021171-f50fae00-0984-11ea-857d-83494ee05cda.jpg)
![IMG-6974](https://user-images.githubusercontent.com/56807370/69021185-035dca00-0985-11ea-9838-09093eafa0a5.jpg)

# The data 

Many great data sources exist that discuss malaria, but based on my initial research, I couldn’t find a singular resource that contained everything I was looking for to tell the story that I’d like to tell. So for this project I’ll be borrowing data from a few different credible resources.

The first data source is a really well-done visualization from Our World In Data. It shows the changes in the youth mortality rate from 1950-2017; unsurprisingly, there are very few data points for sub-Saharan Africa before 1980. The data demonstrate that devastatingly high mortality rates are observed primarily in sub-Saharan Africa, though they have diminished slightly in the last decade. Their data come from the United Nations Inter-agency Group for Child Mortality Estimation. Source: https://ourworldindata.org/child-mortality

For a slightly more granular look at each country, I turned to the World Health Organization Malaria Country profiles, with data from 2008-2018. Using this repository of data will allow me to focus on one specific country, if the story is better told that way as I believe it will be. Source: https://www.who.int/malaria/publications/country-profiles/en/

The United Nations is another agency deeply concerned with the malaria epidemic. They have great data on percentage of deaths caused by malaria in children under the age of  (U5 mortality is often one of the most highly-correlated statistics with how well a country is doing). This data set will help me illustrate the point that malaria is endemic and the treatment of malaria deserves significant funding. Source: https://data.unicef.org/topic/child-health/malaria/

One piece that I’d like to tie in graphically that I haven’t yet seen is how interventions fit into the overall timeline of malaria prevention. To do this, I am going to rely on a report to Congress from the President’s Malaria Initiative from 2016. (Unfortunately, malaria eradication efforts seem to not be as highly-publicized in this administration…) The report, titled “A Decade of Progress,” is certainly written with the intent to lionize the United States’ efforts to eradicate malaria and is tinted with self-affirming language. However, the interventions discussed are factual and should be considered. Source: https://www.pmi.gov/docs/default-source/default-document-library/pmi-reports/pmi-tenth-annual-report-congress.pdf

One problem with relying on the PMI report is that the United States isn’t the only country engaging in great work. The Global Fund, the Gates Foundation, the UN, the WHO, and many more organizations are also doing their part to prevent and treat malaria. It is irresponsible to say that a reduction in malaria is due to the actions of one country or group without understanding the other groups’ work. For this problem, I will need to come up with a creative way to incorporate other reports or include the caveat that correlation does not equal causation, and just because the US stepped up its efforts in a certain place does not mean that other efforts were not also scaled up or even scaled back. 

Another problem with the above data sets is that very few of them take into account other confounding factors. A country that experiences a particularly heavy rainy season or a famine may see higher rates of malaria that I won’t be able to factor in using the data above. Before I finish the project, I want to consider adding in more information without overwhelming the audience; here I would be very grateful for suggestions!

Finally, I am hoping to take a GIS course in the spring, and when that happens, I would like to update this project to include some GIS data. There are many malaria databases for GIS at this source: https://map.ox.ac.uk/

# Methods

My plan for the final project is to create a presentation using Shorthand. I believe that I can use the platform to build the story that I’d like to tell, starting (as the outline says) from the general “What is Malaria” and “Whom does it affect” and building to the very specific call to action about which specific interventions should be advocated for at the federal level.

Something I would like to clarify (which will likely come as I explore the data and begin building my own visualizations) is how best to tell the story. Should I use sub-Saharan Africa as a semi-homogenous unit? Should I focus my story on one country; perhaps Togo, where I served as a Peace Corps Volunteer? Would limiting to one country (for which the data certainly exist) take away too much from the story? Would focusing on many countries dampen the overall takeaways? It is irresponsible to say that the many countries that make up sub-Saharan Africa are all similar. But focusing on one country allows a particular catastrophic event (a drought, a civil war, etc.) tarnish the malaria-related data. 

I could also tell two stories: A story about a particular country and then how that particular puzzle piece fits into the overall picture. What I worry about in this two-pronged approach is overwhelming the audience. I want the final project to be easy to read; the subject material is already heavy enough that making the project too long might prevent some people from finishing it. 

I also need to figure out how much the average reader for this project understands malaria. It’s possible that people don’t know how endemic it is, or what the cause is, or how it is transmitted (unlike most illnesses, malaria is vector-borne: a person cannot give it to another person, but an infected person can infect a mosquito, who can then infect another person. It’s a subtle but crucial difference). I’m excited to test the iterations of my project with people who aren’t familiar with malaria to see what I need to simplify and what I can remove. 


# Final-Project-Part-II
Here is my final project part II! 

# User Research Protocol: Daniel Ryave Telling Stories with Data Final Project Part 2

My goal for this presentation is to convince graduate students who have limited to no knowledge of malaria to be able to do the following things:
1.	Understand the cause and treatment/prevention options for malaria
2.	Determine which interventions are particularly effective and which interventions are particularly cost-effective
3.	Be motivated to call their congressperson to encourage increased foreign aid spending or donate to a worthy NGO 

# User Testing
In order to understand if my presentation is achieving these goals, I sat down with three graduate students who did not know what the cause of malaria is. (In my experience, people who can’t identify the cause of malaria don’t generally know much about treatment or prevention methods.) My theory held true in this case; the three graduate students with whom I spoke had a lot to learn about malaria. 

My user script was likely longer than most user scripts would be, as I wanted to educate them in the same way that my final presentation will. But I also wanted to give them a lot of room to dissect the information and story boards on their own and provide me with feedback. Here is what I said to my storyboard research subjects:

1.	Thank you for helping me with my project. Today we’ll be talking about malaria and how interventions can help reduce the malaria disease burden. Before we start, what can you tell me about malaria? 
2.	Thanks for sharing your knowledge. We’re going to focus on sub-Saharan Africa specifically because the malaria disease rate is the highest there than in any other region on earth. Let me walk you through my presentation. Please share any thoughts that pop into your head as we go.
3.	The first component is a description of malaria and some statistics to show how mortality has changed over the years. How do these graphs make you feel? What jumps into your mind?
4.	Next, we’ll look at a timeline of interventions. How would you interact with this timeline if it were on a screen in front of you?
5.	I lived in Togo, West Africa, for two years, and I saw firsthand the burden that malaria can have on families. Let’s look specifically at Togo so that we can see some interventions and how they have made an impact. We’ll look at the timeline and the effectiveness. How do you feel about storyboard parts 4 and 5? 
6.	Here are the key takeaways of this project: Malaria has wreaked havoc on sub-Saharan Africa for years, and although interventions exist, the problem is still there. Interventions can be successful but are not always fiscally responsible. The best interventions that have the least cost impact are x, y, and z. What do you think about this summary?
7.	The call to action is that I want you as an audience member to be excited to donate to an NGO supporting an intervention that you support. What do you think of the call to action?
8.	Overall, what are your feelings about the presentation? What do you really like and what do you dislike?
9.	What would you like to see changed? Any feedback here is welcome!
10.	Thank you for helping me with this project.

![malaria 1](https://user-images.githubusercontent.com/56807370/69511669-20f3dc00-0f0f-11ea-9837-3ab79b465713.jpg)


# Findings from interviews and changes to implement

My interviewees were extremely helpful in their frank and candid feedback. Here are some pieces of feedback I received and how I made edits into my second storyboard.
1.	The title “Malaria Today: How YOU can help” is not as strong as it could be, according to the people I interviewed. It sounded a little cliché and not very specific. I changed it to: “Malaria in sub-Saharan African: A crisis that can be solved.”
2.	The graphs in storyboard slide 2 did not accurately prove the point I wanted to that malaria is still a pressing issue. To address this, I changed the graph on the right from the rate of mortality to the absolute mortality to show that deaths are growing.
3.	Two people mentioned that they thought it was disconnected that some graphs talked about under 5 mortality and some with the overall population. To encourage continuity, I changed it all to under 5 mortality. 
4.	The intervention timeline was really well received by my interviewees! I’m excited to build it.
5.	Separating slides 3 and 5 in the first storyboard didn’t help with continuity. To help with this, I rearranged slides 4 and 5 to keep interventions together. I think I like this approach, but I may want to move the Togo information to after slide 2. I will have a better idea after I build out the project a little more.
6.	One person mentioned that my graph in slide 5 is a little busy and may be better by plotting efficacy and cost instead of efficacy and year, since old interventions may not be useful. Honestly, I’m not sure if I like this change or not, and I am eager for feedback from other interviewees when I test my second storyboard.
7.	Two people mentioned that my presentation would be stronger if it were more personal. To do this, I plan to introduce a story about someone in Togo who has experienced malaria. 
8.	The interviewees mentioned that the takeaways seemed to logically follow the presentation based on how I presented the storyboard, but it may be harder to communicate all of that information in the 60-second presentation.

![malaria 2](https://user-images.githubusercontent.com/56807370/69511699-41239b00-0f0f-11ea-961f-fe5067d2524a.jpg)


# Personas

It was clear after my interviewees offered such targeted feedback that I needed to do a better job identifying my target audience member. So in order to do that I created a persona. Here's what the prototypical persona for my target audience member might look like:

Name: Alex

Year: Second Year Heinz student 

Interests: Arts, policy, healthcare

Knowledge on malaria: Knows it's a mosquito-related disease that affects many people in "Africa." Doesn't have much more granular knowledge on how malaria works. 

How to capture their attention: Exciting information presented in a new way. Has many competing priorities and likely won't give full attention to this presentation if it isn't extremely useful or novel. 

Political engagement: Alex is knowledgable on politics and can name their congressperson and plans to vote in the upcoming election. If Alex is asked to engage with politics, either by calling a politician, voting for a certian candidate, or even donating a small amount of money to a certain person or cause, Alex is willing to be convinced. With that said, Alex is quite busy and would not give up time to go to a rally or engage in a long-term way.



