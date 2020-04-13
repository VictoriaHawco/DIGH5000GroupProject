# DIGH5000FinalProject
A place for our DIGH5000 Final Project paradata

## Paradata Document

### Origins
The following project originated as a final assignment for our Carleton University Intro to Digital Humanities class. The goal was to work collaboratively on some kind of DH project, and the limits surrounding what we could do were purposefully vague – the whole of the DH spectrum was open to us. 

### Goals
We as a class talked about our interests, about what other DH projects inspired us, and what tools in DH work we ourselves were interested in messing with. What we all settled on quickly however, was to design some project that could relate to Ottawa’s hosting of the DH2020 conference. Several ideas were proposed – some sort of virtual space to view DH projects, or perhaps to just talk about DH projects, even some sort of interactive map of Ottawa showcasing DH projects. What we settled on eventually, however, brought together our desire to showcase Ottawa projects with a couple DH techniques of interest to us all: topic modelling and network analysis. 

As we learned over time, topic modelling was a way to quickly and succinctly analyse larger swathes of data for trends. The unique part of it is the availability of the topic modeller to set the parameters: we could set how many topics we wanted modelled, exclude certain terms or phrases, and in doing so receive notably different results. This was attractive to us for a couple reasons: we could manipulate sets of data in different ways and look and think together about why the results were different, and what in the data and the parameters gave that different result; and additionally we could quickly analyze a large amount of data.

With our goal of turning a spotlight on Ottawa based academics and DH projects, this meant we could input papers and project briefs written in or about Ottawa and find the frequency of topics. We could tap directly into the Ottawa DH scene, and look at where and when people were talking about what, and how they were talking about it. We could track trends in digital humanities work in Ottawa over time, and look at what words and phrases showed up over and over again to discuss it. Some academics might use different terms to describe the same phenomenon, for example. At the very least, we felt it a valuable method to look at how academics discussed different topics and which ones they felt were of the most interest or import. 
Our goal was not to pass a judgement on what was being discussed or how it was being discussed. We did not look at this project with the goal of finding potential blindspots in DH in Ottawa, for example. Instead, we thought it an interesting avenue for thought and discussion. We were all of us new to digital humanities, and this project would give us a crash course in the modern DH scene, so we could quickly become acclimated to what was going on, what people were talking about, and how they were talking about it. 


### Project in Brief
After a couple design discussions, as we grappled with what this project might look like, and why we wanted it to look like that, we settled on a design matrix. First though, it is important to discuss why that above sentence matters. Our discussions were of course in part impacted by the origin of the project, namely its purpose as a marked component for the course. We knew we needed to produce something (or rather work towards producing something), and so our thoughts of what the project would look like were coloured by that. We had thoughts of building something useful, something that touched at some core aspect of DH, but those thoughts themselves could impact the project in a potentially problematic way. Essentially, it was not our intention to build a results-oriented project. Instead, as we learned what topic modelling and network analysis were and what they could do, we realized it was an excellent way to analyze DH data for discussion. We of course recognized that the setting of parameters was in a way a results-oriented approach, but our goal of merely discovering something new about the data we felt was at the forefront of the project. 

Moving now to the results of those initial design discussions, we knew at first blush we would need large amounts of written data; we would need papers and project briefs of DH data if we wanted to have anything to analyze. The project evolved into two steps, then: research and analysis. We needed collectively to spend a good number of man hours scouring the web for papers written by Ottawa based academics, or projects conducted in or about Ottawa. The project was front loaded labour-wise. 

Then, we would transfer the data into text files. Those text files could be run through a topic modelling program, which could be tinkered with as much as we desired to produce different results. From there, we would move to Gephi and play around with that, seeing what we could make of the data we produced.

A few words on network analysis: the reason network analysis was attractive to us as the second of the one-two punch of our project was that it provided a different and unique way to view our data. Network analysis is a much more visual output than topic modelling. Instead of reading what essentially is a report on the frequency of words, Gephi and network analysis can show the interrelatedness of terms in a data set, and can be manipulated to show the strength of the relations and the complex network of terms in the data set. 

