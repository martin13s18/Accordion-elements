# Accordion-elements

NOTE: This task is working asynchronously with practice server!

An html file is given and the task is to show more/less information for the selected article. 

At the start is made a GET request to the server at adress: http://localhost:3030/jsonstore/advanced/articles/list where the response is an object with the titles of the articles.

By clicking the [More] button for the selected article, it reveals the content of a hidden div and changes the text of the button to [Less]. 

The content is obtained by making a GET request to the server at adress: http://localhost:3030/jsonstore/advanced/articles/details/:id where the response is an object with property id, title, content. 

When the same button is clicked again (now reading Less), the div will be hidden and the text of the button to More is changed. 

Link action are toggleable (you are able to click the button infinite amount of times).
