# Types of Computing

# Overview
In this article, we will learn about various types of computing environments through simple examples.
Computing environments basically consist of software and hardware that can process and carry out computations, such as the device on which you are reading this article is just another computing environment.

Let us now examine various types of computing environments using an analogy. Consider the pizza-making company Domino's. Domino's has a simple business plan: spread the love for pizza all over the world. However, Domino's currently has no outlets. Let us then construct it together🍟

From here onward we are going to consider pizza outlet as a computing resource.

# Personal Computing
Our first Domino's outlet, complete with all of the pizza-making and packaging equipment. We own this outlet; we purchased it and now only pay for electricity, raw materials and operational usage. Similarly, you own your personal computer and pay only for electricity usage and some maintenance after making the initial investment.

![Mind Map 1280x720 px-5.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1670092606782/39wEgl-AU.png align="left")

In technical terms personal computing is a standalone machine, where all the programs completely reside on the machine and execute there itself. Eg - Laptops, mobiles, printers.

# Centralized Computing
Now that we have our first outlet, you should list it on food delivery apps such as Swiggy, Zomato, Domino's App, EatSure, and EatClub. Customers place orders through the app, which are then forwarded to your outlet. You prepare the pizza according to the specifications specified in the order and hand it over to the delivery executive of the respective app. The delivery executive brings the pizza to the customer.

Now here comes the concept of **Client-Server Architecture**, it is simple. Our outlet is server, customers are our clients. We have the computing power to make pizza's while our clients don't have it. Hence they send a request and we serve this request. Overall we call this a Client-Server Architecture.

![Mind Map 1280x720 px.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1670086203664/UyD-_86ez.png align="left")

**As our clients don't have the required equipment (Computing power) for making pizza they are called as thin node. Thin nodes are nodes that cannot function independently and require a central computing resource.**

However, there is a disadvantage to this. What if we are the only pizza delivery service in town and we need to close our outlet at 1pm on Sundays due to a problem? Even if they wanted to, the customers will be unable to order pizzas. This is known as the Single Point of Failure problem, in which the clients are completely reliant on us and any failure in our systems causes the entire architecture to collapse.

# Decentralized Computing
We take a market survey and find that there are many such outlets of various other companies like Pizzahut, La pino'z, Papa Johns, etc. Each outlet does the same task of making pizza, but they have their own equipment, vendors and resources. All the outlets keep a watch on their competition and try to be the best in the business. In this way they are functioning independently but are also connected to each other by monitoring the competition.

![Mind Map 1280x720 px-1.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1670092631671/Vr6ZQk_dQ.png align="left")

Now here comes the concept of **Peer-to-peer Architecture**, it is simple. Let us refer to each outlet as a node; in this case, each outlet has the necessary equipment (Computing power) for making pizza and can function independently without requirement of any central server, as discussed in Client-Server Architecture. Every node takes their own decisions and manage their resources. Just remember the fact that every node does it's own job and they are ***not working collectively.*** Similar architecture is used in Block chain technology. **Thick nodes can function independently and have their own computing resources.** 

We will not suffer from Single Point of Failure in this case because there are many outlets of different companies; even if we close our outlet, people can order pizzas from other outlets.

# Distributed Computing
Now let us take a look at the structure of our business, we prepare pizza at our outlet, we take raw materials required from a groceries shop, we take the packaging material from a vendor, we use electricity provided by electric unit and using all of this resources we achieve out outcome of serving our customer. All of these units can be thought of as nodes; they function independently with their own defined mechanisms, but they all work toward the same goal.

As you can notice in this case we have a common outcome of serving the customer and all our nodes ***work collectively*** in-order to achieve this. Every node does a part of work (either supply raw materials, supply electricity and so on). The work is distributed among all the nodes.

![Mind Map 1280x720 px-2.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1670092644797/c7f-bwWFn.png align="left")

In technical terms distributed system is a group of computer programmes that use computational resources distributed across multiple, independent computation nodes to achieve a common, shared goal.
It uses separate nodes to communicate and synchronise over a common network and is also known as distributed computing or distributed databases.

We assume here that we always have a backup ready in case any one of these service goes down. (We have a backup grocery store to buy raw materials from if our current grocery vendor shuts down). By doing this we avoid single point of failure. 

# Cluster Computing
In order to grow our business, we decided to open multiple Domino's outlets throughout the city while maintaining a central headquarters with a warehouse. All raw materials would be imported to the warehouse and then transported to the outlets after being quality checked. Also, after analyzing previous sales, we discover that some outlets sell less than others, so we allocate fewer resources to them and more to others based on their needs.

![Mind Map 1280x720 px-3.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1670092706107/-ED5ZfI_8.png align="left")

Points to be consider
- All the computing nodes are homogeneous i.e. they have same type of hardware & operating system. (We serve same pizza using the same secret recipe at every outlet)
- All the computing nodes are located close to each other. (Outlets are in the same city, hence they are in close proximity)
- Nodes are connected in a centralized network topology. (Centralized topology between headquarter and outlets)
- Scheduling and resource management is controlled by a central server. (Central headquarter is in control of everything)

# Grid Computing
We are expanding our service across the country, and as a marketing strategy, we customise the pizza based on the city. The pizza made in Pune would be tailored to the culture of the people who live there, as it is in other cities. Instead of headquarter with warehouse, we have storage facilities for each outlet. We've also given outlets the freedom to make their own decisions and even create new dishes to add to their menu.

![Mind Map 1280x720 px-4.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1670092717253/xMjfYCfpm.png align="left")

Points to be consider
- Nodes may have different Operating systems and hardwares. Machines can be homogeneous or heterogeneous. (We serve customized pizza using the different recipe at every outlet)
- Nodes may be located at a huge distance from one another. (Outlets in one city are further apart than outlets in another)
- Nodes are connected in a de-centralized network topology. (De-centralized topology between outlets)
- Scheduling and resource management is controlled by a node itself. (Every outlet has it's own storage)

# Cloud Computing
To put it mathematically, Cloud Computing = Cluster Computing + Grid Computing, where different clusters form a single grid. I've written a separate blog on Cloud Computing that will help you fully grasp the concept. [Click here](https://supernova.hashnode.dev/what-is-cloud-computing) to read the blog on Cloud Computing.

# Additional Resources
Following are some of the additional resources which you can use for further reading.

[Comparison – Centralized, Decentralized and Distributed Systems](https://www.geeksforgeeks.org/comparison-centralized-decentralized-and-distributed-systems/)

[Difference between Grid computing and Cluster computing](https://www.geeksforgeeks.org/difference-between-grid-computing-and-cluster-computing/)

That brings us to the end of this blog; if you find any errors, Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/kalpesh-ahire-430a42192/), [Twitter](https://twitter.com/Kalpesh_Ahire18) 🐦

Keep Learning🌱