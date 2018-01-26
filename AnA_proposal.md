Archary & Arcana
Team Dungeonmaster
Team Members: 
Michael Foust, Jonathan Redington, Ronald Randolph, and Michaela Shoffner

Archery & Arcana is a text-based role-playing game inspired by the classic 
Dungeons and Dragons role-playing systems, as well as the more recent Etrian 
Odyssey games. Players will create one or more characters from a number of 
available races and classes, and then venture into dangerous dungeons where 
adventures await them.

We hope to enable co-operative play for anywhere from 2 to 5 players, both 
because it would be an interesting challenge to implement and because it would 
be pretty neat if we can get it working. In addition, the dungeons they will 
delve into will be largely procedurally generated, allowing for every venture 
into a dungeon to be wildly different from previous ones.

We decided to do this project for a couple of reasons. Working with client/server
connections and sockets seemed like something helpful to our possible future jobs,
and we didn’t have any projects related to it in our previous classes. It would 
have quite a few parts and features that could be added or removed depending on 
how progress goes, such as multiplayer, multiple maps and areas, variety of 
options in encounters, and cleverness of the text interpreter. Finally, it simply
seemed like a really fun project, and it’s always easier to be motivated when 
working on something you enjoy.

Our project is not especially new. Many existing games out there would have far 
more features with a smoother interface, as well as all the older text-based 
adventure games that this will most resemble. However, we hope to add some new 
interest to an old form, by using a system that will eliminate one of the 
largest issues experienced by tabletop players, which is that the Dungeonmaster, 
who is playing the part of the storyteller, as well as all non-player characters,
has to manually choose actions for each and every non-player character in a 
scene. Therefore, large-scale or multi-front conflicts and scenes become tedious,
as the Dungeonmaster can spend minutes making sure every character gets their 
turn. However, we are operating through a computer, and, having eschewed 
graphics, our memory and processing overheads will be greatly reduced, allowing 
us to manifest significant processing power to reduce this off-turn time to 
near-minimal levels.

Our team comes from broadly similar backgrounds since we’re all at about the same
point in our classes. Michael Foust has a couple of years experience in C++ and 
enjoys playing role-playing games. Jonathan Redington is an amateur game 
developer with several of his own games currently in the works, has a couple 
years’ experience with C++ and Java, as well as an interest in artificial 
intelligence and role-playing games. Ronald Randolph has had multiple years of 
experience with C++ and has an interest in machine learning and artificial 
intelligence. He is currently developing a few iphone applications both in swift 
and react native. Michaela Shoffner has a couple of years experience with C++, 
tends to be good at writing understandable/documented code, is happy to draft 
papers/reports, and loves role-playing games of all variety.



Our primary customers would be anyone interested in playing a simple adventure 
role-playing game that they can play with friends. Since our initial attempt 
will be have either few or zero images/graphics, it won’t be for anyone who 
places a high value on the look of their games.

Our primary customers are individuals who want a nostalgic DOS game like Zork. 
There are not many games like this in the market today despite there being demand
for it. As an example, the original Super Mario Bros. game is still popular, even
among people who didn’t grow up playing it. In response to this, Nintendo has 
ported many old NES, SNES, and Nintendo 64 games to modern systems. While we don’t
expect our game to be as polished as Mario or to have the same success, we 
believe that our game will have a place in the market. 

Through Archery and Arcana, we hope to provide players with a satisfying local 
multiplayer RPG experience. Our game will not dazzle players with fancy graphics.
We intend to utilize the limited medium of text to allow ourselves to flex our 
writing muscles to create an interesting story that uses mental imagery rather 
than presented imagery to tell its story, allowing for creative interpretations 
on the players’ part, be they comedic, horrifying, or even something else 
entirely.

