 One of the primary things you need to know about Nodejs if you are a beginner is that it understands javascript. Why is that a thing? 

Because before nodejs, only browsers understood javascript. Every browser had a different way of understanding javascript. Just like humans understand English differently - different vocabulary, different speed of comprehension. But thank god, in most of the cases, browsers understood the same thing and acted in pretty much in agreed ways.


But then again, without a browser, the machines didn't have a way of understanding javascript. Enter NodeJS.

Be it your laptop or some machine in Amazon's servers, there are certain advantages if you can talk to it and program it to do tasks for you. This is what all programming languages do. But your machine is a chunk of hardware - some processing power and some storage. They don't understand nearly anything you say. For you to talk to it you gotta teach it how to understand some languages -  this is what "installing" NodeJS means. So, in essence, NodeJS is a way to talk to your computer in Javascript. 
Here's how to do it: https://nodejs.org/en/download/

> NodeJS helps your machine understand javascript




**Same language everywhere**
NodeJS had certain advantages when it comes to developing web-apps. Main thing is that programmers didn't have to shift between different languages to talk to browser and local machines. 



**It makes machines work harder**
Secondly, it makes use of a computer's processing capacity better:
There are cases where the server has to talk to some external system to do the job it is requested of. When this happens the server pauses all activities and wait for the information to come. This is like the idle villager in Age of Empires. 
![Idle Villager](idle_villager.png)

This obviously isn't the best way of making use of machines. So people have tried to find ways of avoiding the idle villager scenario. But none has been as successful as NodeJS. 
NodeJS does such actions via asynchronous calls ("Woo..o_o"). 
This simply means that nodejs server requests some other server (database server for example) for some info and since nodejs server already know that the database server is a slowpoke, it moves on in life and does next what can be done.

Now, this poses problems of its own. And people have come up with innovative ways to work with this (Refer: [[Managing Asynchronous Calls]]). Certainly the advantages of asynchronous systems far outweigh the complexity involved in managing them - in most cases at least.

**It is nourished by a large and generous community**
English wouldn't be English if there were not so many books and movies made using it. NodeJS also has large amount of content published using it. But that's not it. 

- **There are people enthusiastic about sharing their understanding**
Here in stackoverflow there are 131,578 results at the time of writing on nodejs. Somewhere in there most of your questions will be answered (You just need to find the right words). If not, ask away. You are very likely to get an answer. 

- **There is code written which you can readily make use of**
For example, you want to search a PDF for text using a Nodejs server. Here's someone who has done majority of the work for you: https://www.npmjs.com/package/pdf-to-text
Not just that, this someone has shared their work in such a way that they will quickly teach your nodejs server how to do it:
Just say `npm install pdf-to-text` in the right place
This makes your nodejs server a learning machine of a machine
![Sharingan](tenor.gif)


**It's popular. That's enough sometimes**
Whatever be the reasons, NodeJS is popular. For any language to be useful, it has to be understood by more people and systems. The momentum has favored javascript and nodejs. They have built on each other's popularity. Now, javascript has reached everywhere. [Even space](https://www.youtube.com/watch?v=J5VECXgTpWk).
This makes it easier and easier to use javascript to get real stuff done. Facebook and Google have shared a chunk of their knowledge and philosophies through ReactJS and AngularJS. All adding to the usefulness of nodejs and javacript.
