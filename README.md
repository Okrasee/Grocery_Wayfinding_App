# Grocery Wayfinding App - UX Design
<img src="/profile.jpeg">

**Human Factor Fall 2018 Final Project**, September - December 2018 <br>
**My Role:** Research, Sketch, Prototype, UI/UX <br>
**Keyword:** Design, Research, User Experience, User Interface, Mobile App Prototyping, Grocery Shopping, Navigation, Indoor Positioning <br>

## Introduction
It is sometimes hard for people to find the items they want in a grocery store. Either it takes too long or the customer simply could not locate the item. College students usually do not have much time to spend on grocery shopping. So I come up with this idea of helping people, especially young people, **do grocery shopping in a more efficient manner**. 

## Solution
Create an app that 

* **gives user visual guidance;** 

* **sort user’s shopping list.**

## Interaction
<p align="center">
  <img src="/feature_1.gif" width="245" />&nbsp;
  <img src="/feature_2.gif" width="245" />&nbsp;
  <img src="/feature_3.gif" width="245" />&nbsp;
  <img src="/feature_4.gif" width="245" />&nbsp;
</p>

## Features Walkthrough
#### 1. Offer the full list of selections
* When the user inputs his target item, a list of relevant products would show up.  The list displays basic information including the name, price and rating of the item.
* When searching for products, user could narrow down his/her selections by using the filter feature.
* When similar items are placed on different shelves, one may miss some of them if he does not check all of these shelves. However, if user searches in the app, all similar items would appear on the list to optimize the range of choices.

<img src="/feature_5.png">

#### 2. Display a map of the store
* The app shows a map of the store layout. The orange pin stands for the location of the shelf that the target item is on.
* The map could track the user’s precise location empowered by indoor positioning technology and provide him with the shortest route to the product.
* Shelves are usually crammed with items such that people may not be able to spot the item instantly. With this app, however, he could view the specific location of the item on the shelf. The product is marked orange to be differed from other products on the shelf. The orange section of the bottom bar indicates how far the person is away from the product.

<img src="/feature_6.png">
<img src="/feature_7.png">

#### 3. Create a sorted shopping list
* When opening the app, the user would be directed to a screen which asks him to pick the store in which he will do grocery shopping. The app would then design the shopping route according to the distinctive layout of the store that the user has picked.
* The shopping list is automatically sorted by aisle and arranged by store layout which creates the most efficient shopping route. By following the shopping list, the user could avoid running back and forth in the store. 

<img src="/feature_8.png">
<img src="/feature_9.png">

#### 4. Inform unavailability of a product
* People would waste time searching in vain if they do not know that the product is actually not available in store. To prevent this, user could check the availability of an item in the app. 
* If it is not available, the app would suggest a list of similar products as alternatives.
* Besides suggesting a list of similar items, the app would also provide a list of stores that have the target item in stock in case the user really needs it. 
* The user could get the basic information of the stores that offer the target item, and could also set it as the home store in order to access the store map.

image seven

## ***Design Process***
### Task Analysis
I undertook a task analysis process to break down the grocery shopping procedure into small steps and gain a deeper understanding of the problems my users may face.
### User characteristics
#### Who are the users?
People who
* do not have much time to do grocery shopping
* would love to find their target items as quickly as possible
* may have difficulty with finding the products they want
* are not familiar with the store layout
#### What are the users’ goal?
* They shop for products needed for the following week(s)
* They may already know what specific barcoded item (like x brand x pasta) they want
* They may be looking for any type of pasta
* They also want to try things which worth giving a try though they do not intend to buy 
#### What are the equipments and supplies that help them perform the task?
* Shopping List
* Giant Eagle Advantage Card
* Credit/Debit card or cash
* Basket / shopping cart
* Reusable bags / backpack / utility shopping cart
* Phone
### Environment conditions
Big grocery stores which offer all kinds of products needed in daily life. Products are usually grouped by category and crammed on one shelf. But similar products may also be distributed among separate areas in the store. There are aisle signs to guide people to the shelf that their target products locate on. Each store has a different store layout. The stores are crowded during weekends in the day. One could ask an employee for help (e.g. ask for the location of a product or check availability) or go to the customer service. 
### Actions Required in Sequence
image eight
I further divided the second main task into smaller components since this is the major task that I want to analyze.
image nine

### User Study
I asked my users to shop for the following week while I observed how they collected the items they wanted. During my observation, I found all of them made several mistakes. And I also interviewed them with regard to their shopping experience and habits.

#### User 1 
#### "I do not have the habit of heading up to look at the aisle sign."
His problems:
1. Run back and forth between shelves
2. Run back and forth in the fresh produce section 
3. Leave the cart unsafe
4. Shopping list not prepared by aisle
5. Ignore cheese of smaller size
6. Ignore the aisle sign 

#### User 2
#### "I could not find Morton sea salt. So I searched again by looking at every item on each food-related shelf."
Her problems:
1. Skip the shelf
2. Fail to identify the category of the target item
3. Search by item per shelf
4. Honey of different flavor placed in different aisles

#### User 3
#### "I searched for a long time without knowing that the hold-fast glue was actually not available in store. And it took a while for the customer service to confirm it."
Her problems:
1. Leave the right area
2. Ineffective check with the customer service

### Key Insights 
The problems I observed through user study could be categorized into four groups:
image ten

### Human Factor Concepts & Display Design Principles
1. Eliminate resource-demanding cognitive task and reduce the use of user’s mental resources;
2. Avoid absolute judgment limits;
3. Present limited information to minimize access cost and avoid similarity issue
4. A use of visual element;
5. Redundancy check

### Ideation + Sketches
image eleven

### Prototype Iterations
I created mockups based on my sketches and went through two iterations before landing on my final prototypes. Improvements were made to elevate the aesthetics of the interfaces and increase functionality of the app.
image ten
1st iteration
image eleven
2nd iteration

### Final Prototype Overview
image twelve

### Tradeoffs
* Implementing an app may be costly because it takes time and effort to polish the design, maintain the system and update it. The app also needs to be promoted to increase its use among popularity.
* The target users scope is limited. Although this app is designed targeting at young people, it would be good if it could help people of other ages. However, this app could not help old people who are not used to play around with phones. So if old people have trouble finding items in the store, this app could not help solve their searching problem.
* Think about Giant Eagle as a stakeholder, it would not welcome this searching and sorting app because people would not wander around in the store and buy a lot they have not planned to buy.   

### Further Improvement
* I am thinking about marking sections in the store by different color to make the store layout more clear. I will conduct user testing to find out if this design is better than the current iteration.
* My current app interfaces focus on making pathfinding more efficient when people do grocery shopping. However, there are other issues that could be improved. For instance, the app could inform customer about offers and discounts near their position. I could do a more thorough user study to find out other problems and add new features to this app.
* My next step is to implement an AR navigation feature by using ARCore and Android Studio since I have some experience with building Android app. My idea is that the app generates a virtual path that leads the user to the product.  I believe displaying spatial navigation information is more intuitive than a 2D map. Here is a prototype:
image thirteen
