# No design without research

This is the script for the presentation I gave at the Libre Graphics Meeting 2019. The slides are available at https://belenbarrospena.github.io/no_design_without_research_lgm2019


Hello everybody. My name is Belen, and this talk is about a pet peeve of mine: the relationship between design and research.

I guess the first thing I should do is to define what I mean by design and what I mean by research. For the purpose of this talk, design is interaction design: the branch of design that deals with the structure and behaviour of software user interfaces. Interaction design is what you are doing when you make decisions about features: about what your software should do and how it should do it. And defined in this fashion, interaction design applies to all kinds of software, and also to all kinds of interfaces, and not just the graphical ones.

And for the purpose of this talk, research is any act that brings the people who use software into the process of making that software. Research is about getting your users involved in the interaction design work.

Can design exist without the research bits? Does design really need research?

At the university where I do my PhD, I am surrounded by people who think you should not be doing design without doing research. But in free software circles, I often come across  people who express certain wariness, hostility and even downright rejection to this idea of doing research as part of the process of designing software. Those I call the naysayers. Based on their arguments against research, I’ve come to classify the naysayers into 4 groups: the itch-scratchers, the scornful, the dismissive and the defeatist. Let’s go through them.

The itch-scratchers are the people who develop software to solve a problem they believe to be solely their own. Since this is my problem, they say, the only one I need to do research with is myself. Others can choose to use my software if they wish, but in the understanding that my software is about my problem, so it might not be perfect for them.

Although there is a certain logic to this argument, I think it is somehow detached from reality. You see, when you develop a piece of software to scratch your own itch, the itch is your itch as long as you are the only person using the software. When someone else starts using your software, the itch is no longer your itch: it is now 50% your itch, and 50% someone else’s. When a second user comes along, the itch is now about 33% yours. With a 3rd person using your stuff, the itch becomes 20% yours. Do you see where I am going with this? The percentage of your itch shrinks exponentially as you add users. By the time 50 people are using your software, the itch is only 2% yours. You may choose to ignore this reality and keep on telling yourself your itch is your itch, but I am afraid you will be deluding yourself. If you really want your itch to remain yours, you must keep your source code to yourself. The moment you make the source code available to the world, you are giving away your itch. The moment you release your code for anybody to use, you must come to terms with the fact that your itch is unlikely to remain yours for long.

The second type of naysayer I call the scornful. The scornful claim people do not know what they need or want, and that designers are better positioned to determine such things than people themselves … as if designers were somehow a more enlightened or evolved kind of human, one that has managed to overcome our inability to articulate our true wishes, and our incapacity to predict our own behaviour. 

I am sure I don’t have to convince you that those who believe that designers are in possession of some kind of super-power, or are in any way superior to other humans, are kidding themselves. Designers are as incapable of articulating their needs and wants, and as incapable of predicting their own behaviour, as anyone else. As designers, our only super-power is the recognition that this is so. That overcoming this quintessentially human limitation requires time and effort, and that certain tricks of our trade, like iterative prototyping, and design research, can help us overcome this problem. 

The third type of naysayers I call the dismissive. The dismissive claim that, if you ask people their opinion about anything design related, every single person will tell you a different thing, and the designer will be left responsible for making sense of the mess. They will have to deal with not just different, but often opposite design requirements, that may very well be impossible to reconcile. Those will lead to complete paralysis or - god saves us all - to the dreaded design by committee. 

The dismissive seem to be under the impression that design research is about asking people what they like or dislike, or just what they think about something. But design research is nothing like that at all. Design research is a highly structured activity, carefully set up in order to answer specific research questions: things we want to learn more about. And the object of study is not peoples’ likes, dislikes or personal opinions: the object of study is human behaviour.

In our drive to understand human behaviour, sometimes design research involves talking to people and asking them questions. But those questions are never directly about the stuff we are designing: they are about the problem our design is trying to address, about the context and circumstances within which the problem exists, and about the ways people solve that problem today, which are often quirky and highly imaginative.

