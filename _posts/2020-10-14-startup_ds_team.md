# Introduction
This topic is interesting for me since I have worked at a company who have put milions of dollars into AI and sees to be failing to get a ROI. What would I do better if I had the chance to change things?
Most of these notes are from different sources eg from podcasts I have listened to, conferences I have attended or books I have read.
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

When creating a model, identify which data that are most important for your outcome. Some data can only be measured but to affected (wether temperature) and others you can change. Use your model and change the levers to maximize the result and to get a better understanding by isolating effects that otherwize could not be measured.

# How do you know if it's worth starting a project.
Make sure you have enugh data.
Most tasks are too easy to solv with other methods or too complicated where humans need to be in place.
It starts to become interesting when the models and humans are working together. Models are good at finding patterns in huge amount of data while humans are good at eg differentiating between causality and correlation and taking other aspects into accound that cant be fed into the model.
When the humans have made there descision, put that descission into the loop again giving feedback for the models for improvement.







26.45
2 syften med platformen. göra beslutsprocessen så effektiv som möjligt. bygga modellerna för att göra detta.
Om vi tar reda på vad som behövs för att göra beslutsprocessen effektivare och effektivare lär man sig vilken typ av data som behövs när den lyckas/misslyckas.
Varje evolution för varje månad

dashboards- som besluts verktyg, vad behöver de veta för att kunna ta ett bra beslut?

hur ai används:
gpt3 generara text med jälp av seed input.
generera information, deep-fake videos.
största misstag med AI. twitter agorithmen, väljer ett ansikte och väljer ansiktet och croppar till de.
om det är flera ansikten, algorighmen väljer vita killen ansiktet.

Man kommer förstärka BIAS in sin träningsloop. Hur kommer man bort från detta? Man indexerar på andra saker än vad algorighmen föreslår. t.ex att man kikar på diversiteten på sina teams.

psykologin i platfromen så att man faktiskt använder sig av verktyget. Om det inte är enkelt att använda verktygen 
Vad är personens arbetsbörda, är persoenen arbetsbörda, ge inte mer infromation om han inte är klar på andra sidan så att man får 


agila tänkandet, börja smått skala upp!


checkout data engineering podcast


anacondacon 2017:
https://www.youtube.com/watch?v=xrYMfbcv3-c&list=PLGB9meziqbzqvly8Skj3qTieC-fSXeR8T&index=2

the dominion

Data sicence: 2017
https://www.youtube.com/watch?v=jx1zqddZM1k&list=PLGB9meziqbzqvly8Skj3qTieC-fSXeR8T&index=17

book ultra learning
7:30: vanligaste felet, man anstället ett gäng data-scienteits, stänger in dem i ett rum och hoppas på att något magiskt skall hända.
för att lyckas:
1. team sport. uppgiften skall spegla företagets mål, vi hjälper varandra, insikter distrubueras över företaget så att man kan utveckla verksamheten
2. Processen kan vara viktigare än modellen: genom att man systematiskt utvecklas kan även en misslyckad modell vara grunden till en förbättrad verksamhet
3. Hastighet otroligt viktigt: När det gäller att testa en hyppotes och få ett svar är det viktigt att loopen är snabb. 

insight driven buisnezes

om man har en modell kan man 
1. hämta (mer)data
2. skaffa insikter
3. testa och implementera insikter i mjukvara
4. mäta resultatet och justera implementationen
5. identifiera utfall och följ metrics
gå tillbaka till nr 1

snabbheten i denna process är viktig.

trycker på att man inte skall köra "datadrivert" dvs vilken data har man, undersöka denna och därefter köra lite.
1. De som lyckas känner till marknaden.
2. De samlar ihop den data som de har och försöker skaffa kunskap som de tror har relevans
3. de implementerar insikterna och testar dessa vilket genererar mer data och oftast mer insikter (24.00)

31:30
data: insikter: actions decisions

https://www.youtube.com/watch?v=0XDqc5wTve0&list=PLGB9meziqbzqvly8Skj3qTieC-fSXeR8T&index=3&t=0s&app=desktop
