---
layout: essay
type: essay
title:  Master Key to Coding Problems
# All dates must be YYYY-MM-DD format!
date: 2020-12-03
labels:
  - Javascript
  - Coding Standards
  - Design Patters
---

<img class="ui medium right floated rounded image" src="../images/master_key_diagram.jpg"> 

When learning how to code and write programs, there is always a set structure that you want your code to follow. As said in my previous essay about coding structures, “Coding Standards, an Unwritten Written Rule,” we follow a general structure when coding because it allows the code to be more universally understood and usable. One simple example is how different languages format specific parts of their own code. When using Javascript you are able to initialize a variable without specifically telling the program what type of variable it is, like if it is holding a string or integer. But in other languages, such as Java, you need to explicitly define the type of variable. Programs have their own specific instruction on how to format their code, without it, it will have too much ambiguity and the machine will not be able to understand or run the code. We can take a step back and look at a few design patterns that are present in most languages. These design patterns, compared to what I mentioned previously, are generally more universal since they are patterns used to solve common problems in coding. Four common and well used are: Factory, Singleton, Observer, and MVC. It is important to know these design patterns because they are like a master key to a building, they are made to be able to help solve almost any problem. So running though these design patterns can help spark a solution to a problem you're facing.  

The first design pattern is Factory. The idea is that when you create new objects, you do not explicitly define what type of object it is and give it the ability to return multiple types of data back. This allows for more possibilities when creating a singular object and eliminates the excess amount of code when needing to multiple returns from a singular object. Javascript uses this design when initializing variables, as said above. We can create one variable and have it hold a string, int, float, etc. We wouldn't necessarily think that when creating variables we are using this design pattern since it is something so simple, but when you use it you notice how versatile it makes variables in Javascript vs. other popular languages. 

Singleton uses the idea of creating only single instances of classes so we know that anything created and used in this class are the only instance, meaning that it can be used globally and is correct. This is nice because we are able to run a set of code once, and be able to use its data elsewhere. An example of how I have used this is when I run a meteor application, it goes through and initializes the available data the app will run off of given the collections. In our study-ext application, we have a collection of default users which contains data of all the users in the program. When we open the application locally, we can use and access the different parts of the application and see how the program works, but this collection is only initialized once at the initial run of the program and is used throughout the different functions. 

The observer design pattern is built around the idea of objects reacting to the outcome of other objects. This can be helpful since we can use this to create better decisions to unexpected or unwanted outcomes. The Java exceptions are a good example of this. It uses the structure of trying a block of code, and if it does not work then catch it and throw an exception. Java exceptions are very useful because it can let you run blocks of code without it terminating because of an error, helping you figure out what is going wrong in your code. 

Lastly, is MVC (Model-View-Controller), separating the code for the visual user interface from the database. This concept is widely used, but not really thought of because it is universal to most languages. One example of this on my current project study-ext is the separation of visuals from the background database and collections. Our application used meteor react to display our visuals and create the interactable mechanisms for the user. But we also have other collections and publications to give our application data for the user to work with. This separation allows for code to be thought of and worked on in two generally separate parts. 

After going through these design patterns, it is easy to see how even though they seem foreign at first, we are already using them in our own code. This proves the point that they are practically universal design patterns, even though you may not feel like you are using them, the general idea of them is always going to be present in any program. 