And a huge chunk of design research does not involve any question asking at all: it’s all about observing. Observing how people go about their business, how people tackle certain problems, and yes, also observing how people use our software, what we often call usability testing.

In such observations, we do come across the fact that humans are highly individual, and they go about their business in slightly different ways. But across such diversity, strong commonalities exist: patterns and affinities and sameness. Those are the things that are often extraordinarily useful to designers, and are the things we need to hunt for when doing design research. So design research is not about making sense of people’s different opinions: it’s about uncovering the commonalities that underpin individual human behaviour.

And finally, we have the defeatist. They argue that design research just takes too much out of you: too much time, too much money, too much effort. Because of that, it is unsuitable for free software projects. I imagine that, for the defeatist, the word “research” must conjure images of expensive labs with one-way mirrors and fancy cameras, big longitudinal studies, and years-long ethnographic endeavours that result in 10,000-word peer-reviewed papers. These are the things academics do, because they are trying to develop theory. But hang on a minute: we are not trying to develop theory. We are just trying to make some software, for crying out loud!

Here comes the truth about our kind of research, research that is fit for the purpose of making software. Let’s start with how much time does research take:

6 interviews is enough, and 5 usability tests is enough. Our research sessions should not last over 45 minutes, which means a usability study takes 3 hours and 45 minutes to execute, and our interview studies can be done in 4 and a half hours

Now, let’s look at how much money research costs:

Tons of research can be done remotely with things like Jitsi at 0 cost.

Research can be captured by recording audio and video with things like OBS at 0 cost.

And we don’t need to pay money to our research participants: there are other ways of doing things. Free software projects tend to have committed, interested users, and it is very likely they will agree to take part in research just for the sake of it, just to help you and your project. In the end, many of us contribute our time to free software for pleasure. Well, taking part in research is a way of contributing to free software as well, even if we are not used to looking at it that way, and it can also be done for pleasure.

There are also all kinds of interesting ways of compensating participants other than giving them money: from swag to free training. As part of my PhD I often recruit research participants through an organisation called the University of the 3rd Age. In exchange for helping me with that, the organisation doesn’t want any money: what they want is training on things they are interested in. So far we have organised training for them about Facebook’s privacy settings, GDPR and about web third-party tracking. So ask your research participants what they want in return for their contribution, and together you may find new ways of thanking them for their time.

And finally, let’s see how much effort to make sense of the research findings and report back:

Analysis can be done in teams using the affinity diagram technique, a light-weight version of what academics call “thematic analysis”. But because the studies are small, you can probably also analyse the outcome yourself in a couple of hours.

Research findings can be quickly disseminated through online presentations or webinars, videos or podcasts, and through brief documents like blogposts, wiki pages and emails to mailing lists.

If it looks like you can’t answer your research questions doing a study like the ones I’ve just described, break your research question down into smaller, simpler research questions, and organise several small studies instead of a single massive one. You will probably learn more from those mini-studies than by running a huge one anyway.  

Get into the habit of doing research periodically, for example, do a user interview per month. Your insights will build over time as you do more and more of those. After all, free software projects are usually not in a hurry - they don’t need to beat others to market or crap like that -, so you can take your time with the research too. 

And remember, design research is first and foremost an attitude, an attitude you bring to every single encounter with your users. An attitude of genuine interest that translates into detailed observations of human behaviour. Immerse yourself in the environments of your research subjects: hang out with them, listen to what they say and watch what they do.

For me, when I was designing tools for software engineers, this research as attitude approach involved starting using IRC, learning Git, learning how to submit small patches, using text editors to do so, playing a bit with electronics, learning how to solder, and having lunch every day with the software engineers in my office. This is what I call research inspired by ethnography, and you know what? It’s completely free, and it’s also a lot of fun. 

So don’t let the itch-scratchers, the scornful, the dismissive and the defeatist discourage you from doing research. Put on your observing hat, and get out there to uncover the mysteries and quirks of your users’ behaviour. Because sure we can design just software without research. But we cannot design good software, the kind of software that makes sense to the people who use it, without getting our hands dirty with the research bits.
 
