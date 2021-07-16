# flow-element-template

Base template for the creation of doFlo elements. 

## Element Template Walkthrough

Congratulations, if your reading this you've likely decided to extend the doFlo platform by building a custom doFlo element. This documentation will walk you through the configuration, file structure and code so that you have the information needed to do build and deploy your first element.

### What is a doFlo element ?

In its most basic form an element is a succinct proxy to a service and its related capabilities. In most cases this represents a 3rd party service and actions that can be preformed via an API or WebService and / or WebEvents (webhooks) that can be consumed and ultimately responded to.

Multiple components make up the element 

#### What is an Action



## Repo Layout Explanation

* readme.md - this file 
* doflo.jsonc - element config file
* remote
  * src - source code for server side actions (nodejs)
* client
  * connect
    * src - source code for client side UI elements (reactjs)