### R and D, But Mostly R
We initially split into teams: one team would be focused on hunting and gathering the data to run through the topic modelling, as the other team familiarized themselves with the basics of topic modelling and Gephi for when that would become necessary. It became clear very quickly however just how front loaded the project was. What we mean of course is that the research was going to be most lengthy portion of this project, while the rest of it would, barring unfortunate technical – or as it turns out, social – complications, turn out relatively quickly. Instead of our two-teamed approach, we instead all jumped on the research bandwagon.

In order to find Ottawa-oriented projects, we employed a variety of research methods. A lot of our gathering was borne from word of mouth – we would hear about projects from our professors and colleagues, as well as from sources like Twitter. Additionally, we mined our university libraries conducting keyword searches. This did introduce an interesting element of bias – no matter how much we might endeavour to search a variety of terms, we still might have missed areas of research or academics simply by not keyword searching broadly enough. We additionally mined the research bibliographies of university professors in the city or known academics in the region. Many academics produce works in the DH sphere without noting it as such.

Over the course of a number of weeks we all read numerous papers, project briefs, and project webpages, combing through them until we had a number which we felt would produce valuable topic modelling data: the number we slightly arbitrarily settled on was around 50. We read, tracked the bibliographical data, and converted projects we felt were suitably DH into text files, collected in a shared google drive.

From there, the text files were cleaned up for random punctuation or formatting errors. This was done to ensure when the data was run through the topic modelling, it would not produce any anomalies. This was easier said than done, and a few running attempts stalled as we cleaned up our data. Similarly, our attempts at topic modelling were stalled as we had to carefully ensure the order of documents matched the way they were written and formatted in our bibliographic .csv file. Failure to do so yielded no results for our analysis, and so everything had to match up. An easy and achievable goal, but also a little like building a puzzle only to realize you’d unknowingly put a piece where it didn’t belong and were left with one piece that didn’t fit. Combing through for the one error in a sea of punctuation and project titles was time consuming but necessary. 

On a personal note, this came to be a sort of hallmark of our work on this project for us. Aspects of it were time consuming but necessary, and the solution to our problems was often just to go through everything again but more slowly. Despite this, the Ah-Ha moment when something works and you finish tinkering around on a computer was ultimately very satisfying for us.

### Interesting Times
We had finished collecting our data sample and were in the middle of that time-consuming-but-necessary work when something unusual and unprecedented happened. It happened to all of us at the same time, and halted our ability to bash our collective heads into the keyboard in person. We are speaking, of course, of the necessary social distancing and self-isolation measures enacted in Ottawa in early March 2020. Our meetings in class were cancelled, and we held digital meetings over our group Slack space to come together and try to work things out. 
Keeping in touch became difficult, so we really relied on our standard meeting time every Tuesday. But even that, even working more generally on the project, was a unique challenge which man of us were unprepared for. Working on school work, even when it is interesting and engaging work (no matter how occasionally complex or NBTC it may be) in such interesting times was hard. It was hard to focus on work, hard to make deadlines, both personal and professional. Even when nothing was wrong other than self-isolation (and many times in many cases, there were serious personal issues we had to overcome), it was hard to overcome the distraction of the daily news feed and the anxieties it produced. 

No matter how much easier it is to work in uninteresting times, that was not our allotment, and we were committed to finishing what we started as much as we were able, which we all recognized at the outset of these new events that “as much as were able” might look different than we thought it would at the beginning of our time together. 

### The Forest and the Trees
Nevertheless, over our digital meetings we came together over two weeks to finalize our topic modelling and work with Gephi on producing network analysis visualizations.

When we initially were able to input our data set and actually produce legitimate results (meaning not tainted by misplaced punctuation in the .csv file or anything of the sort), we had to have a conversation on the parameters we would set. As discussed earlier, setting parameters is a way to inflict some personal academic bias on the data set. If we set our parameters to display a certain number of topics, say 15, and we don’t like the results and change the parameters, that is necessarily passing judgement on the results we achieved. It is saying that there is something in those results that were not “good enough”, even if we did not concretely establish what “good enough” looked like. As a result, we attempted to try a variety of different parameters, constantly changing and adjusting for the number of topics displayed per work to showcase different results. Over the course of several different trials (see below images) we adjusted for number of topics, and tried removing numbers as a topic as well. 

 
![](Topic%20Modelling%20Trial%201.png))

 
![](Topic%20Modelling%20Trial%202.png)

 
![](Topic%20Modelling%20Trial%203%20-%20no%20numbers.png)

 
![](Topic%20Modelling%20Trial%204%20-%2010%20topics.png)

 
![](Topic%20Modelling%20Trial%205%20-%2012%20topics.png)