The original motive of Dungeons & Dragons and other role-playing game systems was
to create a set of rules within which players could forge their own story with 
their own characters. This context was beneficial to newer players because, even 
if they didn’t have a particularly strong characterization, they could at least 
still be helpful to their friends regardless, meaning they could join in on the 
fun, even when playing with veteran role-players whose characters were far more 
clearly defined. It also provided incentives for said veterans to play with 
newer players aside from the desire to share the fun of role-playing with others,
as many role-playing game systems encourage cooperative tactics to overcome 
obstacles that could not be dealt with if each player was acting only by 
themselves. This mechanically-reinforced spirit of camaraderie is one of the less
publicly-acknowledged traits of the genre, but to players it is certainly 
unforgettable once it has been encountered. Therefore, we intend to implement 
local area multiplayer in order to allow players on the same network to join 
forces in the game and therefore experience similar adventures to those 
encountered in traditional tabletop games.

Our replication of the tabletop experience is not entirely duplicative.
There is a well-known way to massively slow things down in tabletop play sessions:
having one or more characters leave the main group and go their own way, 
literally “splitting the party”. This is troublesome for the players and 
Dungeonmaster (the person who is playing the part of both the storyteller and all
non-player characters) because now both the main group and the new, smaller group
now have to each take their turns and actions separately, potentially having 
entire fights all on their own while the players in the other group sit idle, 
unable to do anything.

However, using the turn-taking model we plan to use, this issue will be 
non-existent, as every non-player character will already be taking their turn 
between player turns, but they will be doing so according to the computer’s 
decisions, which can be made quickly enough that any resultant delay will likely 
be minimal unless insanely massive quantities of non-player characters are 
present, an edge case which is easily preventable.



Our software should, at the highest level, allow the player to find and connect 
to other players, explore an area, and encounter and fight monsters. Some of the 
main components will include: the client and server background implementation, a 
clean user interface for menu and travel selections, a means of tracking where 
the user has gone and providing a map accordingly, and a different combat menu, 
for use when confronting an opponent.

The minimum we want working is basic text descriptions of what’s happening, a 
single area to explore, some basic monsters to meet, and a working interface for 
a single player. Beyond that, we intend to add as many additions as proves 
feasible during the time given. These would include adding different areas, 
increasing the variety of monsters, making the text generator more 
creative/varied, and, naturally, getting multiple players functional.

Most early testing will simply be some of us playing around with it and seeing 
how it reacts to what we do, and fixing issues as they are encountered. Once a 
good baseline is established, we will bring in people not involved in the project
to act as beta testers, and see how it works for someone who has no clue how it 
was made. Both friends and family will be useful for this step, and they will 
advise where things could be improved or made more intuitive.

We intend to use primarily/entirely C++ to create this system, since that is what
the team is most familiar with as a whole. While it may be easier to implement 
nicer interfaces in a different language or system, this is what we know and feel
we can work with for the purposes of this class, hence why it will be largely 
text-centered. However, as this is largely an older genre of game development, 
we’re not hopeful about the existence of helpful libraries that we would be able 
to utilize, and have been planning thus far to be writing most, if not all, our 
code from scratch. If we do later find useful libraries, we will happily 
incorporate them, but as of right now we are planning this to be a “deliberate 
practice” project.



As far as relevant skills go, the entire team has taken up to CS302, and two 
members (Jonathan and Michaela) have taken CS360 as well. As a result of 
everyone’s experience with CS302, we are all quite comfortable with the graph 
data structure, which is how our gameworlds will be stored, so that will prove 
quite helpful on that detail. Jonathan has programmed a couple dungeon generation
engines in the past, although in different contexts, as well as the core 
mechanical components of a role-playing game, such as accounting for all the dice
rolls and skill checks that will need to be carried out. Michaela, while not 
having done as much directly related, has tried out planning and designing a 
small text-based adventure in the past. Ronald has had previous experience with 
version control and utilizing many useful features of github. 

At this point in time, the planned roles are to have Jonathan and Michaela focus 
on the transmission code that will be used to communicate between the server and 
clients, while Ronald and Michael create and polish the input parser and 
description generator. The remaining components, i.e. the dungeon generation, 
save file storage, and combat mechanics will be allocated at a later date.

At the moment, we are planning to distribute the workload based on relative 
experience, as half of the group has taken Systems Programming, where the sockets
we will be using to implement multiplayer were presented and described. The game 
itself will be broken up into a client and server program, and responsibility for
each part of those will be distributed as interest and availability warrant.

Before each sprint, we will be assigning a component or two to each group member,
which they will then be held responsible for at the end of the sprint.

