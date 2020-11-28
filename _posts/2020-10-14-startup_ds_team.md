# Introduction
This topic is interesting for me since I have worked at a company who have put milions of dollars into AI and sees to be failing to get a ROI. What would I do better if I had the chance to change things?
Most of these notes are from different sources eg from podcasts I have listened to, conferences I have attended or books I have read and hopefully gives a good overview about this topic.
- [Podcast interview of Henrik Landgren, founder of Spotify and EQT](https://www.pythonpodcast.com/henrik-landgren-artificial-intelligence-episode-287/)
- [How datascience will drive the next wave of disruption, anacondacon 2017](https://www.youtube.com/watch?v=jx1zqddZM1k&list=PLGB9meziqbzqvly8Skj3qTieC-fSXeR8T&index=17)
- [The drivetrain approach](https://www.oreilly.com/radar/drivetrain-approach-data-products/)
- [The dominion, a neerdy trailer about ds(https://www.youtube.com/watch?v=0XDqc5wTve0&list=PLGB9meziqbzqvly8Skj3qTieC-fSXeR8T&index=3&t=0s&app=desktop)

# When and how is AI useful? 
The buzzword about datadriven descissions is often iterpeted as having a lot of data, look into it and try to find patterns. But taking discisions upon that result often leads to disaster or consumes a lot of time without giving any usable result. One common outcome is to have isolated results where there is a missing link between data and the descissions that are needed. Others put some data-scientist into a room hoping for some magic to happen. -"Show us how good deep learning is, then you get some more money to play with!"
The one who succeeds the best are the ones who understands the market and uses the data to get an even better understanding and use it to leverage the buissnes.
Present dashboards with minimum amount of data that can be uses for taking better descisions eg. Should we continue or not?

The buisniss goals of a company should be reflected in the goals of the data-scientists where everyone is cooperating and insights is distrubuted around the company. The process of working together to a comon goals can be more valuable than the results from the models.
### The loop that is used for agile project execution is about the following:
- Have a hypothesis that points to a goal.
- Implement a solution
- Test the solution
- Measue the result and make some final adjustments.
- Deploy the solution
- Measure and verify if we go towards the goal.

As a result, there is nothing that is called AI, It's just a company using data and models to fasten the loop and make more efficient descisions.

### mini Summary:
- Make sure the DS goals is connected to the buisness goals.
- Make the loop fast!
- I'ts a team sport, work together.
- The process might be more important than the models that is created.



# How do you build a successful DS team
Start by finding a way of collecting both internal(within the company) and external data and store all the data on one place to make it easily accessable.
Then create a pipeline unit for analyzing the collected data. It need to be in a logical fashon meaning that you first have one part with all the raw-data, and clean it to generate more data as input to models. The models generate some further data that can be used by other models. It's really important to make clear from where the data is extracted and where the result is stored, it's easy to make a mess. 
Then you need to make easy to store, test and deploy new models to speed up the loop of experimentations. It's also more easy to add more people into the team using eachothers work if a solid framework is in place.

Use an machinelearning engineer to setup the tools and a data scientist to produce the models. Don't use your best engineers, but use the one who have both the technical and buisniss understanding.
Create clean dataset that can be used in the pipeline.
Make it easy and fast to try out different solutions.

When creating a model, identify which data that are most important for your outcome. Some data can only be measured but to affected (wether temperature) and others you can change. Use your model and change the levers to maximize the result. You can also gain insigt by using the model to isolate effects that otherwize could not be measured.
One compon problem with models is that then can reinforec already known insigts preventing it from exploring new features. eg, if we make a model to prevent crime and it tells us to prevent it eg in suburbs of stockholm. Then all polices are put into place where more data is collected and we are ending up in a loop where we don't look for other patterns. This bias can be prevented by using the models as a guidence and then eg sort the reult manually, find out that it's not logical that all polices are only located at one place.

Another important note is that when putting a human in the loop, then make a feedback to the system about the decision that was made. This will make it possible for the algorithms to learn from the humans and continously improve.

# How do you know if it's worth starting a project.
Make sure you have enugh data.
Most tasks are too easy to solve with other methods or too complicated where humans need to be in place.
It starts to become interesting when the models and humans are working together. Models are good at finding patterns in huge amount of data while humans are good at eg differentiating between causality and correlation and taking other aspects into accound that cant be fed into the model.
When the humans have made there descision, put that descission into the loop again giving feedback for the models for improvement.


# future of AI.
We have so far mostly used AI as a prediction tool. There are other tecniques out there to generate new data eg using [gpt-3](https://www.youtube.com/watch?v=gDDnTZchKec) for generating text and we have also seen a lot of fake videos. This will definetly be part of generating new content, eg websites, articles etc, but also to do fraud. 



# Others
It's very common to use AI tools and mostly concentrate on the algorithms of the tool. But it's also important to understand the psycology of the tools. It needs to be a help for the humans not a burdon. Some have implemented an algorithm to predict the workload of the humans to only as questions and get feedback when they have time to give it. If it feels like a burdon, it will be miss-used, you will get bad data and the overall functionality will fail.