One of the reasons we wanted to adjust for different numbers was that we weren’t sure which would produce more interesting analysis: fewer topics or more. Would fewer topics showcase the more general trends within the data sets? Would this yield more interesting results, as we could see what the general and more frequently used beats of each work were? Or would more topics allow for a broader analysis, and potentially then greater opportunities for connections between each. Ultimately we hunted for that Goldilocks number – the one that would not have so many topics as to be vague and not too useful, but have enough to generate a broad range of points of analysis for comparisons sake. 

Clear trends are visible from looking at the images. Some works are clearly oriented towards new media such as the internet, social media, and games. Some are focused on music generally, and focused on the social aspects of music and of sound. Some focus on specific elements of digital work, like data and coding itself. Still others are focused on more broad social trends like gender and sexuality. 

At this point in the data we had to settle on actual topics to import our data from there to Gephi. The tricky thing was, there is no metric to meet for “accuracy” of our topics. We had no idea if the topics we settled on would prove to be the most accurate, or the most useful or produce the most interesting results. Choosing our topics involved a lot of discussion and even more compromise. There were certain nuances that had to get paved over while others received emphasis because we deemed them important. A few of the papers we believed skewed the data set, for example Jada Watson’s paper heavily influenced our decision making regarding Topic 7. In this way, bias entered the picture: the articles and projects we chose heavily influenced the topics the software presented us with, which impacted our network analysis. Eventually we settled on a few topics to move forward with:

0 = Digital Humanities
1 = Data Studies
2 = Culture Studies
3 = Linguistics
4 = Archaeology
5 = Utopian Studies/Game Studies
6 = Geography
7 = Gender Studies/Music
8 = Indigenous Studies
9 = Poetry
10 = Queer Studies
11 = Discourse Studies

After settling this issue, we were left with one final topic model.

 
![](Topic%20Modelling%20Final.png)

From there, we moved to Gephi. This was difficult, especially due to the interesting times our work was conducted in. Gephi was unfamiliar to all of us, and it was a little bit like learning to ride a unicycle. Some aspects of it are almost familiar, like clicking and unclicking boxes, setting parameters, inputting data. But still others are confusing, and the ones that look familiar often are to do unusual things and must be used in specific ways or else we produce what we ended up humourously calling “the blob” – a supposed network of data nodes and connections that was so broken in its construction it was a solid mass instead of a readable network. It took time, some brainstorming, and throwing ourselves at the Blob over and over again.
  
![](Network%20Analysis%20Trial%201%20-%20the%20Blob.png)

 
![](Network%20Analysis%20Trial%201%20-%20Blob%20on%20the%20Move.png)


