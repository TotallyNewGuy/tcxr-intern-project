# The Commons XR :: 01/2023 - current
This is a briefly introduction of what I did duiring my second internship at The Commons XR (2023 spring).  
I drawn some diagrams to explain my results.  

### [A. Used server-side-rendering to improving website performance](#jump1)  
### [B. Implemented express-seesion to record users](#jump2)  
### [C. Set a secure enviroment for development in Azure](#jump3)  

<span id="jump1"></span>
## A. Used server-side-rendering to improving website performance
▪ Created React components in Typescript with Chakra UI based on Figma design from UI/UX team.  
▪ Utilized Next and Node to do some Server-Side Rendering to improve almost 50% performance.  

![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/TC/CSR.png)
<h4 align="center">Client side rendering make FCP faster but FMP is slow</h4>  

![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/TC/SSR.png)
<h4 align="center">Server side rendering make FMP & TTI faster but FCP is slow</h4>  

![image](https://github.com/TotallyNewGuy/sn-intern-project/blob/main/TC/SSR-d1.png)

![image](https://github.com/TotallyNewGuy/sn-intern-project/blob/main/TC/SSR-d2.png)

![image](https://github.com/TotallyNewGuy/sn-intern-project/blob/main/TC/SSR-d3.png)

<span id="jump2"></span>
## B. Implemented express-seesion to record users
▪ Used express-session and Redis to track users, rewrite URL to pass session ID if cookie is disabled.

![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/TC/login.png)
<h4 align="center">When user login, store session in Redis</h4>  

![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/TC/call.png)
<h4 align="center">When check whether user is loged, check sessionID in Redis</h4>  

<span id="jump3"></span>
## C. Set a secure enviroment for development in Azure
▪ Managed codes in Azure DevOps to work with others and analyze data by Azure Synapse Analytics.

![image](https://github.com/TotallyNewGuy/work-project-diagram/blob/main/TC/azure.png)  
