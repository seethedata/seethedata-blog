+++
date = "2016-02-14T11:36:14-05:00"
draft = false
title = "3 signs that Data Cupid has misfired in your relationship with IT"
disable_profile = true
disable_widgets = true
+++
Note: A special thanks to [Stacey Panco](https://www.linkedin.com/in/staceylpanco) for providing the inspiration for this piece.
	<hr/>
	<center>
![Data Cupid](/images/data-cupid.png)
	</center>

Like it or not, most of us are in a deeply committed work relationship with our IT departments. As with all relationships, things work best when both parties involved are working to provide the support each side requires. Unfortunately, when it comes to data part of that relationship, many people feel more like the victims of an arranged marriage gone wrong rather than a spark-filled love connection.

If you are wondering if it could be possible to have a more fulfilling data relationship with your IT read on and see if any of the following items sound familiar.

#### 1. When you receive the result of a data request, you still have a huge amount of work to do before you can decide what action to take.

Ah yes. Just like getting a Visa gift card for your First Anniversary. Here's some generic plastic money - YOU figure out what you want. 

Over the past few decades, organizations have trained themselves that the only commodities exchanged between a business stakeholder and IT should be "report requirements" and "reports".  While these descriptive dashboards and trend charts certainly have their value, business users today need to be able to directly ask real business-level questions like...

* How do I reduce customer churn?
* What staffing do I need to have next Tuesday night?
* Where should I be spending my marketing budget?

...and more importantly, receive real business-level answers from IT like: 

* Here is a list of customers most likely to churn in the next 3 months and recommended actions for each one as to what will retain them.
* Next Tuesday night is predicted to have a 25% increase of foot traffic, so you should schedule 2 additional associates.
* You should divert spending from campaign X to campaign Y because campaign X has shown no impact in the first 3 days ad campaign Y has raised 10% more revenue during that same period.

You'll notice a couple of themes in all of these answers. Firstly, they are all focused on what **will** happen, not what **has** happened. Secondly, they not only give a prediction, but also they provide recommendations to the business stakeholder as to what actions they could / should take. Providing this insight and recommendation pair is infinitely better than simply pushing a bunch of charts and graphs across the table.

Another common theme is that these are **decisions** that a business stakeholder needs to make and not just a description of the data that they are requesting. As buzzword-y as the term may be, this is the true value of Big Data Analytics. It allows us to raise the level of conversation in our data relationships to truly give business stakeholders actual data-driven direction and not just raw information.



#### 2. When you make a data request that is "exactly what you want", you are redirected to a "standard report" that supposedly has "most of what you are asking for."
You said you wanted an Apple Watch for your birthday - but this wall clock tells the time too. Isn't it great?

Congratulations. You finally have figured out the exact sets of information you need to tackle (and conquer) that big project you are working on. All you need is to see customer information linked with product revenues by date, by region, and by customer loyalty level for the last 6 months, so you put in a request. Unfortunately, you are the "very first person to ask for this" so it will "take a while to get everything updated to support this new requirement", or worse "the system just isn't set up to do that." Don't fear, however, because weekly report #7 shows customer data for the past 4 weeks by color with revenue aggregated by age, which is close enough for what you asked for, right?

This is another facet of the "report-based economy" that organizations have created for themselves. While this is certainly a frustrating experience, the thing to understand about most Business Intelligence and Data Warehouse systems is that the number one design goal is **not** flexibility ; rather, it is providing answers that are 100% accurate. These systems were originally developed to help produce reports to answer questions like:

* How much money did we make last quarter so we can properly report our earning to the SEC?
* Which distribution centers were most overutilized / underutilized in the last year?
* How many of our field agents achieved or exceed their quota for new customer acquisition in the last 6 months?  And how did each geographic region do?
* Did we sell more green ties or red ties to people between the ages of 35-45 last holiday season?

The key to all these questions is that we will want to ask them over and over again and we always want the results to be 100% accurate. Because of this, most data warehouse systems have strict formats and several data cleansing processes that weed out bad data. The benefit is nice, clean, predictable, trustworthy reports. The downside is it makes changes very expensive, be it time, money, or both.

It's important to note that the reason for your struggles is not that the data warehouse model is outdated. Far from it! The results it provides is probably running most, if not all, of your business! However, when it comes to arbitrary, ad hoc, or uniquely creative ways of looking at data, the designs of these systems will fight you all the way. This is where new data architectures and approaches are needed to support these kinds of activities to allow flexibility and speed to action. Within the industry, these new styles of operating are often referred to as "Data Lakes" and "Big Data Analytics".  Both are designed to support answering rapid, creative, and unique questions and the focus of their design is that "Speed to Action" is more important that "100% Accuracy". If I can be 87% sure that this is the right action to take, that is plenty sure enough for me to execute. 

For a more in-depth discussion of this comparison, check out my colleague Bill Schmarzo's excellent blog on [comparing Data Lakes and Data Warehouses](https://infocus.emc.com/william_schmarzo/how-ive-learned-to-stop-worrying-and-love-the-data-lake/).


#### 3. When you receive the result of a data request, it is already too old to be useful.
Just because Hallmark has an entire section of "belated" cards doesn't mean that you are supposed to use them.

The data warehouses that we have been talking about are batch-oriented in nature. This means that they expect to be able to reload information on a periodic basis and there will definitely be a time for "loading things" and another time for "reporting on things". As various parts of your business strive to move faster and faster in the reactions you have with your customers or other business units, sooner or later the concept of "real time" (or at least "right time") becomes more important. 

When "real time" requirements within projects start showing up, the first thing that most people ask to the IT folks is simply "get me my reports faster!". IT usually can make some tweaks here and there early on, however, very quickly the batch-oriented design of the data warehouse begins to strain as data sizes grow and as more things look to achieve real-time or near real-time results. The reason for this is that most real-time analysis is accomplished by processing things as they show up, so that we aren't processing very much at any one time. In order to retro-fit this model to a data warehouse, we must create smaller and smaller batches to keep up. Yet, this is counter to the way that data warehouses are designed. This design optimizes things when batch sizes are **large**, and until things are sufficiently big the optimizations cannot help. 

Too often what ends up happening is that projects with real-time components end up slowing down to the point where they are no longer useful, and then they are abandoned all together. The business returns to the "report-based economy" and as a result, suffers from slow reaction times.

With the architectural designs of a Data Lake however, real-time analysis is not only possible, it is commonplace. Without the burden of guaranteeing 100% accuracy, the speed with which things can be processed is dramatically increased. We can now respond to our customer's activities on Twitter, proactively identify and respond to fraud, or adjust resources in our ERP system as orders enter into it.

#### Epilogue 
If after reading this you find yourself feeling like your relationship is doomed , fear not! Just as in personal relationships, good communication is the key to happiness. Most IT organizations that I speak with feel like they have so much they could provide their business customers, but the business folks just don't think to ask questions at a business level, even to the point where IT thinks that the business folks don't even know what they want. As crazy as it sounds, you could try having a business conversation about what it is you are trying to accomplish (instead of just identifying what technical stuff you think you'll need). If you focus on telling IT what it is you are trying to **do** rather than telling them what you **want**, you may be pleasantly surprised that they have a whole stack of technology that you didn't even know existed to help your cause. And if they don't have it, who better to help you vet out the multitude of options out there? 

Of course, if things don't go well, there's always couple's therapy via things like [EMC's Big Data Vision Workshop](http://reflectionsblog.emc.com/how-we-teach-customers-to-use-big-data/). 



<hr/>
<center>
Care to comment? Please share your thoughts on Twitter [here](https://twitter.com/seethedata/status/709153429806030848).
</center>


