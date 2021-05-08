# How I explained REST to my brother

1- Who is Roy Fielding?

- He’s a smart guys who helped writing the first web servers, that sent documents across the interne ; and then he did a ton of research explaining why the web works the way it does. His name is on the specification for the protocol that is used to get pages from servers to your browser.

2- Why don’t the techniques that we use today work well when we need to be able to talk to all of the machines in the world?

- Because they weren’t designed to be used like that. When Fielding and his colleagues started building the web, being able to talk to any machine anywhere in the world was a primary concern. But most of the techniques developers later used to get computers to talk to each other didn’t have those requirements. You just needed to talk to a small group of machines.

3- What is the HTTP protocol that Fielding and his friends created?

- it’s a proctocl about applying verbs to nouns. For instance, when you go to a web page, the browser does an HTTP GET on the URL you typed in and back comes a web page.

4- What does a GET do?

- Get used to get data from a URL and then render them on the web page.

5- What does a POST do?

- it add something to another system.

6- What does PUT do?

- It replace something in another system .

7- What does PATCH do?

- it do a partial update in the system.
