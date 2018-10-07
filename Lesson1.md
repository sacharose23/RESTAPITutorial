# How to Make a REST API

### Terminology

* **A**pplication **P**rogamming **I**nterface : something that allows one piece of software to talk to another (e.g. Google's API, Twitter's API, etc.)

* What ^ are are called **Re**presentational **S**tate **T**ransfer APIs (**REST** APIs) . Watch this [YouTube video](https://youtu.be/7YcW25PHnAA) to get a better understanding of some REST API concepts & examples.

* One important concept: Client-Server Model (simply put, a Machine-to-Machine Communication Model)

  * You make a call from **Client** to a **Server** & the Server gives you back data from the **HTTP Protocol**.

    * [**Client**](https://en.wikipedia.org/wiki/Client_(computing)) 

      Definition : "[web browsers](https://en.wikipedia.org/wiki/Web_browser) are clients that connect to [web servers](https://en.wikipedia.org/wiki/Web_server) and retrieve [web pages](https://en.wikipedia.org/wiki/Web_page) for display" OR programs on your computer talking to each other.

    * [**Server**](https://en.wikipedia.org/wiki/Server_(computing)) 

      Definition : "computer program or device that provides functionality for other programs or devices called clients".

    * [**HTTP Protocol**](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol) was introduced in 1991 (my birth year!) 

      Definition : "HTTP is the foundation of data communication for the [World Wide Web](https://en.wikipedia.org/wiki/World_Wide_Web), where [hypertext](https://en.wikipedia.org/wiki/Hypertext)documents include [hyperlinks](https://en.wikipedia.org/wiki/Hyperlinks) to other resources that the user can easily access, for example by a [mouse](https://en.wikipedia.org/wiki/Computer_mouse) click or by tapping the screen."


### Four basic methods we'll make today: 

**C** - create : allows you to create a new X (coded as a **post** method)

**R** - read : allows you to read/show/get a new X (coded as a **get** method)

**U** - update : allows you to update an existing X (coded as either a **put** or **patch** method)

**D** - delete : allows you to delete an existing X (coded as a **delete** method)

*There are other [HTTP request methods](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods) & combinations of such that exist.

**Examples of CRUD apps :** google calendar, evites, facebook posts, etc.



### [What's the Difference between CRUD App & REST API?](https://www.bmc.com/blogs/rest-vs-crud-whats-the-difference/) 

> **Note**: At this moment, I am not too confident on differentiating CRUD with REST. So, we will carry on to our Project with the knowledge that *this* is not quite clear, but it will be soon in the future.



### What Applications Will Need

* Code Editor : VS Code (to write our shit)
* API tool : Postman (for testing purposes)
* Terminal : iTerm2 



### What is Our Stack?

* [**Frontend**, **Backend**,](https://en.wikipedia.org/wiki/Front_and_back_ends) **Infrastructure**, & **Persistence** **Layers** (**databases**)

  * **Frontend**  : presentation layer (what the user interacts with)

    * Tools : Bulma, SASS, VueJS, & Axios (readability, reuseability, )

    * Raw Languages : html, css, javascript

      > Analogy : Designing your Home with raw materials vs. going to a furniture store ; we aren't reinventing the wheel everytime.

  * **Backend** : data access layer (what happens in the background)

    > Analogy : theater (users: audience members, presentation layer : actors & whatever the spot light is on, backend : stagehand folks, developer : director or stage managers)

* [**Infrastructure**](https://en.wikipedia.org/wiki/Infrastructure_as_Code) ([**IaaS**](https://en.wikipedia.org/wiki/Infrastructure_as_a_service) : Infrastructure as a Service): 

  * Examples : AWS, storage locations, web hosts, etc.
  * difference between what is what before and what is now and where it's heading
  * purpose and benefits
  * What is a web server? physically think of a computer, but I like to think about a machine that takes inputs (HTTP requests) and gives outputs (data). Long-running process (always 'ON' and waiting)

* **Databases** : where you store your data

------



* We will be building our REST API using a Serverless Framework
  * Components: NodeJS, AWS Lambda, API Gateway, & DynamoDB. 
* Serverless-offline 



























