One of the problems we came up against was getting the right matrix to convert our data in the way we needed it to. Eventually, we formatted it such that the left matrix: null – true the topics, and were met with something much more palatable for our project:  
![](Network%20Analysis%20Trial%203%20-%20Pointy%20Blob.png

The pointy blob! We clearly still were missing something; either something was not formatted correctly, or the inputs on our matrices were not correct. Either way, we were not producing anything of value yet. Again, our goal was to produce a visualization of the interesting points of our topic modelling, which kind of rested upon providing a visual network that we could read. 
Slowly, and with a good deal of trial and error on the party of our party who were taking point on Gephi, we got to a point where we had something more readable. We continued tinkering, particularly in order to find a way to label all our nodes. 

 
![](Network%20Analysis%20Trial%204%20-%20Getting%20Closer.png)

Eventually we transformed what we had into a one-mode graph by culling all the topic information that was previously listed, so the only aspect of our data table were the titles, then we were able to produce more viable results by going into the overview menu and selecting the “Fruchterman Reingold layout in the bottom left panel and running it.

 
![](Network%20Analysis%20Trial%205%20-%20One%20Mode%20Graph.png)

We still had the problem of labelling nodes with author and date information, however, particularly in a way that would not look chaotic and would not mess up our model. We settled on trying an index system, marking the nodes with numbers and providing a separate way to look up the labels of the nodes to get the full information connected to each. 

Eventually, by working with the data set and parameters like it was Play-Doh, we were able to produce more readable graphs. These showed connections between various labelled nodes and the relative strength of each connection. For example, media studies and game studies were quite strongly connected, and media studies was connected to lots of different nodes. Comparatively, archaeology had fewer connections, and while connected to a few different nodes was only very weakly connected to the node of linguistics, for example. 
 
![](Network%20Analysis%20Trial%206%20-%20Readable%20Graph.png)

Once again, one of the things of note with our project is that our selection of the data points impacts the results we get; certain connections might appear weak because we did not find existing projects that would have otherwise strengthened the connections.. This can be understood as a way to read the kinds of work going on in Ottawa, however. If there is a kind of DH work not found in our project or with weaker connections, it could be a fault of our research, or it could be simply a blind spot or not a concern of Ottawa based academics. This is interesting in and of itself – the lack of something, or the silence of an area or the lack of connections indicates the relative presence of that kind of work within Ottawa. 

After more tinkering with a larger amount of our data, we had two readable graphs with different numbers of connections presented. Looking at the two options, we decided the readability of the graph superseded showing those other, smaller points of connection.
 
![](Network%20Analysis%20Trial%207%20-%20Final%20Graph%20Option%201.png)
 
![](Network%20Analysis%20Trial%208%20-%20Final%20Graph%20Option%202.png)

We continued to work on it, messing around with edge visibility and the weight of connections. In doing so we were doing much the same sort of work as with our topic modelling. We were trying out different methods and slightly changing different parameters to see what we liked. we had to confer as a group each time, as we might all have a slightly different idea of what “good enough” looked like, and this was interesting in and of itself as well. Clarity was of most importance to our group it seemed over the course our conversations. Focused on showing the connections, finding ways to colour the lines based on weight as well, and colour group them based on modularity/connectedness.
 
![](Network%20Analysis%20Trial%209%20-%20Colour%20Weighting.png)

This part of the project, and working with network analyses in general, was a little bit like seeing both the forest and the trees. Both the connections between the nodes (their relative strength and weight) and the nodes themselves were important. They both said something interesting about the data set, namely what was being talked about and what was it in connection with. That said, in our project we found clarity became more important than variety. In this way, we picked the forest, not the trees. We focused more on readability, on showcasing the relative weight and strength of the connections between the nodes than anything else. We still tried to strike a balance, showing the trees/nodes as well in their variety, as that was in part the fruit of our topic modelling, but it was the visualization of the connections that seemed to be of most interest to us. 

### Conclusion(s)
Over the course of the semester, surprisingly, coming up against unfamiliar technologies and establishing a project we were interested in and proud of proved to be the least of our problems. Though still difficult and at times frustrating, our goal of producing a topic model and network analysis based on Ottawa connected DH work was ultimately doable. It was more research centred and research heavy than I think any of us knew about initially, but in that way it was incredibly interesting to get to real all about the DH projects going on in our city. The biggest challenge we faced was not technological of course. The current health crisis has impacted us all in different ways, some serious, some merely inconvenient, all anxiety-inducing. Nevertheless, we continued to work on our project best we could till we could produce something that interested up and was a focal point for discussion on DH projects.
It was and has been interesting to us to think about the specific kinds of projects produced in Ottawa, namely heritage based projects with a variety of different emphases such as sound, indigenous rights, and education. 

As explained earlier, we took care in the construction and follow-through of our project to avoid taking a results-oriented approach and inflicting bias. This meant trying not to impact parameters looking for a specific result when topic modelling, and trying to include as wide a variety of projects as possible to produce as honest results as possible when looking at Ottawa based DH work. The potential for bias is in itself interesting – our ability to inflict parameters that will produce specific results, and the gaps in our network analysis as potentially a result of research or potentially a result of availability, are interesting to think about. Thinking about DH projects across the world, what DH projects are underrepresented in Ottawa? Why? Or what connections between DH projects are common across the field more generally? Or those connections, or lack of typical connections, unique to Ottawa? What does that say about Canadian practice of DH, or even Ottawa-specific practice of DH? Further work would need to be done to say anything about the distinction between our Ottawa based-analysis of DH projects and DH work more broadly. 

At the very least, then, it is fascinating to consider what the climate of DH is like in Ottawa, and our work on topic modelling and network analysis provides a valuable into that subject. 
