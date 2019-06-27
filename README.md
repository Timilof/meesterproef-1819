# Meesterproef minor web-dev 18-19

![Final app](/img/app_final_v3.png)


## Case
In the final assessment of the web-dev minor I worked on the case for Semia, Semia is a collaborative group with researchers from the Eye film museum in Amsterdam working together to produce an immense database of films.
I worked on this project together with three other students: Jeroen van Berkum, Leonie smits, en Martijn Reeuwijk. We all had different learning goals we aimed to meet while working on the project but still worked hard together

In the five weeks we made an application with you you could navigate through the film data in an explorative manner. targeted towards researchers and artists working with film, the application allows the user to view shots related to one another based on color, movement within the shot, shapes recognised in each frame and visual complexity of each shot. The user is able to put together a path of shots relating to one another in many interesting ways, creating link where previously there weren't any.

Product repo link maybe? idk


## Learning goals
Leaning on the concept

### BT
- Progressive enhancement
Werkt ook in oudere browsers, als nieuwere browsers ook dingen zoals animaties key frames

- Feature detection
Wordt ingezet om de juiste PE te doen.

### CSS To The Rescue
- applying a clean css and make the app responsive as far as necessary

### WAFS
- Code structuur
Standaard van het team aanhouden (met prettier)
SPA met code in modules
Work in modules

### Web Design
- Principes toepassen
- User needs
User story.
Product testing
Doing research into which features are definitely necessary based on user needs.


### Week 1
In week 1 we were intorduced to the Semia project and everything that came with it. The dataset, the people we would actually be developing it for and the history of/progress that had already been made in the project.

We were shown where the interests of the product owners were, how they had been experimenting with the data given and what their expectations were for us.

![Final app](/img/schets_1.png)
first sketch I pitched to my team  

Early on we weren't sure what we'd like to develop and spent the first two days thinking up strategies and concepts. I did a deep dive into many data driven apps and other mediums and got inspired by the Bladerunner 2049 Film where there's a scene wehere in the main character is navigating through a huge data set with great speed and expertise. I thought it would be very interesting if our users would be able to do that with the film data we had been gifted. I pitched the idea and a simple sketch to the team and after brief discussing and arguing about what and hows I promised to make a short animation clip with a goal to help explain the workings of the application to my teammates and potentially to the product owners as well (after further discussing and approval by teammates).

![Final app](/img/exp_v1.gif)
First concept I animated to help explain to product owners  

The concept I pitched was gladly accepted and we started planning out how to build something like it. I felt the decision making process went too quickly and we didn't experiment and do enough research into whether the workings, features and goal of the app where in line with the goals and expectations of our product owners and of the team as a whole. I am proud of the app we made but it would have been nice to be able to back up all our design decisions by showing how we experimented and research we conducted. Still I believe the concept is strong and durable.

At the end of the week we didn't speak to anyone to note progress or any problems because of a public holiday so we had our first progress on Tuesday of the second week.


### Week 2
In week 2 we spoke to Luarens who noted our progress and gave us quick feedback of our application which was still in its most primal stage. He saw potential and noted our individual learning goals for the project.


During this first week we made a clickable prototype and started completing the first api requests and set up the server.

We also had the opportunity to speak with Nanne, the man responsible for the creation of the huge dataset wherein all individual shots were linked to other shots. A very cool learning moment where we were shown what was possible with the data, the actual complexity of the dataset and with this we were able to get a grip on the possibilities and limitations.

The rest of the week was spent setting up the server and actually getting the backend into place.


### Week 3
In week 3 I focused on the frontend because the app was starting to take shape and desperately needed a frontend to reflect it.
I took main responsibility over the UX aspects thinking of in which ways the users should be able to interact with the data and how the interface should look and behave, a lot was influenced by the backend so I didn't really have a lot of flexibility but I was still pleased with how much i could do.

After speaking with Vasilis in week 3 I came to understand that the interface wasn't as friendly as I thought it was and he made it known that he had expected a more exclusive design approach to the app than I had implemented thus far. I had intended to apply exclusive design principles (and did) however Vasilis thought I would use the same techniques i had used to create keyboard events with which you could navigate the app. I didn't do this due to shortage of time, means and the level in which the app functioned. We had barely built in the core functions and I didn't feel it was a priority to build these features if the core wasn't sufficiently ready yet.

In this week I made a test-able prototype with which i tested a feature with peers and our product owners.
You can view the prototype [here](https://oege.ie.hva.nl/~folit001/proef_semia/)
The tests i run showed that there was a preference for displaying the preview in an overlay view instead of expanding the page to show the preview.

In week 2 I had spoken to Laurens and made a comment about learning what the user needs were and indexing them to get a better understanding of what features were truly necessary and which were nice-to-have. Then at the end of the week we spoke with our product owners and Cristian Olesen (one of the main figures in the Semia project from the Eye film museum) and to them we proposed a product test in the coming week. They consented and we picked a date where we would be able to test. This was great because then we could get to know firsthand what actual stakeholders and people of interest thought of the product so far and what their expectations were.


### Week 4
Spoke to Laurens on Monday, it was a nice talk because the app had really taken shape and we could actually show and talk about the content and workings of the app and we could start thinking about how we would fix certain things that weren't yet working.

Mainly worked on the interface and making it scale to smaller sizes and had been working on a tutorial screen which would explain the application to first time users.

The test at the Eye film museum archives was by far the highlight of this project, having so many experts view what you've made and give their expert advice and opinion on each function and working of the app. It was extremely valuable and we learned a lot, not only about our app and in which ways it was good or lacking but also more about the data we were actually working with. Some of the test subjects were professors and could tell us so much about the type of film we were looking at and in what ways the shots were related to one another.
It was very cool to be able to do that.

After the extensive unit-test we headed back to school where we processed the feedback/criticism and made plans to tackle each point.
The rest of the week was spent finalising and fine tuning features and adding and removing where necessary. We found out how much work we actually still had to do to be able to be content with the app and be able to present it comfortably. At the end of the week we were spoke with our product owner again and showed the changes we had made since the week before and showed where we wanted to take the final version.

### Week 5
In this week we worked non stop to finish the documentation of the project and I especially focussed on styling the frontend to make it not-break on the smaller desktop screens. Also worked on the icons because we received feedback that they weren't clear so i redesigned them and put them in the application. Worked on the tutorial because the content had changed last-minute and also worked on the end-screen of the application which holds all of the users selections and gives the user time and space to view the videos in peace without having the constant loop playing in the background.
Helped Leonie with the poster for a tiny bit but otherwise spent time fixing things I had overlooked.
Was a very short and intense week because we had to present on Thursday and still were implementing things on Wednesday night.
Happy to be able to present the application though because I am proud of what we've made and can't wait to see what the product owners think of the final result of these past five weeks.


## Reflection
For my personal Reflection (in Dutch) click [here](https://github.com/Timilof/meesterproef-1819/blob/master/refelctie.md)
