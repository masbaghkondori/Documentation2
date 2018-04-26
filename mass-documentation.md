# **Apache Camel**

## :point_right: ***first step:*** [watching this simple example on youtube:](https://www.youtube.com/watch?v=jZE-YSHK_gw)  
## :star:**Features:** 
### *-Camel is a Java library to routing and mediation,so you can easily wire up tests in whatever unit testing framework you use (JUnit 3.x (deprecated), 4.x, or TestNG). However the Camel project has tried to make the testing of Camel as easy and powerful as possible.* 
### *- It has component make interacting between many [endpoints](http://camel.apache.org/component-list.html) very simple.It moves and transforms messages between [endpoints](http://camel.apache.org/component-list.html) like FTPS, Twitter, Google drive, etc.*
### *- Apache Camel on its transforming way can do some functions like Filtering, routing, logging, tracking orchanging format.*
### *- There are so many [endpoints](http://camel.apache.org/component-list.html)/components like Google Calander, Google Drive, FTPS, Twitter etc.*
### *- Every endpoint has own APIs or function to action between that endpoint and another one.*
### **Example:** The statement below read something from whatever to Twitter.
### Searching using a producer with static keywords

```
from("direct:foo")
  .to("twitter://search?keywords=camel&consumerKey=[s]&consumerSecret=[s]&accessToken=[s]&accessTokenSecret=[s]"); 
  ```
  

### If you want to do these things 
#### *. moving a file or message from the file system like FTPS* 
#### *. searching a file in a file system* 
#### *. moving it back to Twitter*  
#### We don’t need to know how twitter works. or understand that API  
#### Every one of [endpoints](http://camel.apache.org/component-list.html) supports many parameters like type, move, and so on
#### To do addressing to [endpoints](http://camel.apache.org/component-list.html) is used a “from” and a “to”
#### Between any “from”  and “to” we can do any steps like * .process * or * .transform * or whatever you want.



